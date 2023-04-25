# Linear_search
Linear Search is defined as a sequential search algorithm that starts at one end and goes through each element of a list until the desired element is found, otherwise the search continues till the end of the data set.


How Linear Search Works?
*Step 1: First, read the search element (Target element) in the array.
*Step 2: Set an integer i = 0 and repeat steps 3 to 4 till i reaches the end of the array.
*Step 3: Match the key with arr[i].
*Step 4: If the key matches, return the index. Otherwise, increment i by 1.


Illustration of Linear Search:
Consider the array arr[] = {10, 50, 30, 70, 80, 20, 90, 40} and key = 20

Step 1: Set i = 0 and check key with arr[0].

Step 2: key and arr[0] are not the same. So make i = 1 and match key with arr[1].

Step 3: arr[1] and key are different. Increment i and compare key with arr[2].

Step 4: arr[2] is not the same with key. Increment i and compare key with arr[3].

Step 5: key and arr[3] are different. Make i = 4 and compare key with arr[4].

Step 6: key and arr[4] are not same. Make i = 5 and match key with arr[5].


Time Complexity:


Best Case:
In the best case, the key might be present at the first index. So the best case complexity is O(1)

Worst Case:
In the worst case, the key might be present at the last index i.e., opposite to the end from which the search has started in the list. So the worst case complexity is O(N) where N is the size of the list.

Average Case:
O(N)

Auxiliary Space: O(1) as except the variable to iterate through the list, no other variable is used.
