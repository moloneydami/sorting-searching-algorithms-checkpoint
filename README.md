The Sorting & Searching Algorithm For A Card

1. Start with an array, arr, of length n.
2. Iterate over each index i from 1 to n-1.
3. Set the current element to be inserted as arr[i].
4. Initialize a variable j as i-1.
5. While j is greater than or equal to 0 and arr[j] is greater than the current element:
- Shift arr[j] to the right by one position, i.e., arr[j+1] = arr[j].
- Decrement j by 1.
6. Insert the current element at the correct position in the sorted sequence, i.e., arr[j+1] = current element.
7. Repeat steps 3-6 until all elements have been processed.