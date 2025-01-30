# Java Utility Functions and Classes for Competitive Programming

## 1. **`Arrays` Class**
   - **Purpose**: Provides utility methods to manipulate arrays (sorting, binary search, etc.).
   - **Key Methods**:
     - `Arrays.sort(array)` – Sorts the array in ascending order.
     - `Arrays.binarySearch(array, key)` – Performs binary search on a sorted array.
     - `Arrays.fill(array, value)` – Fills the array with the specified value.
     - `Arrays.equals(array1, array2)` – Compares two arrays for equality.
     - `Arrays.copyOf(array, newLength)` – Copies an array to a new array with a specified length.

   - **Example**:
     ```java
     int[] arr = {1, 5, 2, 8, 3};
     Arrays.sort(arr);  // [1, 2, 3, 5, 8]
     System.out.println(Arrays.toString(arr));  // Outputs: [1, 2, 3, 5, 8]
     ```

## 2. **`Collections` Class**
   - **Purpose**: Provides utility methods for collections like Lists, Sets, and Maps.
   - **Key Methods**:
     - `Collections.sort(list)` – Sorts a list in ascending order.
     - `Collections.reverse(list)` – Reverses a list.
     - `Collections.binarySearch(list, key)` – Binary search on a sorted list.
     - `Collections.max(list)` – Finds the maximum element in the list.
     - `Collections.min(list)` – Finds the minimum element in the list.

   - **Example**:
     ```java
     List<Integer> list = Arrays.asList(4, 2, 8, 6);
     Collections.sort(list);
     System.out.println(list);  // Outputs: [2, 4, 6, 8]
     ```

## 3. **`Math` Class**
   - **Purpose**: Provides mathematical operations (e.g., max, min, sqrt, random, etc.).
   - **Key Methods**:
     - `Math.max(a, b)` – Returns the maximum of two numbers.
     - `Math.min(a, b)` – Returns the minimum of two numbers.
     - `Math.abs(x)` – Returns the absolute value of x.
     - `Math.pow(a, b)` – Returns a raised to the power of b.
     - `Math.sqrt(x)` – Returns the square root of x.

   - **Example**:
     ```java
     int a = 9, b = 16;
     System.out.println(Math.max(a, b));  // Outputs: 16
     System.out.println(Math.sqrt(b));    // Outputs: 4.0
     ```

## 4. **`StringBuilder` Class**
   - **Purpose**: Efficient string manipulation by using mutable objects.
   - **Key Methods**:
     - `append(value)` – Appends the value to the current string.
     - `insert(index, value)` – Inserts a value at the specified index.
     - `reverse()` – Reverses the string.
     - `toString()` – Converts the `StringBuilder` to a string.

   - **Example**:
     ```java
     StringBuilder sb = new StringBuilder("Hello");
     sb.append(" World");
     System.out.println(sb.toString());  // Outputs: Hello World
     ```

## 5. **`HashMap` Class**
   - **Purpose**: Hash-based map implementation to store key-value pairs.
   - **Key Methods**:
     - `put(key, value)` – Adds a key-value pair to the map.
     - `get(key)` – Retrieves the value for a given key.
     - `containsKey(key)` – Checks if the map contains the specified key.
     - `remove(key)` – Removes the key-value pair from the map.

   - **Example**:
     ```java
     HashMap<String, Integer> map = new HashMap<>();
     map.put("a", 1);
     map.put("b", 2);
     System.out.println(map.get("a"));  // Outputs: 1
     ```

## 6. **`PriorityQueue` Class**
   - **Purpose**: A queue that retrieves elements in a specific order, typically based on priority.
   - **Key Methods**:
     - `add(value)` – Adds an element to the priority queue.
     - `poll()` – Retrieves and removes the highest-priority element.
     - `peek()` – Retrieves the highest-priority element without removing it.

   - **Example**:
     ```java
     PriorityQueue<Integer> pq = new PriorityQueue<>();
     pq.add(5);
     pq.add(1);
     pq.add(3);
     System.out.println(pq.poll());  // Outputs: 1
     ```

## 7. **`Deque` Interface (LinkedList Implementation)**
   - **Purpose**: A double-ended queue, can be used as a stack or a queue.
   - **Key Methods**:
     - `addFirst(value)` – Adds an element to the front.
     - `addLast(value)` – Adds an element to the end.
     - `removeFirst()` – Removes and returns the front element.
     - `removeLast()` – Removes and returns the last element.

   - **Example**:
     ```java
     Deque<Integer> deque = new LinkedList<>();
     deque.addFirst(1);
     deque.addLast(2);
     System.out.println(deque.removeFirst());  // Outputs: 1
     ```

## 8. **`BitSet` Class**
   - **Purpose**: Efficiently stores bits in a sequence (useful for bit manipulation).
   - **Key Methods**:
     - `set(index)` – Sets the bit at the specified index.
     - `clear(index)` – Clears the bit at the specified index.
     - `get(index)` – Retrieves the value of the bit at the specified index.

   - **Example**:
     ```java
     BitSet bitSet = new BitSet();
     bitSet.set(0);
     bitSet.set(3);
     System.out.println(bitSet.get(0));  // Outputs: true
     ```

## 9. **`Scanner` Class**
   - **Purpose**: Reading input from various sources (keyboard, files, etc.).
   - **Key Methods**:
     - `nextInt()` – Reads the next integer.
     - `nextLine()` – Reads the next line of input.
     - `nextDouble()` – Reads the next double value.

   - **Example**:
     ```java
     Scanner sc = new Scanner(System.in);
     int a = sc.nextInt();
     System.out.println("You entered: " + a);
     ```

## 10. **`System` Class**
   - **Purpose**: Provides system-related utility functions.
   - **Key Methods**:
     - `System.nanoTime()` – Returns the current value of the most precise available system timer in nanoseconds.
     - `System.currentTimeMillis()` – Returns the current time in milliseconds.

   - **Example**:
     ```java
     long start = System.nanoTime();
     // Perform some operations
     long end = System.nanoTime();
     System.out.println("Time taken: " + (end - start) + " nanoseconds.");
     ```

## 11. **`Math.random()` Method**
   - **Purpose**: Generates a random double between 0.0 (inclusive) and 1.0 (exclusive).
   - **Example**:
     ```java
     double rand = Math.random();
     System.out.println(rand);  // Outputs a random value between 0 and 1
     ```

## 12. **`Integer` Class (Utility Methods)**
   - **Purpose**: Provides utility methods for converting, parsing, and manipulating integers.
   - **Key Methods**:
     - `Integer.parseInt(str)` – Parses a string as an integer.
     - `Integer.valueOf(str)` – Converts a string to an Integer object.
     - `Integer.bitCount(n)` – Returns the number of set bits in the integer.

   - **Example**:
     ```java
     String s = "123";
     int num = Integer.parseInt(s);
     System.out.println(num);  // Outputs: 123
     ```

## 13. **`Long` Class**
   - **Purpose**: Provides utility methods for long integers.
   - **Key Methods**:
     - `Long.parseLong(str)` – Parses a string as a long integer.
     - `Long.bitCount(n)` – Returns the number of set bits in the long.

   - **Example**:
     ```java
     long n = 10000000000L;
     System.out.println(Long.toBinaryString(n));
     ```

## 14. **`HashSet` Class**
   - **Purpose**: Hash-based implementation of the `Set` interface for storing unique elements.
   - **Key Methods**:
     - `add(value)` – Adds an element to the set.
     - `contains(value)` – Checks if the set contains the element.
     - `remove(value)` – Removes the element from the set.

   - **Example**:
     ```java
     HashSet<Integer> set = new HashSet<>();
     set.add(1);
     set.add(2);
     System.out.println(set.contains(1));  // Outputs: true
     ```

## 15. **`Stream API` (from Java 8)**
   - **Purpose**: Allows functional-style operations on collections of elements (filtering, mapping, etc.).
   - **Key Methods**:
     - `filter()` – Filters elements based on a condition.
     - `map()` – Transforms each element.
     - `collect()` – Collects the result of the stream into a collection.

   - **Example**:
     ```java
     List<Integer> numbers = Arrays.asList(1, 2, 3, 4, 5);
     List<Integer> evenNumbers = numbers.stream()
                                        .filter(n -> n % 2 == 0)
                                        .collect(Collectors.toList());
     System.out.println(evenNumbers);  // Outputs: [2, 4]
     ```

---

### Tips and Tricks:
1. **Precompute Results**: Precompute answers for small ranges or queries that can be used repeatedly.
2. **Efficient Input/Output**: Use `BufferedReader` and `BufferedWriter` for faster I/O.
3. **Modular Arithmetic**: Keep results within bounds using `% MOD`.
4. **Greedy Algorithms**: Often used in optimization problems—ensure local choices are optimal.
5. **Binary Search**: Utilize for problems involving sorted data (e.g., finding the position of an element).
6. **Sliding Window**: Useful for problems involving subsequences and subarrays.

