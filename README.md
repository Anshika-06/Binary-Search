# Binary-Search

Binary search is a 'divide and search' algorithm which requires the initial array to be sorted before searching.
It is called binary because it splits the array into two halves as part of the algorithm. 
Binary search is faster than linear search, especially for large arrays. As the size of the array increases, 
the time it takes to perform a linear search increases linearly.


Syntax:
while until the pointers low and high meet each other.
  
  mid = (low + high)/2
   
   if (x == arr[mid])
      
   return mid
    
   else if (x > arr[mid]) // x is on the right side
       
   low = mid + 1
   
   else                       // x is on the left side
       
   high = mid - 1
   
   
        
  ![binary-search](https://user-images.githubusercontent.com/125429580/234466947-2f56a8aa-221b-47a2-883f-225288976a9f.gif)
