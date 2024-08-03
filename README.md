<h1 align="center">Get to know Citi Bike </h1>
<h3 align="center"> See the sights. All of `em.</h4>

<div align="center">
  <img src="Images/readmeimage.png">
</div>

	
<h1 align="center">Analysis Summary</h1>
  
  <h2>Background </h2>
  <p> 
    Citi Bike is the nation's largest bikeshare program, with 25,000 bikes and over 1,500 stations across
    Manhattan, Brooklyn, Queens, the Bronx, Jersey City, and Hoboken.
    Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data 
    on the program's utilization. Each month, bike data is collected, organized, 
    and made public on the Citi Bike webpage.
  </p>
  
  <h2>Key Insights</h2>      
	<ol>
		<li><strong>Total Rides</strong>: The total number of rides in 2023 was 338,231.</li>
		<li><strong>Member vs. Casual</strong>: Members accounted for 80% of the total rides.</li>
		<li><strong>Peak Months</strong>: June, July, and August were the peak months for bike usage.</li>
		<li><strong>Peak Days</strong>: Tuesday, Wednesday, Thursday, and Friday were mostly peak.</li>
		<li><strong>Peak Hours</strong>: 5pm to 7pm were mostly peak.</li>
    </ol>
 
  <h2>Analysis Summary </h2>
  <!-- Best Times-->
  <h3>Peak Times </h2>
    <ol>
      <li><strong>Season</strong>:<a href="Images/RidersBySeason.png"> Sumer season is the peak season of the year.</a></li>
      <li><strong>Months</strong>:<a href="Images/RidersByMonth.png"> June, July and August months are the peak months of the year.</a></li>
      <li><strong>Day</strong>:<a href="Images/RidersByDaysofWeek.png"> Tuesday, Wednesday and Thursday are the most peak days in the week.</a></li>
      <li><strong>Days of month</strong>:<a href="Images/RidersByDaysofMonth.png"> Almost all the days are same except weekends</a></li>
      <li><strong>Hours</strong>:<a href="Images/RidersByHoursofDay.png"> 4pm to 7pm are the most peak times of the day.</a></li>
    </ol>
       
  <!-- Best Areas-->
  <h3>Popular Starts & Ends </h2>
    <ol>
      <li><strong>Best Area</strong>:<a href="Images/PoupulerAreas.png"> West side of the city is most popular for the rides.</a></li>
      <li><strong>Most Popular Station</strong>:<a href="Images/MostPopularStation.png"> W 21 St & 6 Ave is the most popular station for both start and end the rides.</a></li>
      <li><strong>Top 10 Starts</strong>:<a href="Images/Top10StartsLoc.png"> Most popular 10 start stations.</a></li>
      <li><strong>Top 10 Ends</strong>:<a href="Images/Top10EndingLoc.png"> Most popular 10 end stations.</a></li>
    </ol>
   
   <!-- Demographic-->
   <h3>Demographic</h2> 
    <ol>
      <li><strong>Subscription </strong>:<a href="Images/RidersByMemberType.png"> 80% of the rides were done by the subscribed members.</a></li>
      <li><strong>Bike Type </strong>:<a href="Images/TypesOfBike.png"> Irrespective of the member type, 90% of bikers like to have a ride on classic bikes.</a></li>
      <li><strong>Duration</strong>:<a href="Images/RidersByDuration.png"> Most popular rides are medium rides that lays between 6 -10 minutes. </a></li>
    </ol>
     
  <h2>Summary </h2>
      <p> 
        In the year 2023 most of the rides were done by the members during the weekdays.
        After office hours are mostly busy, maybe members use the bike on way back home.
        Another  noticeable thing is casual bikes are more popular than electric,
        maybe riders expect some exercises activity while saving time as well as site seeing.
        Except for the winter,  all other seasons are equally busy , 
        but summer is the most popular season in the year. 
      </p>
 <h2>Recommendations</h2>
  <ul>
    <li><strong>Increase Bike Availability</strong>: Add more bikes during peak months.</li>
    <li><strong>Promote Membership</strong>: Offer discounts to convert casual users to members.</li>
    <li><strong>Escape Peak Times</strong>: Escape the peak days and peak times as much as possible.</li>
    <li><strong>Popular Placess</strong>: Check the most pupular staitons before you starts.</li>
  </ul>

  <h2>Merging and Creating Sample Data</h2>
  <ul>
	<li><strong>MergeCSV.ipynb</strong>:<a href="PythonScripts/MergeCSV.ipynb"> This notebooks is used to 12 months data into a single CSV file.</a></li>
	<li><strong>ExtractSampleData.ipynb</strong>:<a href="PythonScripts/ExtractSampleData.ipynb"> This notebooks is used to extract a sample from the yearly merge data.</a></li>
	<li><strong>Data Source</strong>:<a href="https://citibikenyc.com/system-data"> City bike data is available in.</a></li>
	<li><strong>Select Your year</strong>:<a href="https://s3.amazonaws.com/tripdata/index.html"> Go to the historical data page.</a></li>
	<li><strong>Unzip File/strong>: Unzip the data into the local computer folder where your jupyter notebooks are saved.</li>
    <li><strong>Merge CSV</strong>: Open the MergeCSV.ipynb using Anaconda prompt and run all the cells</li>
    <li><strong>Extract Sample Data</strong>: Open the ExtractSampleData.ipynb using Anaconda prompt and run all the cells</li>
	<li><strong>Limitations</strong>: This notebook can merge only monthly data of one year. </li>
	
  </ul>










