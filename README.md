<!--
**z-tree/z-tree** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
### What is Z-Tree
Z-Tree is a new data structure for sorting, key-value mapping and multiple other purposes.
Sorting with Z-Tree is not based on comparison and the time complexity of sorting with Z-Tree is O(n). Z-Tree is capable of sorting huge files of 1 GB in memory.
For key-value mapping, the time complexity of adding a key/value or finding a value by key is O(1).

### Z-Tree URL
Please refer to the following URL for more information about Z-Tree. You can also find demo and document in the URL below.
http://www.ztreesoft.com/

### What is Z-Memory Pool
Z-Memory Pool is designed for C/C++ to allocate a large amount of memory. Z-Memory is capable of preventing memory leak and detecting memory overflow.

How does Z-Memory Pool Work
Z-Memory Pool frees memory in destructor following RAII rule.
Z-Memory Pool adds a head byte and a tail byte while allocating memory. If the bytes are changed, Z-Memory Pool knows there is memory overflow.

### What is Z-Memory Pool
The demo application "ZTreeZMemoryPool.exe" only supports UNIX/DOS ANSI/ASCII files. If you want it to work with UNICODE or MAC files, you need to change the code.
Click the buttons "Sort in Ascending Order" or "Sort in Descending Order" to select a file and sort.
Z-Tree can be used for key-value mapping just like hash table. Click the buttons "Key-Value Mapping" to test key-value mapping with Z-Tree.
Z-Tree can be used to find the longest common substring.
Z-Memory Pool can be used to allocate a large amount of memory blocks, avoid memory leaks, detect invalid memory address and detect memory overflow.

### License Agreement
The code and data structure of Z-Tree are licensed under the Apache License, Version 2.0 (the "License");
http://www.apache.org/licenses/LICENSE-2.0

The patent for Z-Tree can also be distributed for free. Please name the data structure "Z-Tree" in your documents or publications.
http://www.patentsencyclopedia.com/app/20140222870
