# InfiniteScroller
简单实现图片循环滚动

##思路
视图的排列按1+N+1来，最后的一张放在1位置，第一张放在N+1位置，初始化时设置ContentOffSet在第一张位置。
当滑动停止时判断偏移位置，再来重置ContentOffSet的位置。比如当N张到N+1时设置回到第一张，向反方向滑到1时设置回第N张。