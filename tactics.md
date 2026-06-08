
Characters
----------------

1. freq[ s.charAt (i) - 'a' ] + +;

Bitwise flag : 
----------------

USED TO PROVE THE OCCURANCE OF TWO DIFFERENT THINGS EG. LOWERCASE AND UPPERCASE

1. (oldvalue | 1) = 1     &&   ( 1  | 2 ) = 3

Stack : 
----------------

1. USE while( !stack.isEmpty ) NOT while( stack,peek() ! = null )


Sliding Window
-----------------

1. new_sum = old_sum + num[i] + num[i-k] 

2. make a window then shrink from left or right and remember old constants 

Converting String Into Char Array
----------------------------------

1. char [] ch = str.toCharArray()

HashMap
-----------

1. containsKey()

2. map.put(key,value)

3. map.values

4. Map<String,List<String>>

5. map.keySet()

6. for(Map.Entry<Integer,Integer> e : map.entrySet())

       e.getKey()

       e.getValue()


Boyer-Moore Voting : Leetcode 169 space O(1) time O(n)
--------------------------------------------------------

1. if a target appears more than length_of_array/2 then it survives all cancellations

Comparator
--------------

1. Declaration : Comparator<Integer> obj = new Comparator<>(){

                   public int compare(Integer x , Integer y)

                      return ans

                      if ( ans < 0 ) : x will come before y that means sorting will not happend

                         ( ans > 0 ) : y will come before x that means sorting will happen 

                           ans = 0  : no sorting


Binary Search
-------------------

1. left + (right - left ) /2 

LinkedList
--------------------

1. Slow and Fast pointers 
      slow = head.next
      fast = head.next.next

