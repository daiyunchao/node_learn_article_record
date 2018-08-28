# collection_of_technical-articles
感觉比较好的技术文章收藏
(持续更新...)

## 缓存

日期:2018年8月22日

彻底弄懂HTTP缓存机制及原理 https://www.cnblogs.com/chenqf/p/6386163.html (条理清晰,浅显易懂)

常见缓存分类 https://zhuanlan.zhihu.com/p/40222159(讲的内容还比较全面)

## NATS

日期:2018年8月23日

NATS官方文档: https://nats.io/documentation/

## Node的多线程多进程

日期:2018年8月24日

nodejs cluster模块分析 https://segmentfault.com/a/1190000011737574 (从代码层面讲的,比较全面,回到了一个问题,为什么多个work进程可以同时监听相同的端口号)

818 NodeJS的Cluster模块 https://www.jianshu.com/p/a1abf405edfc

使用 pm2 啟動 Node.js cluster 以提升效能 https://larrylu.blog/nodejs-pm2-cluster-455ffbd7671  (写的很简单,但pm2 去做cluster会方便很多,但使用pm2 启动同一套代码,监听不同的端口,在nginx上配置负载均衡效果应该是一样的,毕竟Cluster的目的是用多进程的方式去利用服务器的CPU,在pm2上启动多个进程感觉跟简单一些)

## Node断言

日期:2018年8月27日

【Node断言assert】https://blog.csdn.net/nextstand/article/details/77676634 (对基本断言的一些简单介绍)

测试框架 Mocha 实例教程 http://www.ruanyifeng.com/blog/2015/12/a-mocha-tutorial-of-examples.html (Mocha应该算最流行的单元测试框架了,使用chai断言库,阮大神写的很详细)

## Node Buffer

日期:2018年8月28日

深入浅出Node.js（六）：Buffer那些事儿 http://www.infoq.com/cn/articles/nodejs-about-buffer (朴灵的文章,提供了在fs.createReadStream有bufferSize的情况下,如何正确的读出中文)

Nodejs进阶：核心模块Buffer常用API使用总结 https://www.cnblogs.com/chyingp/p/nodejs-learning-buffer.html (常用的BufferAPI的一些说明)

NodeJS中被忽略的内存 https://segmentfault.com/a/1190000004934938 (内容基本和朴灵的深入浅出相同,其中说到Buffer的内存是不会被V8限制的,所以放到了Buffer这一节,当然文章中的其他部分,如内存限制和垃圾回收等也是干货满满)
