<h1>Happiness-Project</h1>
<hr>
<h2>Why are you happy or not happy?</h2> 
<p>Is my happiness level normal? Are my fellow compatriots happy? What's the happiest country? What makes them so happy? Freedom? Health? Trust in government? Are happiness levels increasing or decreasing in my country?</p>
<p>If you have any of these same questions, explore here! I know what you're thinking, "All these happiness questions... It sounds like a-." No, this isn't a bad drug infomercial prescribing you a drug with life debilitating side effects, it's an exploration of world happiness data. Side effects include deeper understanding of global happiness and a curiousity to explore more!</p>
<br>
<h2>Intro</h2>
<p>Our project creates a website interface in which the user can explore happiness levels in different countries, years, and regressed against country demographics. Our dataset came from <a href="https://www.kaggle.com/mathurinache/world-happiness-report-20152021">Kaggle Gallup World Happiness Report 2015-2021</a>. We wanted to visualize the happiness data so that the user might see more easily trends and possible explanations as to why some countries might be happier than others. Our interface allows the user to explore on their own without any inferences.
</p>
<br>
<h2>Cleaning Our Data</h2>
<p>Our data originally came in a csv for each year. Our first step was to drop unwanted columns and make sure the column headers and the data formatting were congruent across all year's csvs. For 2020 and 2021, we had to add happiness rank data and normalize their life expectancy measurements. We could then concatenate all of the years into one csv. 
For our country temperature measurement data (which we later decided not to use), we compared the list of country names from our happiness data using a "isin" function. After manually changing some country names to match up, we ended up with 152 countries in which we had all the desired data.</p>
<br>
<h2>SQL</h2>
<p>We created a SQL schema to store our data and pushed our data to SQL using SQLAlchemy. We later moved the SQL db to be hosted on Heroku so that all team member's machines could access.</p>



Evan Mobley | [Evan's LinkedIn](https://www.linkedin.com/in/evanmmobley/) | [Evan's Github](https://github.com/emmobley63) | [emmobley63@gmail.com](mailto:emmobley63@gmail.com)

Paul Anderson | [Paul's LinkedIn](https://www.linkedin.com/in/paul-anderson-1426b340/) | [Paul's Github](https://github.com/pander1405)

Shreya Bakshi | [Shreya's LinkedIn](https://www.linkedin.com/in/shreya-bakshi/) | [Shreya's Github](https://github.com/bakshishreya)
