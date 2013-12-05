<p style="font-size:1 6pt">JavaScript-LinkedList</p>

<p>A complete data structure of a linked-list in JavaScript.</p>

<code>
var linkedList = new LinkedList();<br />
<br />
// --- Example 1 --------------------------------------------------<br />
linkedList.push('one');<br />
linkedList.push('two');<br />
linkedList.push('three');<br />
<br />
linkedList.pop(); // return 'one'<br />
linkedList.pop(); // return 'two'<br />
linkedList.pop(); // return 'three'<br />
linkedList.pop(); // return undefined<br />
<br />
// --- Example 2 --------------------------------------------------<br />
linkedList.push('A');<br />
linkedList.push('B');<br />
linkedList.push('D');<br />
linkedList.add('C', 2); // Add 'C' in index 2 (between 'B' and 'D')<br />
<br />
linkedList.length(); // return 4<br />
<br />
linkedList.pop(); // return 'A'<br />
linkedList.pop(); // return 'B'<br />
linkedList.pop(); // return 'C'<br />
linkedList.pop(); // return 'D'<br />
<br />
linkedList.length(); // return 0<br />
<br />
linkedList.pop(); // return undefined<br />
<br />
linkedList.length(); // return 0<br />
<br />
// --- Example 3 --------------------------------------------------<br />
linkedList.push('I');<br />
linkedList.push('II');<br />
linkedList.push('III');<br />
linkedList.push('IIII');<br />
linkedList.push('V');<br />
<br />
linkedList.remove(3); // Remove 'IIII'<br />
linkedList.add('IV', 3); // Add 'IV' beetween 'III' and 'V'<br />
</code>