# Bubble Sort

Bubble sort psuedocode

```
# Write the psuedocode 
START
BubbleSort(array, n):
    for i from 0 to n-1:
        swapped = false
        for j from 0 to n-i-2:
            if array[j] > array[j+1]:  
                swap(array[j], array[j+1])
                swapped = true
        if swapped == false:
            break  // Stop if no swapping occurred (array is sorted)

END
```
