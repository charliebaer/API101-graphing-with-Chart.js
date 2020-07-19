
# API101-graphing-with-Chart.js

The following code is a continuation to https://github.com/charliebaer/api101-csv

The code uses the dataset from the nasa and displays "Zonal annual means, 1880-present, updated through most recent complete year" which is in CSV format.


1. line chart displays the characteristics from difference of global mean (1880-2018).

2. The global mean is around 14°C (57°F)

3. note that the type of 'temp' is string and not a number, so I have used parseFloat() which is a global JS function that takes strings and turns them into a number 

4. I tried my best to finish both the functions without depending on each other and act independently, its the main reason I did'nt declare any variables on global scope(instead returned the objects in the getdata() to the Chartit())

5. To sum it all up 
 - we loaded the tabular data in the form of CSV file
 - parsed it manually
 - repackaged that data with Chart.js
 - displayed that data using HTML canvas

The chart ultimately displays the rising global temperatures over the years 

   ![Alt Text](https://64.media.tumblr.com/465a1503e3d6aee271d51d7ca640a555/tumblr_o3anu2fe3H1r83d7lo4_500.gifv)

Btw the chart renderings from Chart.Js are **smoooooooooooooooooooth** AF..like **Jiggly smooth** 

![Alt Text](https://64.media.tumblr.com/ffc7a8b52a8d9280c198095ab453a3d9/tumblr_msioidFy2d1qh59n0o2_500.gifv)

PS. I just learned that you can add gifs in your repos' decription

Nasa dataset : https://data.giss.nasa.gov/gistemp/

Chart.js : https://www.jsdelivr.com/package/npm/chart.js

documantation to Chart.js : https://www.chartjs.org/docs/latest/

