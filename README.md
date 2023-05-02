Download Link: https://assignmentchef.com/product/solved-coen79-lab-1
<br>
<ul>

 <li>Program 1: count the input characters.</li>

</ul>

In this program you will ask the user to enter some text. The user may input any combination of alphanumeric and non-alphanumeric characters.

Your program should count each category and tell the user how many of each they entered. Example:




Please type something:

“Hello World” has 10 alphanumeric characters and 0 non-alphanumeric characters.




<ul>

 <li>Program 2: string of numbers and its reverse</li>

</ul>

In this program you will ask your user to enter a  string 10 numbers with no space in between.  You will print the numbers and it reverse according to the following example




Please type a string of 10 digits (0 to 9) with no space

0123456789          9876543210

0123456789            9876543210

0123456789              9876543210

0123456789                9876543210

0123456789                  9876543210




<ul>

 <li>Program 3:</li>

</ul>

In this program, your program reads a text file and output erases all non-alphabetical characters and for all words larger than 10 characters, converts them to uppercase and prints on the screen (use: cout)




For example, if the file input contains:




1_counter.exe compiled successfully.

1_counter.exe got correct output.

Exit code: 0

2_pattern.exe compiled successfully.

2_pattern.exe got correct output.

Exit code: 0

3_convert.exe compiled successfully.

3_convert.exe got correct output.

Exit code: 1




Execution of your program

&gt;./a.out input

will generate the following output on the screen




COUNTEREXE

SUCCESSFULLY

COUNTEREXE

PATTERNEXE

SUCCESSFULLY

PATTERNEXE

CONVERTEXE

SUCCESSFULLY

CONVERTEXE




<ul>

 <li>Program 4</li>

</ul>

Write a function that ask the user to think about a number between 1 and 20. Use successive guesses to find that number.




An output of the system can be the following:




<ul>

 <li>Think of a number between 1 and 20. Press enter when you are ready.</li>

 <li>Is the number 1? Y or N // if the user wrote anything but Y or N (y or n , yes or no is also acceptable), tell the user to only enter Y or N.</li>

 <li>Is the number 5? Y or N //if the user entered N</li>

 <li>I Found the number in &lt;number&gt; steps //if the user entered Y</li>

</ul>