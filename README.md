Download Link: https://assignmentchef.com/product/solved-cse102-assignment-1
<br>
<span class="kksr-muted">Rate this product</span>

Description

• This is an individual assignment. Please do not collaborate• If you think that this document does not clearly describe the assignment, ask questions before its too late.

This is a C Programming assignment. You will write a C program according to the following description.• Your program catches user input, learns and tests a simple classifier. This assignment is about using control

statements, performing arithmetic operations and simple input/output.

Program Flow

• Read pre-defined number of points for class 1.• Read pre-defined number of points for class 2.• Find the average point for each class.• Find the line connecting the two average points. • Find the midpoint of the connecting line.

• Find the perpendicular separating line which passes through the midpoint.• Classify any given point and print its label until an unusual input is encountered.

Example

# commands

<pre>line 0  &gt; 10.4 34.8line 1  &gt; 3.5 45.9</pre>

&gt;.&gt;.&gt;.line 10 &gt; 22.2 12.6 line 11 &gt; 62.1 11.0 &gt;.

&gt;.

&gt;.line 20 &gt; 10.2 34.9

<pre>line 21 &gt; class 1</pre>

<pre>                      average point</pre>

Figure 1: Visualization

<pre>commentsUser enters point coordinates for class 1</pre>

<pre>User enters point coordinates for class 2</pre>

<pre>User enters a test pointProgram prints its class</pre>

1

<pre>separating line</pre>

<pre>line 22 &gt; 10.3 33.8line 23 &gt; class 1</pre>

&gt;. &gt;. &gt;.

line x &gt; q

Remarks

<pre>User enters a test pointProgram prints its class</pre>

<pre>User enters something not expectedProgram quits.</pre>

<ul>

 <li>There will be 20 training samples (10 for each class). But, don’t make this number hard-coded. Use a macro. Changing the macro should be enough for trying different number of samples. You can assume that the number of training samples for each class will be the same.</li>

 <li>There is no limit on the number of test points.</li>

 <li>Assume that non of the points will be on the separating line.</li>

 <li>Assume training phase will be error-free.</li>

 <li>Be careful with divide-by-zero situations. You can avoid them by perturbing the 0 results with very smallnumbers.</li>

 <li>Do not print anything other than the expected output.</li>

 <li>Your program either prints class 1 or class 2. Each label should be on a new line. There shouldn’t be anyempty lines.</li>

 <li>You cannot use pointers and other things which are not covered in class.</li>

 <li>Using input/output redirection is advised. (Do not submit any of the files you used for testing).Turn in:</li>

</ul>

<ul>

 <li>Source code of a complete C program. Name of the file should be in this format: &lt;full_name&gt;_&lt;id&gt;.c.</li>

 <li>Example: gokhan_kaya_000000.c. Please do not use any Turkish special characters.</li>

 <li>You don’t need to use an IDE for this assignment. Your code will be compiled and run in a command window.</li>

 <li>Your code will be compiled and tested on a Linux machine(Ubuntu). GCC will be used.</li>

 <li>Make sure you don’t get compile errors when you issue this command : gcc &lt;full_name&gt;_&lt;id&gt;.c.</li>

 <li>A script will be used in order to check the correctness of your results. So, be careful not to violate the expectedoutput format.</li>

 <li>Provide comments unless you are not interested in partial credit. (If I cannot easily understand your design,you may loose points.)</li>

 <li>You may not get full credit if your implementation contradicts with the statements in this document.</li>