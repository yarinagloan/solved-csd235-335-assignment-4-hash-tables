Download Link: https://assignmentchef.com/product/solved-csd235-335-assignment-4-hash-tables
<br>
For this assignment you will implement a hash table that meets the following requirements:

the underlying data structure, hashArray, is a fixed size Java array (not an ArrayList) of type Integer

(not int)

methods:

HashTable( int sz )  //a constructor that takes a single int parameter void insert(Integer key)  //takes an Integer parameter and stores it in the list void remove(Integer key)  // find an item in the hash table and remove it

Integer search(Integer key)  // searches for an item in the hash table and if found, return it. Otherwise, return null void toString()  // outputs the contents of the hash table, one row per element in hashArray int size()  // return the number of elements in all of the chains int size(int index) // return the number of elements in the indexed chain double loadFactor()  // a method the calculates and returns the loading factor to the caller

and the following private method(s):

rehash() – instantiate an Integer array that is the next prime number greater than twice the size of the original hash array.  Then for each element in the original hash array, rehash it into new array

(don’t forget that the hash function is based  on the size of the hash array)

When you are finished, upload the java files to canvas.

<h2>Extra Credit</h2>




In order to earn extra credit on this assignment, you have fulfill all of the requirements of the assignment. If that’s the case, the for extra credit points on this assignment if the loading factor drops below 0.2, reduce the size of hashArray by half, and rehash. (Hint: If you’re adding data to an empty hash table, and the loading factor moves up to or above 0.2, that’s not dropping to 0.2. The change in loading factor has to be dropping when the decision is made to reduce the size of the hash array).