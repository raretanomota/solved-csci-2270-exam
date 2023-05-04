Download Link: https://assignmentchef.com/product/solved-csci-2270-exam
<br>



You will be solving two of the three programming problems detailed below. <em>Problem 1</em> is <strong>mandatory</strong>, but you only have to do <strong>either</strong> <em>Problem 2</em> <strong>or</strong> <em>Problem 3</em>. For each problem you must submit three documents:

<ol>

 <li>A C++ program that solves the given problem. It is required that your code files are well commented. Note:   you  will   not  receive  more  than  25%  of   the  possible   points    on any      problem  if              your         submitted               code        does        not</li>

 <li>If your code does not fully meet the specifications, then include a text file with your explanations for potential partial credit.</li>

</ol>

The third document you submit will help us understand your thought process. Mention anything you have done to write, test, and debug your code. Incomplete code can still receive points if you show that you have identified the errors and tried to debug them.

Your submission should be valid C++ 11 code.

Your solutions should use similar types and functions to the example code provided, but you are welcome to make modifications as you see fit.

Show how you have tested your code. You will be graded higher for code with complete tests.

We will be running this code on other computers, so make sure to avoid <strong>any</strong> undefined behavior such as uninitialized variables.

<h1>Problem 1 (Mandatory)</h1>

<strong>Task:</strong>

Find the middle of a given linked list in C++. Given a singly linked list, find the middle of the linked list. For example, if given linked list is 1-&gt;2-&gt;3-&gt;4-&gt;5 then output should be 3. If there are an even number of nodes, then print the second of the middle elements. For example, if given linked list is 1-&gt;2-&gt;3-&gt;4-&gt;5-&gt;6, then the output should be 4.

Use the following algorithm: Traverse the linked list using two pointers. Advance the first pointer by one node at a time. Advance the second pointer by two nodes at a time. When the fast pointer reaches the end, the slow pointer will reach the middle of the linked list.

<strong>Requirements:</strong>

This function should return a pointer to the middle node. If the list is empty, your function should return NULL.

<strong>Examples:</strong>

Calling             getMiddle               on linkedList 1-&gt;2-&gt;3-&gt;4-&gt;5-&gt;6 should return 4

Calling             getMiddle               on linkedList 1-&gt;2-&gt;3-&gt;4-&gt;5 should return 3

<ol start="2">

 <li>The function getMiddle skeleton code has been provided in the LinkedList.cpp file. Complete your implementation inside of this skeleton (you are not allowed to alter any other provided functions).</li>

 <li><strong>Test your function</strong> Test your code on the test cases provided in the driver file,</li>

</ol>

LinkedListDriver.cpp (you are welcome to try your own test cases as well).

<h1>Problem 2</h1>

<strong>Task:</strong>

You are required to process a given string S that includes ‘#’ symbol.

The ‘#’ symbol represents backspace of a character. For instance given a string ‘abc#def’ you are required to transform it to ‘abdef’. The transformation requires that the character before the # symbol and the symbol itself (i.e. c and #) be removed from the string.

Inside of your function, you will need to repeat this process on two strings. Once this is done, return true if both string are the same (post transformation). Otherwise return false.

You must use the provided stack class to execute this task.

<strong>Requirements:</strong>

<ol>

 <li>The function stringManipulation skeleton code has been provided in the driver.cpp file. Fill in the function definition with your algorithm implementation. You must        use the stack</li>

</ol>

This function should return true if the strings matched else false.

<ol start="2">

 <li><strong>Test your function</strong> to make sure that it passes all the test cases.</li>

</ol>

Hint: the string class member function length() might be useful in your implementation.

<h1>Problem 3</h1>

<strong>Task:</strong>

Create a function that will append one array to another one.

<strong>Requirements:</strong>

The function prototype is given:

where

arr1               : pointer to the first array           arr2         : pointer to the second array            size1        : size of the array1                size2        : size of the array2

<ol>

 <li>Function will append array2 to array1. After calling the function, elements of array2 will be appended to array1. Size of array1 should become size1        +              size2</li>

 <li>The main function will take size1 and size2 as command line arguments. Sample code for creating array1 is given in the starter code. You need to create the array2 in similar way.</li>

</ol>

Then, call the append function.

<ol start="3">

 <li>After appending the arrays, <strong>free up the memory space used by the original array(s)</strong>.</li>

 <li>Print the contents of the two arrays before the function call and the contents of the resulting array after the function call. Each element should be separated by a ,               . There should not be any        ,      after the last element.</li>

</ol>

<strong>Example program output:</strong>