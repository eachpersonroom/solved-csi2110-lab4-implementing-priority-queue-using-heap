Download Link: https://assignmentchef.com/product/solved-csi2110-lab4-implementing-priority-queue-using-heap
<br>
<strong>Implementing Priority Queue Using Heap</strong>

In lecture you have studied priority queues implementations using sorted and unsorted sequences. We analyzed that both implementations take O(n) for one of the two main operations of the priority queue (insert and removeMin).By implementing a priority queue using a heap we can execute insert and removeMin in O(log(n)) time reducing time complexity while still storing the Priority Queue in the most efficient amount of space.

The task for this lab involves writing the full implementation of a priority queue using an array implementation for a heap as the data structure. Your TA should review how to implement a <a href="arrayHeap.pdf">heap using an array</a>.Your TA should also review the upHeap and downHeap operations needed to do insert and removeMin operations, respectively; the main reference for this are the slides on heap priority queues covered in class.

Task details:

<ol>

 <li>Review the given PriorityQueue&amp;ltK,V&amp;gt interface and Entry&amp;ltK,V&amp;gt class.</li>

 <li>Complete HeapPriorityQueue&amp;ltK,V&amp;gt class using a heap, stored as an array of elements Entry&amp;ltK,V&amp;gt.</li>

 <li>Test HeapPriorityQueue&amp;ltK,V&amp;gt using HeapPriorityQueueTest.</li>

</ol>


