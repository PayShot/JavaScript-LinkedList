JavaScript-LinkedList
---------------------

A complete data structure of a linked-list in JavaScript.

```JavaScript
var linkedList = new LinkedList();

// --- Example 1 --------------------------------------------------
linkedList.push('one');
linkedList.push('two');
linkedList.push('three');

linkedList.pop(); // return 'one'
linkedList.pop(); // return 'two'
linkedList.pop(); // return 'three'
linkedList.pop(); // return undefined

// --- Example 2 --------------------------------------------------
linkedList.push('A');
linkedList.push('B');
linkedList.push('D');
linkedList.add('C', 2); // Add 'C' in index 2 (between 'B' and 'D')

linkedList.length(); // return 4

linkedList.pop(); // return 'A'
linkedList.pop(); // return 'B'
linkedList.pop(); // return 'C'
linkedList.pop(); // return 'D'

linkedList.length(); // return 0

linkedList.pop(); // return undefined

linkedList.length(); // return 0

// --- Example 3 --------------------------------------------------
linkedList.push('I');
linkedList.push('II');
linkedList.push('III');
linkedList.push('IIII');
linkedList.push('V');

linkedList.remove(3); // Remove 'IIII'
linkedList.add('IV', 3); // Add 'IV' beetween 'III' and 'V'
```
