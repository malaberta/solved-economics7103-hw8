Download Link: https://assignmentchef.com/product/solved-economics7103-hw8
<br>
This assignment uses the same data as the previous assignment.

You have access to imaginary vehicle sales data from 2017 (<em>instrumentalvehicles.csv</em>). You are interested in estimating the hedonic price of an additional mile per gallon as part of a larger analysis of willingness to pay for fuel efficiency. In your data, you have the following variables:

<table width="526">

 <tbody>

  <tr>

   <td width="64">Variable</td>

   <td width="462">Description</td>

  </tr>

  <tr>

   <td width="64"><em>price</em></td>

   <td width="462">Sales price of the vehicle in USD</td>

  </tr>

  <tr>

   <td width="64"><em>car</em></td>

   <td width="462">Class of the vehicle. =1 if the vehicle is a sedan, =0 if the vehicle is an SUV</td>

  </tr>

  <tr>

   <td width="64"><em>mpg</em></td>

   <td width="462">Fuel efficiency in miles per gallon</td>

  </tr>

  <tr>

   <td width="64"><em>weight</em></td>

   <td width="462">Weight of the vehicle in pounds</td>

  </tr>

  <tr>

   <td width="64"><em>height</em></td>

   <td width="462">Height of the vehicle in inches</td>

  </tr>

  <tr>

   <td width="64"><em>length</em></td>

   <td width="462">Length of the vehicle in inches</td>

  </tr>

 </tbody>

</table>

Table 1: Variable descriptions for homework 7.

<strong>New twist</strong>: You have been told that there is a strange policy that required a specific safety technology for vehicles longer than 225 inches. The side effect of the policy was that every vehicle equipped with the technology is significantly less fuel-efficient. You think you may be able to exploit the policy cutoff using a regression-discontinuity design.

<ol>

 <li>Do you think that this design should be a sharp or fuzzy RD? Explain.</li>

 <li>Create a scatter plot with <em>mpg </em>on the <em>y</em>-axis and <em>length</em>−<em>cutoff </em>on the <em>x</em>-axis with a line at the RD cutoff. Is there visual evidence of bunching? Is there visual evidence of a discontinuity?</li>

 <li>Fit a first-order polynomial to both sides of the cutoff in a regression discontinuity design. Plot theresulting polynomial over a scatterplot and estimate the impact of the policy on fuel efficiency around the cutoff.</li>

 <li>Fit a second-order polynomial to both sides of the cutoff in a regression discontinuity design. Plot theresulting polynomial over a scatterplot and estimate the impact of the policy on fuel efficiency around the cutoff.</li>

 <li>Fit a fifth-order polynomial to both sides of the cutoff in a regression discontinuity design. Plot theresulting polynomial over a scatterplot and estimate the impact of the policy on fuel efficiency around the cutoff.</li>

 <li>Using the discontinuity as an instrument for miles per gallon, estimate the impact of <em>mpg </em>on the vehicle’s sale price. Use whatever degree polynomial you see fit for the first stage and explain your choice. In the hedonic regression, control for the class of the vehicle by including <em>car<sub>v </sub></em>as in Homework 6. Report the second-stage regression results in a nicely formatted table using confidence intervals or standard errors of your choice (do not report the first stage F statistic). Do you think this is a valid instrument?</li>

</ol>