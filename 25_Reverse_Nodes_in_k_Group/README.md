# Reverse Nodes in k-Group

这道题是 Swap Nodes in Pairs的扩展，我的做法就是模拟一遍操作。

先从链表中找出长度为k的一段，然后将这一段链表反转，最后再拼接到一起

例如

    1->2->3->4->5->6

	当k为2时

	先遍历找出长度为2的子链表，1->2，3->4, 5->6

	再拼接 将 1->4,3->5（上一段的结尾连到当前的头）


