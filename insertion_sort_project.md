# Patika_dev_Insertion_Sort_Project

[Patika.dev](https://www.patika.dev/tr)
-------
## Elements of array are: [22,27,16,2,18,6]


## 1. Write the stages of the above sequence according to the sort type.


<ul>
<li>Initially, the first two elements of the array are compared in insertion sort.
Here, 27 is greater than 22. That means both elements are already in ascending order. So, for now, 22 is stored in a sorted sub-array.
<br> 
    [22,27,<b>16</b>,2,18,6]
<br></li>
<li>Now, move to the next two elements and compare them. 27 is greater than 16, so swap them.
<br>
    [22,<b>16</b>,27,2,18,6]
<br> </li>
<li>After swapping, elements 22 and 16 are not sorted, thus swap again..
<br>
    [<b>16</b>,22,27,2,18,6]
<br></li>

<li> The fourth element, the number 2. It is smaller than all of them, swap it again and again. Hence, it settles to the far left.
[16,22,27,<b>2</b>,18,6]<p>
[16,22,<b>2</b>,27,18,6]<p>
[16,<b>2</b>,22,27,18,6]<p>
[<b>2</b>,16,22,27,18,6]<p>

<li> Now, the fifth element, the number 18. Now, 18 is smaller than 27 and 22. Hence, swap again twice.<p>
[2,16,22,<b>18</b>,27,6]<p>
[2,16,<b>18</b>,22,27,6]<p>

<li> Look at the sixth element which is 6. Now, 6 is smaller than 27, 22, 18 and 16. Hence, swap again four times.<p>
[2,16,18,22,<b>6</b>,27]<p>
[2,16,18,<b>6</b>,22,27]<p>
[2,16,<b>6</b>,18,22,27]<p>
[2,<b>6</b>,16,18,22,27]<p>

<li> And, the array is completely sorted.
</ul>

## 2. Write the Big-O notation.

**O(n^2)**  

## 3. Time Complexity: 
### Best Case:<p>
	O(n)
### Average Case:<p>
	O(n2)
### Worst Case:<p>
	O(n2)

**Best Case Complexity** - It occurs when there is no sorting required, i.e. the array is already sorted. The best-case time complexity of insertion sort is O(n).<p>
**Average Case Complexity** - It occurs when the array elements are in jumbled order that is not properly ascending and not properly descending. The average case time complexity of insertion sort is O(n2).<p>
**Worst Case Complexity** - It occurs when the array elements are required to be sorted in reverse order. That means suppose you have to sort the array elements in ascending order, but its elements are in descending order. The worst-case time complexity of insertion sort is O(n2).<p>

## 4. What case does the number 18 fall into after the array is sorted?
18 is in the middle after the sorting it is included in the **Average case**.<p>

## Write the first 4 steps of [7,3,5,8,2,9,4,15.6] according to Insertion Sort.

- [3,7,5,8,2,9,4,15,6] 3 and 7 swapped
- [3,5,7,8,2,9,4,15,6] 7 and 5 swapped
- [2,3,5,7,8,9,4,15,6] 2 is smaller than all of them
- [2,3,4,5,7,8,9,15,6] 4 and 9, 8, 7, 5 swapped
- [2,3,4,5,6,7,8,9,15] And the lastly 6 found its place. The array is sorted successfully.
