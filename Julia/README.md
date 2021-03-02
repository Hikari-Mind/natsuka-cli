# natsuka-cli的Julia实现
<del>哈，好家伙，立flag，新建文件夹也是在开发了</del>
### 项目架构与实现方案
> 目前Julia并没有合适的包用于构建cli应用(因为Julia自身使用REPL)但是有相应的库可以编译出高效的结果

> [SnoopCompile.jl](https://github.com/timholy/SnoopCompile.jl)可以用来自动产生precompile的指令，这样就可以把大部分实际上会用的函数给静态预编译出来

> [Fezzik](https://github.com/TsurHerman/Fezzik)它会运行一遍这些函数做trace，然后获得类型信息和预编译指令，能够编译出一个静态的链接库储存这些编译结果