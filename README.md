<h1>Inspiration</h1>
 
<p>Over the past 9 months, Covid-19 has had a transformative impact on society. Given the impact that I have personally faced, I wanted to channel my data science skills so that I could analyze, and visualize insights so that I can better understand the magnitude of the pandemic.</p>

<h1>Basic Visualization and Analysis</h1>
<p><img alt="Image" title="icon" src="https://github.com/AbhikMahakul/Covid-Analysis/blob/main/Images/Basic%20Trends/casesovertime.png" /></p>
 
<p> Above is a visualization of cases over time in the United States. As expected the cases have increased over time. </p>


<p><img alt="Image" title="icon" src="https://github.com/AbhikMahakul/Covid-Analysis/blob/main/Images/Basic%20Trends/deathsovertime.png" /></p>


<p> Above is a visualization of deaths over time in the United States. As expected the cases have increased over time. </p>


<p><img alt="Image" title="icon" src="https://github.com/AbhikMahakul/Covid-Analysis/blob/main/Images/Basic%20Trends/deathratio.png" /></p>

<p> Above is a visualization of the ratio of deaths to cases. I find this interesting becuase this ratio has decreased over time. It would be interesting to know why this ratio has decreased. Are we better at treating Covid-19? Has a different demographic been getting infected with Covid more recently? </p>

<h1>Mask Usage Analysis</h1>


<p><img alt="Image" title="icon" src="https://github.com/AbhikMahakul/Covid-Analysis/blob/main/Images/Mask%20Usage/AlwaysWearsMask.png" /></p>


<p><img alt="Image" title="icon" src="https://github.com/AbhikMahakul/Covid-Analysis/blob/main/Images/Mask%20Usage/SometimesWearsAMask.png" /></p>


<p><img alt="Image" title="icon" src="https://github.com/AbhikMahakul/Covid-Analysis/blob/main/Images/Mask%20Usage/Never.png" /></p>

<p> Above are visualizations which show mask usage as a function of income. For these visualizations, counties were randomly selected from the state of Illinois. Based off of these graph, it appears that higher income counties are not only more likely to wear a mask, but they have a more adamant about always wearing a mask. Lower income counties are less likely to wear a mask, and have less conviction with their mask usage.  </p>


<h1>State Performance Visualizations</h1>

<h2>Deaths as a Function of Population</h2> 

<h3> Statistical Summary</h3>
<p><img alt="Image" title="icon" src="https://github.com/AbhikMahakul/Covid-Analysis/blob/main/Images/Mask%20Usage/DeathVsPopulationStats.png" /></p>

<p><img alt="Image" title="icon" src="https://github.com/AbhikMahakul/Covid-Analysis/blob/main/Images/DeathsVsPopulations/Top8.png" /></p>

<p><img alt="Image" title="icon" src="https://github.com/AbhikMahakul/Covid-Analysis/blob/main/Images/DeathsVsPopulations/Bottom8.png" /></p>

<p> I started by using linear regression to determine a relationship between a state's population, and the number of deaths. After building the linear model, I was able to separate the top 8 vs the bottom 8 performing states. I performed this by grouping the states with the highest 8 resdiuals (more deaths than expected) as the worst performing 8 states, and I grouped the states with the lowest 8 residuals (less deaths than expected) as the best performing states. 
<br> 
<br>
As for determining if this model is effective, we can look at the following -
<br>
<br>
Coefficent of Determination - .4936
<br>
<br>
Correlation Coefficent - .7025 
<br>
<br>
With a Correlation Coefficent of .7025, we can state there is a strong linear relationship between the number of Covid Cases as a function of the state's population. The Coefficent of determination means that 49.36% of the model is explained the variability. As for causes in variability, this could be due to individual behaviors, climate, legislation, and a variety of other factors.  </p>

<h2> Deaths as a Function of Cases </h2>

<h3> Statistical Summary</h3>
<p><img alt="Image" title="icon" src="https://github.com/AbhikMahakul/Covid-Analysis/blob/main/Images/DeathsVsCases/Top8DeathsVsCases.png" /></p>

<p><img alt="Image" title="icon" src="https://github.com/AbhikMahakul/Covid-Analysis/blob/main/Images/DeathsVsCases/Bottom8DeathsVsCases.png /></p>

<p><img alt="Image" title="icon" src="https://github.com/AbhikMahakul/Covid-Analysis/blob/main/Images/DeathsVsCases/Top8DeathsVsCases.png" /></p>

<p> I started by using linear regression to determine a relationship between a state's number of Covid Cases, and the number of deaths. After building the linear model, I was able to separate the top 8 vs the bottom 8 performing states. I performed this by grouping the states with the highest 8 resdiuals (more deaths than expected) as the worst performing 8 states, and I grouped the states with the lowest 8 residuals (less deaths than expected) as the best performing states. 
<br> 
<br>
As for determining if this model is effective, we can look at the following -
<br>
<br>
Coefficent of Determination - .76
<br>
<br>
Correlation Coefficent - .5789
<br>
<br>
With a Correlation Coefficent of .76, we can state there is a strong linear relationship between the number of Deaths as a function of the state's Covid Cases. The Coefficent of determination means that .5789 of the model is explained the variability. As for causes in variability, this could be due to individual behaviors, climate, demographics of those being infected, medical technology used, and a variety of other factors.  </p>
