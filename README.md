# DBProxyTree
DBProxy（Atlas）分库分表技术研究


![](https://i.imgur.com/CnVdtlO.png)

<pre>
   1）使用DBProxy之后，应用程序只需要在连接串中设置DBProxy的地址，不需要关注整个数据库集群的结点；
   2）DBProxy内部实现负载均衡，读写分离
</pre>

![](https://i.imgur.com/4SMImqo.png)

<pre>
DBProxy整体架构

</pre>