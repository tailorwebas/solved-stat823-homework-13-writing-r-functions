Download Link: https://assignmentchef.com/product/solved-stat823-homework-13-writing-r-functions
<br>
Using R Markdown in R Studio, complete the following questions. Launch RStudio and open a new RMarkdown file or use the class RMarkdown template provided and save it on your working directory as a .Rmd file. At the end of the activity, save your <strong>pdf </strong>generated from RMarkdown+Knitr and submit your homework on the Blackboard.




<ol>

 <li>Write an R function for computing the value of</li>

</ol>

<em>f</em>(<em>x</em>) = <em>e<sup>−x</sup></em><sup>2</sup>

<table>

 <tbody>

  <tr>

   <td width="734"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

and test it for a vector <em>x </em>= <em>c</em>(0<em>,</em>1<em>,</em>100).

<ol start="2">

 <li>Write an R function to compute the sample excess kurtosis given by</li>

</ol>

1 P<em><sup>n</sup></em><em>i</em>=1(<em>x</em><em>i − x</em>¯)<sup>4</sup>

<em>g</em>2 = 1<em>n</em>P<em>n </em>(<em>x</em><em>i − x</em>¯)22 <em>− </em>3

<em>i</em>=1 <em>n</em>

for a given vector <em>x </em>= (<em>x</em><sub>1</sub><em>,··· ,x<sub>n</sub></em>), where <em>x</em>¯ is the average of the elements of <em>x</em>. Test the function for a vector <em>x </em>= 1:10.

<ol start="3">

 <li>Suppose Jane wishes to take out a mortgage on a house. She wants to know what her periodic payments will be. If <em>P </em>is the initial amount mortgaged, <em>r </em>is the effective interest rate, and <em>n </em>is the length of the mortgage, then the periodic payment <em>R </em>is given by</li>

</ol>

<em>Pr</em>

<em>R </em>=

1 <em>− </em>(1 + <em>r</em>)<em><sup>−n</sup></em>

<ul>

 <li>Construct a function which employs this formular</li>

 <li>Calculate Jane’s monthly payments, if the initial amount is $100<em>,</em>000, the interest rate is 1% and the number of interest conversions periods is 300.</li>

</ul>

<ol start="4">

 <li>Suppose payments of <em>P </em>dollars are deposited annually into a bank account which earns constant interest <em>r </em>per year. What is the accumulated value of the account at the end</li>

</ol>

Page -1- of 2

<strong>Lesson 13: Homework                                                             STAT/BIOS 823: Writing R functions</strong>

of <em>n </em>years, supposing deposits are made at the end of each year? The total amount at the end of <em>n </em>years is given by the expression (1 + <em>r</em>)<em>n − </em>1

<em>n−</em>1

<em>Amount </em>= <em>P</em>(1 + <em>r</em>)               + <em>··· </em>+ <em>P</em>(1 + <em>r</em>) + <em>P </em>= <em>P </em>

<em>r</em>

(a) Write an <em>R </em>function to compute the accumulated amounts after <em>n </em>= 10 years, with periodic payments <em>P </em>= $400 with a vector of interest rates <em>r </em>ranging from

0<em>.</em>01 to 0<em>.</em>2 by increments of 0<em>.</em>01.

<ul>

 <li>Produce a line plot of the amounts (y-axis) against the interest rates (x-axis)</li>

 <li>Optional question: Write a single function to perfom both parts (a) and (b) above.</li>

</ul>