Download Link: https://assignmentchef.com/product/solved-comp1410-lab-5-more-on-pointers
<br>
<strong>: </strong>Learn to use pointers and operators at a more advanced level.

<ol>

 <li><strong> Pointer Operators </strong></li>

</ol>

Type the following program and document <u>every line</u> by explaining its function and output.  If any line produces an error, comment that specific line and explain the nature of the error.  Write your code for this part in a file called: <strong>Lab5a.c </strong>

<strong> </strong>

<strong>#include &lt;stdio.h&gt; </strong>

<strong> int main() </strong>

<strong> </strong>

<strong>{ </strong>

<strong> </strong>

<strong>int a = 7 ; </strong>

<strong> </strong>

<strong>int *aPtr ; </strong>

<strong> </strong>

<strong>aPtr = &amp;a ; </strong>

<strong> </strong>

<strong>printf( “%p”, &amp;a ); </strong>

<strong> </strong>

<strong>printf( “%p”, aPtr ); </strong>

<strong> </strong>

<strong>printf( “%p”, &amp;aPtr ); </strong>

<strong> </strong>

<strong>printf( “%d”, a ); </strong>

<strong> </strong>

<strong>printf( “%d”, *aPtr ); </strong>

<strong> </strong>

<strong>printf( “%p”, *&amp;aPtr ); </strong>

<strong> </strong>

<strong>printf( “%p”, &amp;*aPtr ); </strong>

<strong> </strong>

<strong>printf( “%d”, *&amp;a ); </strong>

<strong> </strong>

<strong>printf( “%d”, &amp;*a ); </strong>

<strong> return 0; </strong>

<strong> </strong>

<strong> } </strong>













<ol>

 <li><strong> Array Manipulation with Pointers </strong></li>

</ol>

Write, document and test each of the following function specifications <strong>(</strong>write your code for this part in a file called: <strong>Lab5b.c</strong>):

<strong>[You should use only pointer arithmetic – DO NOT USE <u>array indices</u> (i.e. subscripts)]. </strong>

<strong> </strong>

<ol>

 <li>A function called <strong>FillArray() </strong>that accepts a pointer to a integer as the array name, an integer for its size. This function pseudo-randomly fills the array with integers ranging from 0 to 100. Do not be concerned about possible duplicate values.</li>

 <li>A function called <strong>PrintArray() </strong>that accepts a pointer to a integer as the array name, an integer for its size. This function only prints the array elements.</li>

 <li>A function called <strong>BubbleSort() </strong>that accepts a pointer to a integer as the array name, an integer for its size. The function should sort the array passed, in descending order. Use the function <strong>Swap() </strong>that you designed in the last Lab #4, to swap any values in the function <strong>BubbleSort()</strong>.</li>

 <li>In the main() function:</li>

</ol>




<ol>

 <li>Declare an integer array called <strong>NumList </strong>of size SIZE (define SIZE as 20, using #define).</li>

 <li>Populate the array with pseudo-random numbers [0 -100] by calling the function <strong>FillArray()</strong>.</li>

 <li>Display the Array contents by calling the function <strong>PrintArray()</strong>.</li>

 <li>Sort the array <strong>NumList </strong>in descending order by calling the function <strong>BubbleSort()</strong>.</li>

 <li>Display the SORTED array by calling the function <strong>PrintArray()</strong>.</li>

</ol>




For your convenience, the function prototypes are given bellow:




<strong>void FillArray ( int *array, int size ); void PrintArray ( int *array, int size ); void BubbleSort ( int *array, int size ); void Swap ( int *x, int *y );</strong>







<strong>Summary of the lab requirements:  </strong>You must complete Part A above by writing a program called <strong>Lab5a.c</strong>.  Parts B must be completed by writing a single C language program called <strong>Lab5b.c</strong>.  Remember to fully document your programs.