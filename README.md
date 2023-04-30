Download Link: https://assignmentchef.com/product/solved-cs2400-lab-5-multiple-files-multiple-arrays
<br>
The purpose of this lab assignment is to gain more practice with arrays and file I/O.

<strong>Be sure to first create a separate directory for this assignment,</strong> called Lab5, create your files and do your work this week in this new directory.

Problem

Often, data is presented to a program in multiple files, and needs to be stored in multiple arrays. In this lab, we will use a pair of related data files.

File data1.txt contains prices for 6 auto parts. File data2.txt contains the associated names of those parts. The files are related in that the name on line 1 of data2.txt corresponds to the price on line 1 of data1.txt, and similarly for each pair of lines of the files.

File data1.txt contains the prices in dollar amounts, so choose an appropriate variable data type for this data. data2.txt contains the names in string format.

Program

Write a program which will declare an array for the prices, and an array for the names of the parts, open the files, and load data in the arrays.

There are exactly 6 entries in each file, so you can use static arrays to load your data.

Once the data is loaded, output the names of the most and least expensive parts. Together with the names of the most and least expensive parts, you should output the actual prices for these formatted as $dollars.cents, e.g. $20.12. Please be sure the names and the prices are aligned nicely e.g.:

The name of the most expensive part is engine ($100.45)

The name of the least expensive part is gasket ($12.99)

Be sure to close your data files before ending your program.

<strong>Required Functions: </strong>

<ul>

 <li>A function to load the prices array</li>

 <li>A function to load the names array</li>

 <li>A function to print all the names of prices</li>

 <li>A function to find the index of the most expensive part</li>

 <li>A function to find the index of the least expensive part</li>

</ul>

<h1></h1>


