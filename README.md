# flatten-array

To achieve what was asked for with this challange.

[[1,2,[3]],4] -> [1,2,3,4]. 

The array is nested at 2 levels. So I will first create a variable for the desired flattened array and called flatArray. Next I will use the JS code to flatten it to [1,2,3,4].

----

var flatArray = arr.flat(depth);

var arr1 = [[1,2,[3]],4];
arr1.flat(2); 

This should return with an flatArray looking like [1,2,3,4].
