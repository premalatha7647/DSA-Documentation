



# Time and Space complexity:
    1. O(1)
        when the program return the direct value 
        for example:
          Find the 5th element in the array

                function findElement(a){

                    return a[5]
                }
            Time complexity is very low here even the input size increases.

    2. O(log n)
        
        In binary search (sorted array), until we find the given element, the array will divided by 2

        n => number of elements or length of the array

        arr=[1,2,3,4,5,6,7,8]
        
        n * 1/2 * 1/2 * 1/2 * 1/2 .... x = 1 
        n / 2^x =1
        x= log2 n
        x log n



    3. O(n)

        when the loops run n times .

        for(i =0; i<n; i++){
            ....
        }

    4. O(n log n)

     for(i =0; i<n; i++){
           
           logn =>> oprations
        }

    5. O(n^2) or O(n^3),....

        when more then one loop has to create for oparations

        for(i =0; i<n; i++){
            ....
            for(j=0; j<n; j++){

            }
        }

    6. O(2^n)
        when different types of oprations runs on n times
            for(i =0; i<n; i++){
            ....
           }
            for(j=0; j<n; j++){
            ....
            }

    7. O(n!)

    