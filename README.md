Download Link: https://assignmentchef.com/product/solved-ch08-320201-homework-9-hash-tables-and-greedy-algorithms
<br>
<h2>Problem 1: Hash Tables</h2>

<ul>

 <li>Given the sequence <em>&lt; </em>3<em>,</em>10<em>,</em>2<em>,</em>4 <em>&gt;</em>, apply the double-hashing strategy for open addressing to store the sequence in the given order in a hash table of size <em>m </em>= 5 with hash functions <em>h</em><sub>1</sub>(<em>k</em>) = <em>k </em>mod 5 and <em>h</em><sub>2</sub>(<em>k</em>) = (7<em>.k</em>) mod 8. Document all collisions and how they are resolved (provide computations).</li>

 <li><em>Implement </em>a hash table that supports insertion and querying with open addressing using linear probing. The implementation should be consistent with the following class specification:</li>

</ul>

<table width="599">

 <tbody>

  <tr>

   <td width="599">class Node{ public:int key; int value;Node(int key, int value);} class HashTable{ private: Node **arr; int maxSize; int currentSize;public:HashTable(); hashCode(int key); void insertNode(int key, int value); int get(int key); bool isEmpty();}</td>

  </tr>

 </tbody>

</table>

5

10

15

<h2>Problem 2: Greedy Algorithms</h2>

<ul>

 <li>Show that a greedy algorithm for the activity-selection problem that makes the greedy choice of selecting the activity with shortest duration may fail at producing a globally optimal solution.</li>

 <li>Assuming an unsorted sequence of activities, derive a greedy algorithm for the activity-selection problem that selects the activity with the final starting time. Your solution should not simply sort the activities and then select the activity.</li>

</ul>