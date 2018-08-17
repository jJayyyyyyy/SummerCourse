##	2018.08.15晚19:00到22:00实验课内容

1.	使用汇编编写冒泡排序

	用户从键盘输入 0~9 的数字，然后对其进行冒泡排序

	注意: 目前只能输入个位数，如果输入 12，则会被理解为 1 和 2

	<br>

2.	思考

	在编写和调试的过程，我遇到了不少问题，这里拿出几个作为思考题，希望你有空的时候想想怎么做

	*	如何从小到大排序，如何从大到小排序

	*	这次试验中用到了栈，它的作用是什么，能否联想到中断过程

	*	汇编，输出单个字符的时候，'\r' = 13(ASCII), '\n' = 10(ASCII) 两个字符有何区别(carriage return 和 newline 的区别)

		如果把 L30 的 `mov dl, 10` 换成 `mov dl, 13` 会发生什么

	*	10个数的排序，为什么 L40 是 `mov cx, 9`

		如果不改变现在数据段中的内容，那么 `mov cx, 9` 与 `mov cx, 10` 的最终效果有区别吗？

		怎样修改数据段中的内容，才能显现出两条指令的区别(结合第三个思考题)

	<br>

*	个人建议: 如果用的是自己的电脑，建议在 sandboxie 等沙盒中进行实验