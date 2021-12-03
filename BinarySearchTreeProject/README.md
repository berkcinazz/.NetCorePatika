## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

 # Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

   ### 1.          [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
   ###                /                     \
   ### 2.      [7, 5, 1, 8, 3]            [6, 0, 9, 4, 2]
   ###          /           \                   /        \
   ### 3.    [7, 5, 1]      [8, 3]         [6, 0, 9]    [4, 2]
   ###        /      \       /   \          /      \     /   \
   ### 4.  [7, 5]    [1]   [8]   [3]     [6, 0]    [9]  [4]  [2]
   ###     /    \     /    /       \      /  \      /    /    \
   ### 5. [7]   [5]  [1]  [8]     [3]   [6]  [0]  [9]   [4]   [2]
   ###     \     /   /      \      /     \    /    /     \    /
   ### 6.   [5, 7]  [1]      [3, 8]      [0, 6]  [9]     [2, 4]
   ###         \     /         /           \     /         /
   ### 7.     [1, 5, 7]     [3, 8]        [0, 6, 9]     [2, 4]
   ###             \          /                \         /
   ### 8.         [1, 3, 5, 7, 8]             [0, 2, 4, 6, 9]
   ###                        \                 /
   ### 9.                [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]              

 [Binary Search Tree Project](https://app.patika.dev/moduller/veri-yapilari-ve-algoritmalar/binary-search-tree-proje)