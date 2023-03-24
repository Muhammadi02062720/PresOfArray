> ## What is the array in js ?

 >In JavaScript, arrays aren't primitives but are instead Array objects with the following core characteristics:

 * JavaScript arrays are resizable and can contain a mix of different data types. (When those characteristics are undesirable, use typed arrays instead.)
 * JavaScript arrays are not associative arrays and so, array elements cannot be accessed using arbitrary strings as indexes, but must be accessed using nonnegative integers (or their respective string form) as indexes.
 * JavaScript arrays are zero-indexed: the first element of an array is at index 0, the second is at index 1, and so on — and the last element is at the value of the array's length property minus 1.
 * JavaScript array-copy operations create shallow copies. (All standard built-in copy operations  with    any JavaScript objects create shallow copies, rather than deep copies).

  ![](https://github.com/Muhammadi02062720/PresentationOf-3-/blob/23168bac9912874185639223b2f6645f296af0fe/images/865.jpg)

> ### CHANGE ELEMENTS IN ARRAY

  >You can also add elements or change the elements by accessing the index 
 value. 

![](https://github.com/Muhammadi02062720/PresentationOf-3-/blob/f1ca90dab692352130e34c19a4ddd95b1d70e3df/images/Screenshot_1.png)

>Suppose, an array has two elements. If you try to add an element at index 3 
(fourth element), the third element will be undefined. For example,

![](https://github.com/Muhammadi02062720/PresentationOf-3-/blob/f1ca90dab692352130e34c19a4ddd95b1d70e3df/images/Screenshot_2.png)

> # Array methods

![](https://github.com/Muhammadi02062720/PresentationOf-3-/blob/fa3d61b37ed6446496fe5f485abb613dea549d8a/images/Screenshot_3.png)

> ### Add an Element to an Array

 >If we want to add new elements in array, we have to use belows methods:

  + push();
  + unfhift();
 
>##### if we want to add new element to an array we use the method (push()):
 >The method push() add element on the end of the array'
  >For example:
  ![](https://github.com/Muhammadi02062720/PresentationOf-3-/blob/cfe543d2d55fc6cb42d790c1fd01cdf1b0f6c72a/images/Screenshot_4.png)

>The method unshift() add element to the start of the array
 >For example:
 ![](https://github.com/Muhammadi02062720/PresentationOf-3-/blob/d98db6527c2432a742cf6199bc0e23d511749b00/images/Screenshot_5.png)

 >### Delete an Element in Array

  >If we want to delete some elements of array we use belows methods:

   > * pop();
   > * shift();
 >##### The method pop() delete an element from the end of the array:

  >For example:

  ![](https://github.com/Muhammadi02062720/PresentationOf-3-/blob/e8063f349830a3d3e6d6d8eef81c909efc14bc3a/images/Screenshot_6.png)

>##### The method shift() delete an element from the start of the array:

![](https://github.com/Muhammadi02062720/PresentationOf-3-/blob/ba889dafd630b5a3605fb08abae65608c012711d/images/Screenshot_7.png)

 >## JavaScript array methods:

  >If you want to reverse an elements on array,you have to use the method reverse();

   >How reverse() method does work ?
    >Reverse() method, reverse an elements of array from the end into start:

    ![](https://github.com/Muhammadi02062720/PresentationOf-3-/blob/cc902f08d2dd57456155de93cea3c884d8fb1990/images/Screenshot_8.png)

 >#### Concat();

  ![](https://github.com/Muhammadi02062720/PresentationOf-3-/blob/3c4a28e6f6bb0882e0e5688f2458e5f4535cba5d/images/Screenshot_9.png)

>#### indexOf();

 ![](https://github.com/Muhammadi02062720/PresentationOf-3-/blob/62964d9d16241dac9f43c5f93c3ae7847e89269d/images/Screenshot_10.png)

>#### includes():

![](https://github.com/Muhammadi02062720/PresentationOf-3-/blob/5bb44d436b9cb9594752aa2cfd074bdcd71eaa59/images/Screenshot_11.png)

>#### splice():
 >The splice() method changes the contents of an array by removing or replacing existing elements and/or adding new elements in place. To access part of an array without modifying it, see slice().

  >slice() method takes three parametrs:
  >For example:    slice(start, delete, add);
  ![](https://github.com/Muhammadi02062720/PresentationOf-3-/blob/6c4ac869ac4bf11d41cd5c0ccad5cc3bd90685c8/images/Screenshot_13.png)
  