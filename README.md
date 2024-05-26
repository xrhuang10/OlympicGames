# Olympic Games
<h3>Machine Learning Project</h3>
<h5>Overview</h5>
<p>
  I love sports, geography, and coding, so what better way to combine them than this Olympic Medal Prediction Project?
  The goal of this project was to predict the number of medals each country would receive at the upcoming Olympic Games based on previous medal data.
</p>

<h5>Process</h5>
<p>
  By pulling an Excel query with Olympic data, I was able to organize the data and link it as a CSV file with my VSCode python file. The data was sorted into a table, which comprised:
  <ul>
    <li>Team</li>
    <li>Country</li>
    <li>Year</li>
    <li>Events</li>
    <li>Athletes</li>
    <li>Age</li>
    <li>Height</li>
    <li>Weight</li>
    <li>Medals (Total Count)</li>
    <li>Medals (Previously Obtained)</li>
    <li>Medals (Obtained in the last 3 Olympics)</li>
  </ul>
  By using pandas and numpy, I could read the Excel file and transfer that data to VSCode for further mathematical manipulation. Afterwards, I separated the data into pre-2008 vs post-2012. 
  The first group would be the sample group for the ML to train its algorithm, and try to predict the 2012, 2016, 2020 Olympics. Then, I took its predictions and compared it with the actual results from group 2 (post-2012).
  
  I was able to sort through the data, with a prediction model using simple linear regression function (y=mx+b) from the sci-kit learn package to find the line of best fit that would predict the medal count for each country.
  
  By using the mean_absolute_error function and error formula, I was able to find the ML model's most/least predictions, then correct it for future iterations.
  Finally, I used seaborn and matplotlib to plot the data with the line of best fit.
</p>
<p>*Note: The main plot is written on line 12 and displayed on line 21, so to reeavalute the data based on different parameters, change line 12. </p>

<h5>Conclusion</h5>
<p>
  This project was my first ever experience with AI/ML. I realized that although the coding is not as complicated as I expected, the math and logic are what make AI/ML so intimidating to beginners. 
  I hope to learn more about this field, and eventually build a full-stack project that would feature a UX-friendly, interactive, and responsive display of the data. 
</p>
