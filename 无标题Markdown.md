# Trees
- Depth：  
从根到节点
- level:   
深度+1
- 结点的高度：结点和它路径上叶子节点的最大值
- 树的高度：根结点的高度
- N-ary Tree  
  结点的子节点最多有N个
- Balanced Tree  
  左子树与右子树的高度差≤1  
  check if the tree is balanced:  
  1.traverse from leaf to root
  2.check every node
  3.
- Binary Tree  
1. Complete Binary Tree  
每一层都被填满除了最后一个，都靠左侧填
1. Full Binary Tree  
每个结点的子节点数为0或2
1. Perfect Binary Tree  
full and complete
- BinarySearchTree  
查找：从根结点开始
插入：从根结点开始
删除：删除叶子节点--直接删  
      删除的节点有一个孩子--直接把孩子的子节点连接删除节点的父节点  
      删除的节点有两个孩子--寻找右子树的第一个左孩子结点，交换删除结点与当前结点，然后再删除结点
- AVL Tree  
    is BST and 左子树与右子树高度差≤1  
    用于查找  
  to get AVL tree的旋转操作
- Red-Black Tree    
    is BST tree,  
    every node is either red or black  
    node is colored black  
    two red node cannot be adjacent, ie red parent node cannot have red child node  
    每条从根到叶子节点的路径中黑色结点的数量相同  
    空结点被认为是黑色的
- 2-3 Tree  
    is balanced and ordered search tree  
    所有叶子在同一高度，内部结点有两个或三个孩子，  
    结点有一个Key的话有0个或2个孩子，值介于两个孩子之间，  
    结点有2个key的话有0个或3个孩子，两个值介于3个孩子之间


# Trie
前缀树，解决字符串类查询的问题

