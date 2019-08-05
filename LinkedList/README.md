单链表
==========================
创建单链表思路
--------------------------
1.先创建一个head头节点，作用为表示单链表表头
2.后面每添加一个节点，就直接添加到链表的最后
## 遍历单链表

通过一个辅助节点，帮助遍历整个链表

代码实现了单链表数据的增删改及添加后排序功能

## 单链表的应用实例(思路分析)
### 直接添加到链表尾部
1.先创建head头节点来表示单链表表头  
2.后面每添加一个节点,就直接添加到链表的最后  
3. 通过一个辅助变量遍历整个链表  
### 按定义编号顺序添加(先排序后插入)
1.首先通过辅助变量(指针)找到添加节点的位置  
2.新的节点.next = temp.next  
3.将temp.next = 新的节点  
### 修改节点功能
1.通过辅助变量temp遍历找到待修改节点  
2.temp.xxx = newNode.xxx  
### 删除节点功能
1.通过辅助变量temp遍历找待删除节点的前一个节点  
2.temp.next = temp.next.next  
3.删除后节点将不会有其他引用指向,会被垃圾回收机制回收  
