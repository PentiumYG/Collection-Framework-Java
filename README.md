# Collection Framework Java
* List
    * ArrayList 
        * add()  - O(n)
        * get()
        * addAll()
        * add(index, element)
        * remove(index)   - O(n)
        * remove(Integer.valueOf(_val_))
        * clear() - completely removes all elements of the list(empties the list)
        * set(index, value)   -O(1)
        * contains(element) - checks if element present in the array or not , return true or false   - O(n)
        * size() - length of the list
        * for(Integer element: list){ System.out.println(“the element is: ”+element )}
        * Iterator<Integer> it = list.iterator(); // helps in iterating for collection 
            * while(it.hasNext()){ System.out.println(“iterator: ”+it.next())}

    * Stack
        * Stack<String> st = new Stack<>();
        * st.push(“Pentium”)
        * st.peek() - element present at top
        * st.pop() - removes toppest element

    * LinkedList 
        * Same functions as arrayList.

* Queue
    * LinkedList
        * Queue<Integer> queue = new LinkedList<>();
        * queue.offer(12) - inserting elements in the queue
        * queue.poll() - returns first element that was inserted in the queue. we can print this element
        * queue.peek() - which element will be removed next
        * add() - throws exception in case of error… same as offer()
        *  element() - throws exception in case of error… same as peek(), which returns null if no element found in queue
        * remove() - throws exception in case of error…. same as poll(), which returns null if no element found in queue

    * PriorityQueue
        * PriorityQueue<Integer> pq = new PriorityQueue<>();   or     Queue<Integer> pq = new PriorityQueue<>();
        * same functions like earlier: offer(), peek(), poll(), etc., can be used as it is a part of queue.
        * after adding elements order is changed as min Heap is implemented and since priority is of smallest element therefore the smallest element is printed if we use poll() 
        * To change priority to maximum element we can use comparator as follows:
            * PriorityQueue<Integer> pq = new PriorityQueue<>(Comparator.reverseOrder());

    * ArrayDeque
        * Doubly ended queue
        * ArrayDeque<Integer> add = new ArrayDeque<>();
        * same functions like earlier: offer(), peek(), poll(), etc., can be used as it is a part of queue. adds elements at last 
        * adq.offerFirst() - insert element at the starting
        * adq.offerLast() - insert element at the end     same as offer()
        * adq.peekFirst() - view the starting element   same as peek()
        * adq.peekLast() - view the last element
        * adq.pollFirst() - removes element at the starting    same as poll()
        * adq.pollLast() - removes element at the end

* Set
    * HashSet
        * 

