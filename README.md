# bubble-search

Bubble sort in C to arrange numbers in ascending order; you can modify it for descending order and can also sort strings. 
The bubble sort algorithm isn't efficient as its both average-case as well as worst-case complexity are O(n2).

![image](https://user-images.githubusercontent.com/110607289/234481234-9a997420-2cc2-4e21-b669-fc3044440c37.png)


Bubble sort algorithm
Start at index zero, compare the element with the next one (a[0] & a[1] (a is the name of the array)), and swap if a[0] > a[1]. 
Now compare a[1] & a[2] and swap if a[1] > a[2]. Repeat this process until the end of the array. After doing this, the largest element is present at the end. 
This whole thing is known as a pass. In the first pass, we process array elements from [0,n-1].
Repeat step one but process array elements [0, n-2] because the last one, i.e., a[n-1], is present at its correct position. 
After this step, the largest two elements are present at the end.
Repeat this process n-1 times.

We can use the Bubble Sort algorithm to check if an array is sorted or not.
If no swapping takes place, then the array is sorted. We can improve its best-case complexity to O(n).
