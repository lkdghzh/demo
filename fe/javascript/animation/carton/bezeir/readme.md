# bezeir曲线的几个维度
- 线的个数 辅助线的个数
<pre>
    n个节点(n>2)，
    总线数：(n-1)+(n-2)+...+1，公差为1等差数列求和，S=（1+n-1）*（n-1）/2=n*(n-1)/2
    中间辅助线（包含最后一条）：n*(n-1)/2-(n-1)

    假如：2个节点，总1条 0辅助
    假如：3个节点，总3条 1辅助
    假如：4个节点，总6条 3辅助
    假如：5个节点，总10条 6辅助
</pre>
    
- 自变量的范围
<pre>
    不论几次贝塞尔，t从0->1[0,1],这个过程：
    假如：描了100个点，就是把范围1分成100份 ，每份0.01
    假如：描了1000个点，就是把范围1分成100份 ，每份0.001
</pre>

<img src="https://github.com/lkdghzh/blog/blob/master/fe/blog-assets/bezier-simple.gif"/>
<img src="https://github.com/lkdghzh/blog/blob/master/fe/blog-assets/besier-multi.gif"/>