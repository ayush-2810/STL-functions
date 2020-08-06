# **STL-functions**  

**STL** is library in **c++** which contains **built** **in** functions which are very **useful** for us to use. We don't have to make them on ourselves.  

This **repository** contains some basic **STL** **functions**.

**sort(a,a+n)** : This functions sort the array a with size n in ascending order.
  - **Time complexity** : O(nlogn)

**__gcd(a,b)** : This function returns the gcd of the two numbers a and b.

**vector\<int> v** : This declares vector in c++. Vectors are same as **dynamic arrays** with the ability to resize itself automatically when an element is inserted or deleted, with their storage being handled automatically by the container. 

**v.size()** : This returns the size of the **vector** v.

**sort(v.begin(),v.end())** : This function sorts the vector in **ascending** order.
  - **Time complexity** : O(nlogn)

**sort(v.begin(),v.end(),greater\<int>)** : This function sorts the vector in descending order.

**s.size()** or **s.length()** : This function returns the size or length of the string s.   

**s.substr(i)** : This function returns the substring of string s from integer i.

**unordered_map<T, T>** : This function creates an unordered map with data type **T** where T can be int, string etc.

**ordered_map<T, T>** : This function creates an ordered map with data type T.

**binary_search(startaddress, endaddress, valuetofind)** : This function search for the element in the array and returns 0 and 1 in logn time complexity. 
  - **Time complexity** : O(logn)

**auto** : Use of auto is to avoid long initializations when creating iterators for containers like vectors, maps, etc.

**a[n]{0}** : Declares dictionary with n number of elements initialized to 0.

**find(a, a+n, value)** : Find element in range.

**list_name.reverse()** : This function **reverses** the list.  

**__builtin_popcount(n)** : This function returns the number of **set bits** in a number n.
  - **Time complexity** : O(1)
