## #A题
水题，遇0+1，遇1-1，最后输出abs值就可以了
## #B题
这是一道判断题，我的方法就是找到每个数的增量和，然后奇数位加，偶数位减，然后每次改变最多改变当前量n的倍数之多，所以就判断一下mod n是不是0
就可以了。
## #C
俄罗斯套娃，贪心就可以了，找出一开始的最长连续序列，然后每找到一个ans-=2，意思是少了一次加入，少了一次拆分，最后手动减k，原代价是2*n-1
## #D
本题就是一个销售找时间问题的变种，我们直接用STL的优先队列存住包含该点的区间，然后如果top不在包含这个点说明无解。贪心题
## #E
这道题就是一个比较妙的思想，找离他最近的下一个一定不会错，如果该操作与其方向不一致，说明挡住了他的去路，否则他就能和上一个走到一样高。
然后就是L的情况要it--，因为方向是倒过来的

