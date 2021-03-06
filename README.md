
<p align="center">
  <a href="https://www.oracle.com/cn/java/technologies/javase/javase-jdk8-downloads.html">
    <img src="https://img.shields.io/badge/JDK-1.8.0__77-brightgreen" alt="JDK">
  </a>
  <a href="https://spring.io/">
    <img src="https://img.shields.io/badge/Spring-5.2.1.RELEASE-green" alt="Spring">
  </a>
  <a href="https://spring.io/projects/spring-boot">
    <img src="https://img.shields.io/badge/SpringBoot-2.2.1.RELEASE-yellowgreen" alt="SpringBoot">
  </a>
  <a href="https://spring.io/projects/spring-security">
    <img src="https://img.shields.io/badge/SpringSecurity-5.1.0.RELEASE-orange" alt="SpringSecurity">
  </a>
  <a href="https://spring.io/projects/spring-security-oauth">
    <img src="https://img.shields.io/badge/Spring--Security--OAuth2-2.3.5.RELEASE-red" alt="Spring-Security-OAuth2">
  </a>
  <a href="https://netty.io/">
    <img src="https://img.shields.io/badge/Netty-4-blue" alt="Netty">
  </a>
</p>

源码深入学习：Spring源码、SpringBoot源码、SpringAOP源码、SpringSecurity源码、OAuth2源码、JDK源码、Netty源码

Tip：
如果读者电脑无法浏览到github图片，则需要设置hosts配置文件, 解决办法：[解决GitHub网页githubusercontent地址无法访问问题
](https://zhuanlan.zhihu.com/p/107691233)

# 目录

-   项目导入
    将整个JavaSourceLearning导入IDEA中，然后选中项目pom.xml文件右键，open as maven project然后等待maven下载相应jar包即可。

-   JDK源码学习
    - JDK版本：1.8.0_77
    - [深入学习String源码与底层（一）](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/JDK/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0String%E6%BA%90%E7%A0%81%E4%B8%8E%E5%BA%95%E5%B1%82%EF%BC%88%E4%B8%80%EF%BC%89.md)
    - [深入学习String源码与底层（二）](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/JDK/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0String%E6%BA%90%E7%A0%81%E4%B8%8E%E5%BA%95%E5%B1%82%EF%BC%88%E4%BA%8C%EF%BC%89.md)
    - [深入解读CompletableFuture源码与原理](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/JDK/%E6%B7%B1%E5%85%A5%E8%A7%A3%E8%AF%BBCompletableFuture%E6%BA%90%E7%A0%81%E4%B8%8E%E5%8E%9F%E7%90%86.md)
    - [一篇文章快速深入学习ThreadLocal](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/JDK/%E4%B8%80%E7%AF%87%E6%96%87%E7%AB%A0%E5%BF%AB%E9%80%9F%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0ThreadLocal.md)
    - [深入学习Java volatile关键字](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/JDK/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0Java%20volatile%E5%85%B3%E9%94%AE%E5%AD%97.md)

-   Spring源码学习
    - Spring版本：5.2.1.RELEASE
    
    - [深入Spring源码系列（一）——在IDEA中构建Spring源码](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/Spring/%E6%B7%B1%E5%85%A5Spring%E6%BA%90%E7%A0%81%E7%B3%BB%E5%88%97%EF%BC%88%E4%B8%80%EF%BC%89%E2%80%94%E2%80%94%E5%9C%A8IDEA%E4%B8%AD%E6%9E%84%E5%BB%BASpring%E6%BA%90%E7%A0%81.md)
    - [深入Spring源码系列（二）——深入Spring容器，通过源码阅读和时序图来彻底弄懂Spring容器（上）](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/Spring/%E6%B7%B1%E5%85%A5Spring%E6%BA%90%E7%A0%81%E7%B3%BB%E5%88%97%EF%BC%88%E4%BA%8C%EF%BC%89%E2%80%94%E2%80%94%E6%B7%B1%E5%85%A5Spring%E5%AE%B9%E5%99%A8%EF%BC%8C%E9%80%9A%E8%BF%87%E6%BA%90%E7%A0%81%E9%98%85%E8%AF%BB%E5%92%8C%E6%97%B6%E5%BA%8F%E5%9B%BE%E6%9D%A5%E5%BD%BB%E5%BA%95%E5%BC%84%E6%87%82Spring%E5%AE%B9%E5%99%A8%EF%BC%88%E4%B8%8A%EF%BC%89.md)
    - [深入Spring源码系列（二）——深入Spring容器，通过源码阅读和时序图来彻底弄懂Spring容器（下）](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/Spring/%E6%B7%B1%E5%85%A5Spring%E6%BA%90%E7%A0%81%E7%B3%BB%E5%88%97%EF%BC%88%E4%BA%8C%EF%BC%89%E2%80%94%E2%80%94%E6%B7%B1%E5%85%A5Spring%E5%AE%B9%E5%99%A8%EF%BC%8C%E9%80%9A%E8%BF%87%E6%BA%90%E7%A0%81%E9%98%85%E8%AF%BB%E5%92%8C%E6%97%B6%E5%BA%8F%E5%9B%BE%E6%9D%A5%E5%BD%BB%E5%BA%95%E5%BC%84%E6%87%82Spring%E5%AE%B9%E5%99%A8%EF%BC%88%E4%B8%8B%EF%BC%89.md)
    - [深入Spring源码系列（补充篇）——程序调用Spring源码](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/Spring/%E6%B7%B1%E5%85%A5Spring%E6%BA%90%E7%A0%81%E7%B3%BB%E5%88%97%EF%BC%88%E8%A1%A5%E5%85%85%E7%AF%87%EF%BC%89%E2%80%94%E2%80%94%E7%A8%8B%E5%BA%8F%E8%B0%83%E7%94%A8Spring%E6%BA%90%E7%A0%81.md)
    - [从Spring源码中学习——策略模式](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/Spring/%E4%BB%8ESpring%E6%BA%90%E7%A0%81%E4%B8%AD%E5%AD%A6%E4%B9%A0%E2%80%94%E2%80%94%E7%AD%96%E7%95%A5%E6%A8%A1%E5%BC%8F.md)

-   SpringAOP源码学习
    - Spring版本：5.2.1.RELEASE 
    
    - [深入学习SpringAOP源码（一）——注册AnnotationAwareAspectJAutoProxyCreator](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/SpringAOP/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0SpringAOP%E6%BA%90%E7%A0%81%EF%BC%88%E4%B8%80%EF%BC%89%E2%80%94%E2%80%94%E6%B3%A8%E5%86%8CAnnotationAwareAspectJAutoProxyCreator.md) 
    - [深入学习SpringAOP源码（二）—— 深入AnnotationAwareAspectJAutoProxyCreator](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/SpringAOP/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0SpringAOP%E6%BA%90%E7%A0%81%EF%BC%88%E4%BA%8C%EF%BC%89%E2%80%94%E2%80%94%20%E6%B7%B1%E5%85%A5AnnotationAwareAspectJAutoProxyCreator.md)
    - [深入学习SpringAOP源码（三）——揭开JDK动态代理和CGLIB代理的神秘面纱](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/SpringAOP/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0SpringAOP%E6%BA%90%E7%A0%81%EF%BC%88%E4%B8%89%EF%BC%89%E2%80%94%E2%80%94%E6%8F%AD%E5%BC%80JDK%E5%8A%A8%E6%80%81%E4%BB%A3%E7%90%86%E5%92%8CCGLIB%E4%BB%A3%E7%90%86%E7%9A%84%E7%A5%9E%E7%A7%98%E9%9D%A2%E7%BA%B1.md)
        
-   SpringBoot源码学习
    - SpringBoot版本：2.2.1.RELEASE
    
    - [深入SpringBoot源码学习之——SpringFactoriesLoader](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/SpringBoot/%E6%B7%B1%E5%85%A5SpringBoot%E6%BA%90%E7%A0%81%E5%AD%A6%E4%B9%A0%E4%B9%8B%E2%80%94%E2%80%94SpringFactoriesLoader.md) 
    - [深入SpringBoot源码学习之——监听器与事件机制](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/SpringBoot/%E6%B7%B1%E5%85%A5SpringBoot%E6%BA%90%E7%A0%81%E5%AD%A6%E4%B9%A0%E4%B9%8B%E2%80%94%E2%80%94%E7%9B%91%E5%90%AC%E5%99%A8%E4%B8%8E%E4%BA%8B%E4%BB%B6%E6%9C%BA%E5%88%B6.md)
    - [深入SpringBoot源码学习之——系统初始化器](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/SpringBoot/%E6%B7%B1%E5%85%A5SpringBoot%E6%BA%90%E7%A0%81%E5%AD%A6%E4%B9%A0%E4%B9%8B%E2%80%94%E2%80%94%E7%B3%BB%E7%BB%9F.md)
    

-   Netty源码学习
    - [二进制运算以及源码、反码以及补码学习](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/Netty/%E4%BA%8C%E8%BF%9B%E5%88%B6.md) 
    - [Netty源码包结构](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/Netty/Netty%E6%BA%90%E7%A0%81%E5%8C%85%E7%BB%93%E6%9E%84.md)
    - [Netty中的EventLoopGroup](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/Netty/Netty%E4%B8%AD%E7%9A%84EventLoopGroup%E6%98%AF%E4%BB%80%E4%B9%88.md)
    
-   SpringSecurity&OAuth2源码学习
    - SpringSecurity版本：5.1.0.RELEASE
    - [从零开始系统学习SpringSecurity和OAuth2（一）—— 初识SpringSecurity](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/SpringSecurity/%E4%BB%8E%E9%9B%B6%E5%BC%80%E5%A7%8B%E7%B3%BB%E7%BB%9F%E5%AD%A6%E4%B9%A0SpringSecurity%E5%92%8COAuth2%EF%BC%88%E4%B8%80%EF%BC%89%E2%80%94%E2%80%94%20%E5%88%9D%E8%AF%86SpringSecurity.md)   
    - [从零开始系统学习SpringSecurity和OAuth2（二）—— 安全过滤器FilterChainProxy](https://github.com/coderbruis/JavaSourceLearning/blob/master/note/SpringSecurity/%E4%BB%8E%E9%9B%B6%E5%BC%80%E5%A7%8B%E7%B3%BB%E7%BB%9F%E5%AD%A6%E4%B9%A0SpringSecurity%E5%92%8COAuth2%EF%BC%88%E4%BA%8C%EF%BC%89%E2%80%94%E2%80%94%20%E5%AE%89%E5%85%A8%E8%BF%87%E6%BB%A4%E5%99%A8FilterChainProxy.md)
    
  持续更新中...
    
    
# 支持

  开源不易，各位帅哥美女们star支持一下....


