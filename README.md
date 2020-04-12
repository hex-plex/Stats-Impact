<html><body><h1>Stats-Impact</h1>
<p>This is the solution that I presented in the competition Stats Impact
  for which I came at <b> First</b> place.</p>
In the competetion I was given a dataset consisting
<ul>
  <li>Country name</li>
  <li>Region/Province</li>
  <li>Latitude and longitude</li>
  <li>No.ofConfirmed Cases</li>
</ul>
<h2>Objective:</h2>
To be able to predict the no of cases at a given point of time by learning from the given data<br>
<h2>Salient features of my solution</h2>
  <ol>
    <li>Having studied the data, A exponential relation is converted to a linear relation by training on the log of the no of cases which helps us with more efficient computation and reducing the computational cost.</li>
    <li>Increasing the feature set with adding square of latitude ,square of longitude and product of latitude and longitude which is explained in the presentation</li>
    <li>Another additional feature is the Day0 with respect to each country as that helps to get a analytical background for the country </li>
    <li>Another additional feature is the rate of Change on the log of the no of Cases which gives an adiitional guidance for the model to learn</li>
  </ol>
  <h3><i>All the brief explanation is done in the code itself and also present in the presentation</i></h3>
  </body></html>
