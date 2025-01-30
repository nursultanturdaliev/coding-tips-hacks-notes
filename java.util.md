# Important Java `java.util` Class Methods for Coding Challenges

## 1. **`Arrays` Class**
The `Arrays` class contains static methods for working with arrays.

- **`Arrays.sort(T[] a)`**  
  Sorts the specified array into ascending order.
  
- **`Arrays.sort(int[] a)`**  
  Sorts the specified array of primitive ints in ascending order.
  
- **`Arrays.binarySearch(T[] a, T key)`**  
  Searches for the specified element in a sorted array.
  
- **`Arrays.equals(Object[] a, Object[] b)`**  
  Compares two arrays for equality.

- **`Arrays.copyOf(T[] original, int newLength)`**  
  Copies the specified array, truncating or padding with `null` (if necessary) to ensure the copy has the specified length.
  
- **`Arrays.asList(T... a)`**  
  Converts an array to a list.
  
- **`Arrays.fill(T[] array, T val)`**  
  Assigns the specified value to each element of the specified array.

## 2. **`Collections` Class**
The `Collections` class contains static methods for working with collections.

- **`Collections.sort(List<T> list)`**  
  Sorts the specified list into ascending order.
  
- **`Collections.reverse(List<?> list)`**  
  Reverses the order of elements in the list.
  
- **`Collections.shuffle(List<?> list)`**  
  Randomly permutes the elements in the list.
  
- **`Collections.max(Collection<? extends T> coll)`**  
  Returns the maximum element in the collection.

- **`Collections.min(Collection<? extends T> coll)`**  
  Returns the minimum element in the collection.

- **`Collections.frequency(Collection<?> c, Object o)`**  
  Returns the number of occurrences of the specified element in the collection.

- **`Collections.unmodifiableList(List<? extends T> list)`**  
  Returns an unmodifiable view of the specified list.

- **`Collections.singletonList(T o)`**  
  Returns an immutable list containing only the specified object.

- **`Collections.emptyList()`**  
  Returns an empty list (immutable).

- **`Collections.copy(List<? super T> dest, List<? extends T> src)`**  
  Copies all elements from the source list to the destination list.

## 3. **`List` Interface Methods**
Common methods for working with `List` collections.

- **`list.add(E e)`**  
  Appends the specified element to the end of the list.
  
- **`list.remove(int index)`**  
  Removes the element at the specified position in the list.
  
- **`list.get(int index)`**  
  Returns the element at the specified position in the list.
  
- **`list.size()`**  
  Returns the number of elements in the list.

- **`list.contains(Object o)`**  
  Returns `true` if the list contains the specified element.

- **`list.indexOf(Object o)`**  
  Returns the index of the first occurrence of the specified element.

## 4. **`Set` Interface Methods**
Common methods for working with `Set` collections.

- **`set.add(E e)`**  
  Adds the specified element to the set.

- **`set.remove(Object o)`**  
  Removes the specified element from the set.

- **`set.contains(Object o)`**  
  Returns `true` if the set contains the specified element.

- **`set.size()`**  
  Returns the number of elements in the set.

## 5. **`Map` Interface Methods**
Common methods for working with `Map` collections.

- **`map.put(K key, V value)`**  
  Adds the specified key-value pair to the map.

- **`map.get(Object key)`**  
  Returns the value to which the specified key is mapped, or `null` if the map contains no mapping for the key.

- **`map.containsKey(Object key)`**  
  Returns `true` if the map contains a mapping for the specified key.

- **`map.containsValue(Object value)`**  
  Returns `true` if the map maps one or more keys to the specified value.

- **`map.remove(Object key)`**  
  Removes the mapping for a key from the map if it is present.

- **`map.size()`**  
  Returns the number of key-value mappings in the map.

- **`map.keySet()`**  
  Returns a `Set` view of the keys contained in the map.

- **`map.values()`**  
  Returns a `Collection` view of the values contained in the map.

- **`map.entrySet()`**  
  Returns a `Set` view of the mappings contained in the map.

## 6. **`Queue` Interface Methods**
Common methods for working with `Queue` collections.

- **`queue.add(E e)`**  
  Inserts the specified element into the queue.
  
- **`queue.poll()`**  
  Retrieves and removes the head of the queue.

- **`queue.peek()`**  
  Retrieves, but does not remove, the head of the queue.

- **`queue.size()`**  
  Returns the number of elements in the queue.

## 7. **`Deque` Interface Methods**
Common methods for working with `Deque` collections.

- **`deque.addFirst(E e)`**  
  Inserts the specified element at the front of the deque.

- **`deque.addLast(E e)`**  
  Inserts the specified element at the end of the deque.

- **`deque.removeFirst()`**  
  Removes and returns the first element of the deque.

- **`deque.removeLast()`**  
  Removes and returns the last element of the deque.

- **`deque.peekFirst()`**  
  Retrieves, but does not remove, the first element of the deque.

- **`deque.peekLast()`**  
  Retrieves, but does not remove, the last element of the deque.

## 8. **`Iterator` Interface Methods**
Methods for iterating over collections.

- **`iterator.hasNext()`**  
  Returns `true` if the iteration has more elements.

- **`iterator.next()`**  
  Returns the next element in the iteration.

- **`iterator.remove()`**  
  Removes from the underlying collection the last element returned by the iterator.

## 9. **`Map.Entry` Methods**
Used when working with the entries in a `Map`.

- **`entry.getKey()`**  
  Returns the key associated with the entry.

- **`entry.getValue()`**  
  Returns the value associated with the entry.

- **`entry.setValue(V value)`**  
  Replaces the value associated with the entry.

## 10. **`Objects` Class**
Utility methods for working with objects.

- **`Objects.equals(Object a, Object b)`**  
  Returns `true` if the two objects are equal.

- **`Objects.hash(Object... values)`**  
  Returns a hash code for the specified objects.

- **`Objects.isNull(Object obj)`**  
  Returns `true` if the specified object is `null`.

- **`Objects.nonNull(Object obj)`**  
  Returns `true` if the specified object is not `null`.

- **`Objects.requireNonNull(T obj)`**  
  Ensures the specified object is non-`null`, throwing a `NullPointerException` if it is.

## 11. **`Optional` Class Methods**
Useful for handling `null` values.

- **`Optional.of(T value)`**  
  Returns an `Optional` describing the specified value.

- **`Optional.empty()`**  
  Returns an empty `Optional` instance.

- **`Optional.ofNullable(T value)`**  
  Returns an `Optional` containing the value if non-`null`, or empty if `null`.

- **`optional.get()`**  
  Returns the value if present, otherwise throws `NoSuchElementException`.

- **`optional.ifPresent(Consumer<? super T> action)`**  
  Executes the specified action if the value is present.

- **`optional.orElse(T other)`**  
  Returns the value if present, or the specified `other` value if not.

  ## 12. **`Stack` Class**
The `Stack` class represents a last-in-first-out (LIFO) stack of objects.

- **`stack.push(E item)`**  
  Pushes an item onto the top of the stack.

- **`stack.pop()`**  
  Removes the item at the top of the stack and returns it.

- **`stack.peek()`**  
  Looks at the object at the top of the stack without removing it.

- **`stack.empty()`**  
  Tests whether the stack is empty.

- **`stack.search(Object o)`**  
  Returns the 1-based position of the object in the stack.

## 13. **`PriorityQueue` Class**
A `PriorityQueue` is a queue where elements are ordered based on their priority.

- **`pq.offer(E e)`**  
  Inserts the specified element into the queue.

- **`pq.poll()`**  
  Retrieves and removes the head of the queue.

- **`pq.peek()`**  
  Retrieves, but does not remove, the head of the queue.

- **`pq.remove(Object o)`**  
  Removes a single instance of the specified element from the queue.

- **`pq.comparator()`**  
  Returns the comparator used to order the elements, or `null` if the elements are ordered using their natural ordering.

## 14. **`LinkedList` Class**
A doubly linked list that implements the `List`, `Deque`, and `Queue` interfaces.

- **`linkedList.addFirst(E e)`**  
  Adds the specified element at the beginning of the list.

- **`linkedList.addLast(E e)`**  
  Appends the specified element to the end of the list.

- **`linkedList.removeFirst()`**  
  Removes the first element of the list.

- **`linkedList.removeLast()`**  
  Removes the last element of the list.

- **`linkedList.getFirst()`**  
  Returns the first element of the list.

- **`linkedList.getLast()`**  
  Returns the last element of the list.

## 15. **`TreeMap` Class**
A `TreeMap` is a map that is sorted based on the natural ordering of its keys, or by a `Comparator` provided at map creation.

- **`treeMap.put(K key, V value)`**  
  Inserts a key-value pair into the map.

- **`treeMap.get(Object key)`**  
  Retrieves the value for the specified key, or `null` if the key is not found.

- **`treeMap.remove(Object key)`**  
  Removes the key-value pair associated with the specified key.

- **`treeMap.firstKey()`**  
  Returns the first (lowest) key in the map.

- **`treeMap.lastKey()`**  
  Returns the last (highest) key in the map.

- **`treeMap.headMap(K toKey)`**  
  Returns a view of the portion of the map whose keys are less than the specified key.

- **`treeMap.subMap(K fromKey, K toKey)`**  
  Returns a view of the portion of the map between the specified keys.

## 16. **`HashMap` Class**
A `HashMap` is a map that provides constant-time performance for basic operations like `get`, `put`, and `remove`.

- **`hashMap.put(K key, V value)`**  
  Inserts a key-value pair into the map.

- **`hashMap.get(Object key)`**  
  Retrieves the value for the specified key.

- **`hashMap.remove(Object key)`**  
  Removes the entry associated with the specified key.

- **`hashMap.containsKey(Object key)`**  
  Checks if the map contains the specified key.

- **`hashMap.containsValue(Object value)`**  
  Checks if the map contains the specified value.

- **`hashMap.isEmpty()`**  
  Returns `true` if the map is empty.

## 17. **`EnumSet` Class**
A specialized `Set` for enum types, providing a high-performance set implementation.

- **`enumSet.add(E e)`**  
  Adds the specified element to the set.

- **`enumSet.remove(Object o)`**  
  Removes the specified element from the set.

- **`enumSet.contains(Object o)`**  
  Checks if the set contains the specified element.

- **`enumSet.iterator()`**  
  Returns an iterator over the elements in the set.

- **`enumSet.complementOf(EnumSet<E> set)`**  
  Returns the complement of the given enum set.

## 18. **`Collections.synchronizedList()`**
Creates a thread-safe (synchronized) version of a list.

- **`Collections.synchronizedList(List<T> list)`**  
  Returns a synchronized (thread-safe) list backed by the specified list.

## 19. **`BitSet` Class**
A `BitSet` is a growable array of bits that can be set, cleared, and queried.

- **`bitSet.set(int bitIndex)`**  
  Sets the bit at the specified index to `true`.

- **`bitSet.clear(int bitIndex)`**  
  Clears the bit at the specified index (sets it to `false`).

- **`bitSet.get(int bitIndex)`**  
  Returns the value of the bit at the specified index (`true` or `false`).

- **`bitSet.cardinality()`**  
  Returns the number of bits set to `true` in the bit set.

- **`bitSet.and(BitSet set)`**  
  Performs a logical AND of this `BitSet` with the specified `BitSet`.

- **`bitSet.or(BitSet set)`**  
  Performs a logical OR of this `BitSet` with the specified `BitSet`.

## 20. **`Collections.sort()` with Comparators**
You can sort a collection using custom sorting logic by passing a `Comparator`.

- **`Collections.sort(List<T> list, Comparator<? super T> c)`**  
  Sorts the specified list according to the order induced by the specified comparator.

## 21. **`Locale` Class**
Useful for handling locale-specific operations (like language, country, etc.).

- **`locale.getCountry()`**  
  Returns the country associated with this locale.

- **`locale.getLanguage()`**  
  Returns the language associated with this locale.

- **`locale.getVariant()`**  
  Returns the variant code for the locale.

## 22. **`ThreadLocal` Class**
Helps in creating variables that are local to the current thread.

- **`threadLocal.get()`**  
  Retrieves the value for the current thread.

- **`threadLocal.set(T value)`**  
  Sets the value for the current thread.

- **`threadLocal.remove()`**  
  Removes the value for the current thread.

## 23. **`ConcurrentHashMap` Class**
A thread-safe version of `HashMap` designed for concurrent access.

- **`concurrentMap.putIfAbsent(K key, V value)`**  
  Inserts the key-value pair only if the key is not already present.

- **`concurrentMap.compute(K key, BiFunction<? super K, ? super V, ? extends V> remappingFunction)`**  
  Computes a new value for the specified key.

- **`concurrentMap.remove(Object key, Object value)`**  
  Removes the entry only if the key is associated with the specified value.

- **`concurrentMap.putAll(Map<? extends K, ? extends V> m)`**  
  Copies all of the mappings from the specified map to this map.

## 24. **`StringTokenizer` Class**
A legacy class for breaking a string into tokens.

- **`tokenizer.nextToken()`**  
  Returns the next token from the string tokenizer.

- **`tokenizer.hasMoreTokens()`**  
  Returns `true` if there are more tokens to be parsed.

## 25. **`Timer` and `TimerTask` Classes**
Used for scheduling tasks to run after a delay or periodically.

- **`timer.schedule(TimerTask task, long delay)`**  
  Schedules a task for execution after the specified delay.

- **`timer.scheduleAtFixedRate(TimerTask task, long delay, long period)`**  
  Schedules a task to execute periodically at a fixed rate.

## 26. **`Queue` Interface Methods (Additional)**
Methods that are helpful when working with `Queue` collections.

- **`queue.remove(Object o)`**  
  Removes the first occurrence of the specified element from the queue.

- **`queue.clear()`**  
  Removes all elements from the queue.

---

### Key Notes:
- Collections: `List`, `Set`, `Map` are the most commonly used collection types.
- For coding challenges, focus on methods that help with sorting, searching, iterating, and removing elements efficiently.
- Using utility classes like `Arrays`, `Collections`, and `Objects` can simplify common tasks and reduce boilerplate code.

This list should help with most typical coding challenges where data manipulation, searching, and sorting are common.
