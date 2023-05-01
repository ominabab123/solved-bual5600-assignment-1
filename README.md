Download Link: https://assignmentchef.com/product/solved-bual5600-assignment-1
<br>
This assignment relates to the ‘College’ data set, which can be found in the ‘ISLR’ library. It contains a number of variables for 777 different universities and colleges in the US. The variables are

<ul>

 <li>Private: Public/private indicator</li>

 <li>Apps: Number of applications received</li>

 <li>Accept: Number of applicants accepted</li>

 <li>Enroll: Number of new students enrolled</li>

 <li>Top10perc: New students from top 10% of high school class</li>

 <li>Top25perc: New students from top 25% of high school class</li>

 <li>Undergrad: Number of full-time undergraduates</li>

 <li>Undergrad: Number of part-time undergraduates</li>

 <li>Outstate: Out-of-state tuition</li>

 <li>Board: Room and board costs</li>

 <li>Books: Estimated book costs</li>

 <li>Personal: Estimated personal spending</li>

 <li>PhD: Percent of faculty with Ph.D.’s</li>

 <li>Terminal: Percent of faculty with terminal degree</li>

 <li>F.Ratio: Student/faculty ratio</li>

 <li>alumni: Percent of alumni who donate</li>

 <li>Expend: Instructional expenditure per student</li>

 <li>Rate: Graduation rate</li>

</ul>




<ol>

 <li>Read the data into R. Call the loaded data “college”.</li>

</ol>




<ol start="2">

 <li>Answer the following sub-questions</li>

 <li>Use the “summary()” function to produce a numerical summary of the variables in the data set.</li>

 <li>Use the “pairs()” function to produce a scatterplot matrix of the first ten columns or variables of the data. Recall that you can reference the first then columns of a matrix A using A [,1:10].</li>

</ol>

<ul>

 <li>Use the “plot()” function to produce side-by-side boxplots of “Outstate” versus “Private”</li>

</ul>

<ol>

 <li>Create a new qualitative variable, called “Elite”, by binning the “Top10perc” variable. We are going to divide universities into two groups based on whether or not the proportion of students coming from the top 10% of their high school classes exceeds 50%.</li>

</ol>

Use the “summary()” function to see how many elite universities there are.  Now use the “plot()” function to produce side-by-side boxplots of “Outstate” versus “Elite”




<ol>

 <li>Use the “hist()” function to produce some histogram with differing numbers of bins for a few of the quantitative variables. You may find the command “par(mfrow=c(2,2))” useful: it will divide the print window into four regions so that four plots can be made simultaneously. Modifying the arguments to this function will divide the screen in other ways.</li>

</ol>




<ol>

 <li>Continue exploring the data, and provide a brief summary of what you discover.</li>

</ol>


