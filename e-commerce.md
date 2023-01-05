![image-20221217232501562](电商.assets/image-20221217232501562.png)

![image-20221217231547614](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20221217231547614.png)



![image-20221217231645720](电商.assets/image-20221217231645720.png)

![image-20221217232409485](电商.assets/image-20221217232409485.png)

![image-20221217232521174](电商.assets/image-20221217232521174.png)

![image-20221217232911578](电商.assets/image-20221217232911578.png)

![image-20221217233222832](电商.assets/image-20221217233222832.png)

![image-20221217233424515](电商.assets/image-20221217233424515.png)

![image-20221217233509916](电商.assets/image-20221217233509916.png)









![image-20221217233731258](电商.assets/image-20221217233731258.png)



![image-20221217233906788](电商.assets/image-20221217233906788.png)

![image-20221217234241136](电商.assets/image-20221217234241136.png)



![image-20221217234503108](电商.assets/image-20221217234503108.png)

![image-20221217234846829](电商.assets/image-20221217234846829.png)















![image-20221217235344601](电商.assets/image-20221217235344601.png)

![image-20221218001403178](电商.assets/image-20221218001403178.png)

![image-20221218002255218](电商.assets/image-20221218002255218.png)





再hash法，就是如果某个[hash函数](https://www.zhihu.com/search?q=hash函数&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra={"sourceType"%3A"answer"%2C"sourceId"%3A2567533017})产生了冲突，再用另外一个hash进行计算，比如[布隆过滤器](https://www.zhihu.com/search?q=布隆过滤器&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra={"sourceType"%3A"answer"%2C"sourceId"%3A2567533017})就采用了这种方法。

[开放寻址法](https://www.zhihu.com/search?q=开放寻址法&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra={"sourceType"%3A"answer"%2C"sourceId"%3A2567533017})，就是直接从冲突的数组位置往下寻找一个空的数组下标进行数据存储，这个在ThreadLocal里面有使用到。

建立公共溢出区，也就是把存在冲突的key统一放在一个公共溢出区里面。



作者：跟着Mic学架构
链接：https://www.zhihu.com/question/344345276/answer/2567533017
来源：知乎
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。