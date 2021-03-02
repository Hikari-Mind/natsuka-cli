# natsuka-cli的Java实现
<del>哈，好家伙，立flag，新建文件夹也是在开发了</del>
### 项目架构与实现方案
> 传统的`Maven`项目，使用`GraalVM`作为本地化虚拟机，使用`Picocli`构建cli项目

> [GraalVM](https://www.graalvm.org/)是一个通用的虚拟机，可以运行 JavaScript、Python、Ruby、R、基于 JVM 的语言（如 Java、Scala、Clojure、Kotlin）和基于 LLVM 的语言（如 C 和 C++）所编写的应用程序;它允许混合多种编程语言：程序中的一部分可能会使用 JavaScript、R、Python 或 Ruby 编写，这些组成部分可以通过 Java 进行调用，并且可以彼此共享数据;另一个特性是创建原生镜像的能力

> [Picocli](https://github.com/remkop/picocli)是一个现代库和框架，适用于在 JVM 上构建命令行应用