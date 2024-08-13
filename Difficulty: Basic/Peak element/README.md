<h2><a href="https://www.geeksforgeeks.org/problems/peak-element/1?page=1&sortBy=submissions">Peak element</a></h2><h3>Difficulty Level : Difficulty: Basic</h3><hr><div class="problems_problem_content__Xm_eO" style="user-select: auto;"><p style="user-select: auto;"><span style="font-size: 18px; user-select: auto;">Given an <em style="user-select: auto;">0-indexed</em> array of integers <em style="user-select: auto;">arr[] of size n</em>, find its peak element and return it's index. An element is considered to be peak if it's value is greater than or equal to the values of its adjacent elements (<em style="user-select: auto;">if they exist</em>).</span></p>
<p style="user-select: auto;"><em style="user-select: auto;"><span style="font-size: 18px; user-select: auto;">Note: The output will be&nbsp;1 if the index returned by your function is correct; otherwise, it will be 0.</span></em></p>
<p style="user-select: auto;"><strong style="user-select: auto;"><span style="font-size: 18px; user-select: auto;">Examples :<br style="user-select: auto;"></span></strong></p>
<pre style="user-select: auto;"><strong style="user-select: auto;"><span style="font-size: 18px; user-select: auto;">Input: </span></strong><span style="font-size: 18px; user-select: auto;">n = 3, arr[] = {1, 2, 3} </span><span style="font-size: 18px; user-select: auto;">
<strong style="user-select: auto;">Output:</strong> 1
<strong style="user-select: auto;">Explanation: </strong>If the index returned is 2, then the output printed will be 1. Since arr[2] = 3 is greater than its </span><span style="font-size: 14pt; user-select: auto;">adjacent elements, and there is no element after it, we can consider it as a peak element. </span><span style="font-size: 14pt; user-select: auto;">No other index satisfies the same property, so answer will be printed as 0.</span></pre>
<pre style="user-select: auto;"><strong style="user-select: auto;"><span style="font-size: 18px; user-select: auto;">Input: </span></strong><span style="font-size: 18px; user-select: auto;">n = 7, arr[] = {1, 1, 1, 2, 1, 1, 1}</span><span style="font-size: 18px; user-select: auto;">
<strong style="user-select: auto;">Output: </strong>1<strong style="user-select: auto;">
Explanation: </strong></span><span style="font-size: 18px; user-select: auto;">In this case there are 5 peak elements with indices as {0,1,3,5,6}. Returning any of them will give you correct answer.</span></pre>
<p style="user-select: auto;"><strong style="user-select: auto;"><span style="font-size: 18px; user-select: auto;">Your Task:</span></strong><br style="user-select: auto;"><span style="font-size: 18px; user-select: auto;">You don't have to read&nbsp;input or print anything. Complete the function <em style="user-select: auto;">peakElement()</em> which takes the array <em style="user-select: auto;">arr[] and its size n</em> as input parameters and returns the index of the peak element.</span></p>
<p style="user-select: auto;"><span style="font-size: 18px; user-select: auto;"><strong style="user-select: auto;">Expected Time Complexity:</strong> O( log(n) ).<br style="user-select: auto;"><strong style="user-select: auto;">Expected Auxiliary Space:</strong>&nbsp;O(1)</span></p>
<p style="user-select: auto;"><span style="font-size: 18px; user-select: auto;"><strong style="user-select: auto;">Constraints:</strong><br style="user-select: auto;">1 ≤ n ≤ 10<sup style="user-select: auto;">5</sup><br style="user-select: auto;">1 ≤ arr[i] ≤ 10<sup style="user-select: auto;">6</sup></span></p></div><p><span style=font-size:18px><strong>Company Tags : </strong><br><code>Accolite</code>&nbsp;<code>Amazon</code>&nbsp;<code>Visa</code>&nbsp;<code>Adobe</code>&nbsp;<code>Google</code>&nbsp;<br><p><span style=font-size:18px><strong>Topic Tags : </strong><br><code>Arrays</code>&nbsp;<code>Searching</code>&nbsp;<code>Data Structures</code>&nbsp;<code>Algorithms</code>&nbsp;