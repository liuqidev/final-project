# final-project
大数据系统基础最后的大作业

## 0. 关于本仓库
### 目的: 

1. 共享关于大数据系统大作业相关的各成员的学习成果, 阅读材料.
2. 了解项目进度和存在的问题, 提交大家各自的源程序, 并对队友的代码进行审核.
3. 学习如何进行代码管理和版本控制.
4. 尝试多人使用Git/GitHub来协同办公, 讨论和解决问题.



### 文件夹说明:

很抱歉, 这里我按照个人的习惯, 暂时将文件夹定义为以下几类, 尽量将资料什么的按照下面说明存在相应的位置

- data: 数据集就不需要传上来了, github有文件大小限制. 给个超链接或者下载的方式说明即可
- src: 源程序
- report: 最后要交的报告
- doc: 一些说明的东西, 比如大作业的要求, 老师的PPT等
- out: 结果输出, 比如可能的实验的结果等
- assets: 一些报告中所学要用到的插图, 截图(可以是图片也可以是pdf等格式)
- ref: 相关参考文献, 建议大家将自己看的与作业相关的阅读材料(一般存链接即可)保存在这个路径下, 什么博客上看的文章就也给个链接就行
- test: 测试的输出结果
- log: 可能的日志文件, 修改记录
- more: ...大家可以随意增加其他文件夹和文件, 最好将属于上面的存储到相应的位置
- readme.md: 说明文档, 在每个地方都可以放一个readme.md文档, 就像这个一样.



### 关于本仓库的使用:

一下内容是推荐学习的:

- markdown: 一种书写符号规范, 例如本文档是使用其语法规则书写的.
- git: 一种分布式文件管理工具和标准. 对于本项目不需要很深入了解.
- github: 一个应用了git的源代码托管网站, 世界最大的开源社区



### 工具:

推荐下载和使用下面的工具

- markdown编辑器: 推荐, 非必须. windows/linux下建议[Typora](https://typora.io/), Jupyter Notebook, 其余均不建议; Mac下, 同前面, 同时也有比较多的好用的编辑器.
- git: https://git-scm.com/, 推荐但非必需, 主要是用其中的git bash, 通过命令行进行操作. 本项目也可以不使用.
- github desktop: https://desktop.github.com/, 推荐但非必需, 主要是图像化操作在github上的一切. 

总的来说, 可以不需要使用任何额外的东西, 在github上可以完成一切操作.





### 从哪里开始?

| 准备工作流程                                                 |
| ------------------------------------------------------------ |
| 1. 其https://github.com使用邮箱注册一个github账号, 验证邮箱(这个环节可能有网络不畅缓冲不出来验证码的情况). |
| 2. 去https://github.com/dsjxtjc/final-project/tree/master, 点击右上角的fork, 将代码拷贝一份到你的账号下, 其实可以直接在主分支上修改, 但是不推荐. |
| ![](assets/fork.png)                                         |
| ![](assets/fork1.png)                                        |
| 3. 可以克隆一份到本地方便修改,  下载可以使用SSH, 使用方法和大数据系统基础上的用法一致, 需要下载前面所说的Git, 以及将生成SSH公钥复制到Github后台.也可以使用https方式和downloadzip方式, 就能下载zip包.![](assets/clone.png) |
| 4. , 在本地的修改, 可以进行git版本的控制(例如那次把代码改烂了, 可以回退到之前的任意版本), 也可以使用github desktop来实现. |
| 5. 将修改后的仓库上传到这GitHub上, 可以使用git , github desktop, 或者直接在github网站上采用可视化或拖拽方式进行. ![](assets/upload.png) |
| 6. 但你觉得自己的修改可能对整个系统有帮助, 可以使用pullrequest, 将自己的修改推到主分支上. |
| ![](assets/pullrequest.png)                                  |

主分支会审核提交者的代码, 但作为主分支所属组织的成员时, 也可以直接对主分支进行修改. 否则, 大家做的修改都是在各自分支上的. 由于git学习起来需要一些时间, 所以这里暂定采取上面这种分布式办公的方式. 能使用图像化操作就用简单的方式, 但是依然推荐使用github desktop 或者git bash.

关于更多详情, 我们多在微信群里讨论, 更推荐在主分支里使用issue进行讨论!![](assets/issue.png)



### 教程

先修知识学习教程:

markdown: 主要用于写文档, 例如写出本文档这种样子

- 简书教程: https://www.jianshu.com/p/q81RER

- typora教程, 下载typora后如下: 

![](assets/helpmd.png)



GitHub:

- https://lab.github.com/, github机器人手把手教学

- https://guides.github.com/activities/hello-world/, 官方简短的说明文档

Git:

- [廖雪峰的Git教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/) 

## 任务1: 方案选择

>
> 时间: 2018年12月6日周四下午五点
>
> 状态: 已完成

讨论方案
1. 现有分布式软件, 框架, 架构的研究和分析, 源码阅读理解
2. 大数据机器学习, 比赛
3. 某种分布式系统研究实现等
4. 流式处理计算框架研究和实现等

已有作业基础:
- Linux基础
- DFS, MP
- Spark

下一阶段任务:
- 熟悉理解Spark相关原理, 从而进一步讨论下一阶段任务, 技术路线, 分工等.

确定: 方案中的第3条



## 任务2: (进行中……) 分工, 技术路线

> 讨论时间: 2018年12月10日, 周一
>
> 地点: 待定
>
> 状态: 待定

