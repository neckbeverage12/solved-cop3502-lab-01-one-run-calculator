Download Link: https://assignmentchef.com/product/solved-cop3502-lab-01-one-run-calculator
<br>



<h1>Overview</h1>

In this project students will build a four-function one-run calculator on the command line. The program will first prompt the user for two numbers, then display a menu with five operations. It will allow the user to select an option by reading input using a scanner object. The program will then display the result of the operation and exit. The project is designed to give students an opportunity to practice input, output, selection, and basic operators via a simple project.




<h1>Specification</h1>




When the program starts it should prompt the user to enter an operand and read a <strong><u><sub>double</sub></u></strong><u> precision</u> floating point number as follows:




Enter first operand: <strong>89.1</strong>

Enter second operand: <strong>42</strong>




Once the two operands have been read and stored, the program should display a menu as follows:




Calculator Menu

—————

<ol>

 <li>Addition</li>

 <li>Subtraction</li>

 <li>Multiplication</li>

 <li>Division</li>

</ol>




…and then display a menu and accept user input (we recommend an <strong>integer type</strong> for the input):




Which operation do you want to perform? <strong>1</strong>




If a valid operation is selected, the program should print the result and exit:




The result of the operation is 131.1. Goodbye!




If the input is an invalid integer, it should print this error message and exit:




Error: Invalid selection! Terminating program.

<h1>Submissions</h1>

<strong>NOTE</strong>: Your output must match the example output *exactly*. If it does not, <strong><em>you will not receive full credit for your submission</em></strong>!




File:                 Calculator.java

Method:           Submit on ZyLabs




<u>Do not submit any other files</u>!




<h1>Sample Output</h1>




<strong>Example #1 </strong>



Enter first operand: <strong>2.25</strong>

Enter second operand: <strong>-1.5</strong>




Calculator Menu

—————

<ol>

 <li>Addition</li>

 <li>Subtraction</li>

 <li>Multiplication</li>

 <li>Division</li>

</ol>

Which operation do you want to perform? <strong>4 </strong>

The result of the operation is -1.5. Goodbye!




<strong>Example #2 </strong>



Enter first operand: <strong>30.9</strong>

Enter second operand: <strong>86.75</strong>




Calculator Menu

—————

<ol>

 <li>Addition</li>

 <li>Subtraction</li>

 <li>Multiplication</li>

 <li>Division</li>

</ol>

Which operation do you want to perform? <strong>100 </strong>




Error: Invalid selection! Terminating program.


