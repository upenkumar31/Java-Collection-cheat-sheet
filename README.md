# Java-Collection-cheat-sheet

#LinkedList.
      LinkedList<Integer> linkedList = new LinkedList<>();
        
        linkedList.add(value); // O(1)
        linkedList.addFirst(value); // O(1)
        linkedList.addLast(value); //
        linkedList.add(index,value);
        linkedList.clear();
        booleanResult = linkedList.addAll(new HashSet<>());
        booleanResult = linkedList.contains(value);
        LinkedList<Integer> cloneList = (LinkedList<Integer>) linkedList.clone();
        linkedList.descendingIterator(); // return iterator which traverse back to head
        value = linkedList.element();  // return first value of list
        value = linkedList.get(index);
        linkedList.getFirst();
        linkedList.getLast();
        index = linkedList.indexOf(value);
        ListIterator listIterator = linkedList.listIterator();
        linkedList.lastIndexOf(value);
        linkedList.offer(value); //add value end ofd the list
        value = linkedList.peek(); // return peek first value
        linkedList.poll(); //return first value and delete node
        linkedList.pollFirst();
        linkedList.pollLast();
        linkedList.pop(); // same as poll
        linkedList.push(value);
        linkedList.remove(new Integer(10000));
        linkedList.remove(index);
        linkedList.removeFirst();
        linkedList.removeFirstOccurrence(value);
        linkedList.removeLast();
        linkedList.removeLastOccurrence(value);
        linkedList.set(index,value);
        Object ar[] = linkedList.toArray();
        linkedList.hashCode();
        linkedList.isEmpty();
        linkedList.size();
        linkedList.removeIf(n ->(n>10));
        linkedList.sort((a,b)->(a>b?a:b));
        Stream<Integer> stream = linkedList.stream();
        linkedList.subList(index,index+5); // from to index
        linkedList.toString();
