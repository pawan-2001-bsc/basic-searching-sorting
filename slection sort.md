# selection Sort

selection sort psuedocode


# Write the psuedocode 
START
SelectionSort(array, n):
    for i from 0 to n-1:
        minIndex = i
        for j from i+1 to n-1:
            if array[j] < array[minIndex]:
                minIndex = j
        swap(array[i], array[minIndex])

END
