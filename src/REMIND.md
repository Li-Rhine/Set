链表实现集合 不需要实现可比较接口

    LinkedListSet BSTSet (h为高度)
增   O(n)           O(h) = O(logn) 最差也是O(n)
查   O(n)            O(h) = O(logn)
删   O(n)            O(h) = O(logn)

2^h -1 = n --->  h=log₂ (n+1)  = O(log₂n) = O(logn)

二叉树的时间复杂度O(log₂n),链表O(n) 

有序集合中的元素具有顺序性（基于搜索树实现）
无序集合中的元素具有没有顺序（基于哈希表的实现）
