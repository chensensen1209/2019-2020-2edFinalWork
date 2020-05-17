# DataStructure_FinalWork
题目一（个人完成，共30分）: 带环、相交链表问题

设计目的：

  掌握链表的基本操作。

  掌握带环链表的相关操作算法。

内容：
  基于课程上机关于单链表的作业，要求进一步实现以下需求:


1.构造链表后，将元素值为m和n（从键盘输入，如有多个相同元素值，仅考虑首个出现的元素）的节点建立连接，
注意判断节点出现的先后关系，将后面出现的节点（假设为n）的链域连到先出现的节点（假设为m），将原n节点的
后续节点搬迁到原单链表的头部，形成以下双头相交链表（如果使用带头结点的链表，搬迁过程中请自行额外增加一
个头节点）；
 

2.利用课程ppt中关于判断链表是否有环的方法，判断链表是否有环路，并求出环路出现的位置，即m，n节点的指针，请使用环路判断函数（输入为链表头指针），不可直接查找m,n，支持使用2个不同的链表头部指针进行查询；

3.将环路链接取消，恢复成单链表，并根据表头指针（输入）求解链表的中间节点（输出中间节点的值并返回指针），注意：不要将链表转换成数组来求解；

4.编写函数，判断两个链表是否相交，函数输入为双头相交链表的两个头指针并输出相交的指针，如没有相交则返回NULL。注意：判断相交是基于指针的比较（判断是否有相同的节点指针出现在两个链表中）而不是节点的值的比较。