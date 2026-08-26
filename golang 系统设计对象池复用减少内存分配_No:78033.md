最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计对象池复用减少内存分配
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.2bhujh.asia/arts/799736.Doc

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.2bhujh.asia/arts/233969.Doc

原标题：golang 系统设计容量评估简单方法论
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.2bhujh.asia/arts/192786.Doc

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.2bhujh.asia/arts/808418.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.2bhujh.asia/arts/756779.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.2bhujh.asia/arts/235886.Doc

原标题：复盘总结：数据库迁移升级风险评估清单
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://wiki.2bhujh.asia/arts/530962.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.2bhujh.asia/arts/482114.Doc

原标题：golang md5 sha 加密工具实现
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.2bhujh.asia/arts/676513.Doc

原标题：golang mysql limit 大分页优化
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.2bhujh.asia/arts/686697.Doc

原标题：golang 数据库批量更新性能优化
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.2bhujh.asia/arts/937909.Doc

原标题：golang 系统设计分布式事务几种方案
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.2bhujh.asia/arts/710364.Doc

原标题：Performance：缓存策略优化，降低数据库压力
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.2bhujh.asia/arts/753499.Doc

原标题：无用对象回收抑制内存上涨
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.2bhujh.asia/arts/528315.Doc

原标题：ORM 隐式慢查询问题规避
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.2bhujh.asia/arts/377303.Doc

原标题：手写简易 MQ 理解消息存储消费
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.2bhujh.asia/arts/243780.Doc

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.2bhujh.asia/arts/595852.Doc

原标题：开发记录：跨域中间件完整配置与边界处理
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.2bhujh.asia/arts/334853.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.2bhujh.asia/arts/298022.Doc

原标题：golang 灰度权重流量分发简单实现
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.2bhujh.asia/arts/130447.Doc

原标题：从零搭建本地数据库开发环境
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.2bhujh.asia/arts/390811.Doc

原标题：业务错误码体系设计方案
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.2bhujh.asia/arts/590688.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.2bhujh.asia/arts/475551.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.2bhujh.asia/arts/284302.Doc

原标题：GET POST 接口请求参数处理
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.2bhujh.asia/arts/786076.Doc

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.2bhujh.asia/arts/085512.Doc

原标题：版本升级服务启动失败处理
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.2bhujh.asia/arts/057417.Doc

原标题：实战：搭建日志收集分析简易完整演示环境
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.2bhujh.asia/arts/823233.Doc

原标题：快速入门简单签名校验实现思路
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.2bhujh.asia/arts/752822.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.2bhujh.asia/arts/127911.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://wiki.2bhujh.asia/arts/110673.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.2bhujh.asia/arts/989607.Doc

原标题：golang websocket 服务端开发
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.2bhujh.asia/arts/466834.Doc

原标题：消息队列消费堆积扩容处理
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.2bhujh.asia/arts/855036.Doc

原标题：nodejs 进程间通信 IPC 实操
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.2bhujh.asia/arts/783554.Doc

原标题：golang 开发环境快速搭建指南
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.2bhujh.asia/arts/756151.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.2bhujh.asia/arts/768721.Doc

原标题：golang jwt 过期刷新 token 实现
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.2bhujh.asia/arts/159735.Doc

原标题：golang validator 自定义校验规则
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.2bhujh.asia/arts/649402.Doc

原标题：K8s 镜像拉取网络故障修复
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.2bhujh.asia/arts/895644.Doc


二、踩坑排错｜Troubleshooting
原标题：service‑worker 离线缓存实践
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.2bhujh.asia/arts/881712.Doc

原标题：入门实践：本地简单代理服务搭建
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.2bhujh.asia/arts/760253.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.2bhujh.asia/arts/528728.Doc

原标题：新手指南：看懂开源项目的Issue与PR
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.2bhujh.asia/arts/597580.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.2bhujh.asia/arts/596334.Doc

原标题：golang 系统设计故障演练简单思路
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.2bhujh.asia/arts/528456.Doc

原标题：golang 系统设计性能优化通用思路方法论
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.2bhujh.asia/arts/638671.Doc

原标题：Security：Docker镜像安全扫描漏洞修复
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.2bhujh.asia/arts/565965.Doc

原标题：实践：静态站点自动化部署到GitHubPages
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.2bhujh.asia/arts/809410.Doc

原标题：开发记录：容器日志标准输出采集实践方案
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.2bhujh.asia/arts/356505.Doc

原标题：golang ci 流水线单元测试集成测试
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.2bhujh.asia/arts/853491.Doc

原标题：golang redis 事务 multi exec 使用
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.2bhujh.asia/arts/072606.Doc

原标题：react 状态管理方案选型对比
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.2bhujh.asia/arts/672549.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.2bhujh.asia/arts/896978.Doc

原标题：golang 系统设计消息队列降级业务开关实现
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.2bhujh.asia/arts/605583.Doc

原标题：golang k8s ingress 路由域名转发
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.2bhujh.asia/arts/293871.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.2bhujh.asia/arts/356905.Doc

原标题：CI 流水线超时时间延长配置
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.2bhujh.asia/arts/450880.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.2bhujh.asia/arts/960541.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.2bhujh.asia/arts/969194.Doc

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.2bhujh.asia/arts/372018.Doc

原标题：GitHub Markdown 文档语法汇总
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.2bhujh.asia/arts/586887.Doc

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://wiki.2bhujh.asia/arts/520475.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.2bhujh.asia/arts/787828.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.2bhujh.asia/arts/181995.Doc

原标题：golang gin 静态资源访问配置
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.2bhujh.asia/arts/288976.Doc

原标题：golang 系统设计熔断降级架构讲解
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.2bhujh.asia/arts/694467.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.2bhujh.asia/arts/770119.Doc

原标题：YAML 配置文件语法快速上手
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.2bhujh.asia/arts/691480.Doc

原标题：运维笔记：系统内核参数调优生产服务器
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.2bhujh.asia/arts/475513.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.2bhujh.asia/arts/208044.Doc

原标题：react hooks 常见陷阱避坑指南
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.2bhujh.asia/arts/857064.Doc

原标题：nodejs 日志轮转生产环境配置
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.2bhujh.asia/arts/267978.Doc

原标题：golang 系统设计监控大盘故障快速定位思路
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.2bhujh.asia/arts/370211.Doc

原标题：手写简易 ORM 理解对象映射
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.2bhujh.asia/arts/861121.Doc

原标题：服务健康检查告警监控体系
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.2bhujh.asia/arts/932088.Doc

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.2bhujh.asia/arts/153503.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.2bhujh.asia/arts/505734.Doc

原标题：文件句柄耗尽资源泄露处理
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.2bhujh.asia/arts/641206.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.2bhujh.asia/arts/677742.Doc

三、实战开发｜Practice
原标题：超大数据集分页性能优化方案
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.2bhujh.asia/arts/644247.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://wiki.2bhujh.asia/arts/041194.Doc

原标题：golang k8s 镜像拉取密钥配置
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.2bhujh.asia/arts/496711.Doc

原标题：golang 系统设计高可用服务架构梳理
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.2bhujh.asia/arts/785868.Doc

原标题：nestjs 拦截器过滤器管道实战
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://wiki.2bhujh.asia/arts/966339.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.2bhujh.asia/arts/132430.Doc

原标题：Architecture：静态资源分发CDN整体架构思路
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.2bhujh.asia/arts/361915.Doc

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.2bhujh.asia/arts/184005.Doc

原标题：golang redis set 集合去重业务
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.2bhujh.asia/arts/771368.Doc

原标题：golang 系统设计压测指标确定与分析
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.2bhujh.asia/arts/888590.Doc

原标题：golang 日志 zap 结构化日志实践
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.2bhujh.asia/arts/596452.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.2bhujh.asia/arts/371068.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.2bhujh.asia/arts/523545.Doc

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.2bhujh.asia/arts/562265.Doc

原标题：golang mysql 连接泄漏检测方法
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.2bhujh.asia/arts/174023.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.2bhujh.asia/arts/811993.Doc

原标题：golang 重试退避机制代码实现
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.2bhujh.asia/arts/989025.Doc

原标题：项目语义化版本号规范管理
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.2bhujh.asia/arts/552891.Doc

原标题：Hands‑on：简易配置中心本地原型实现
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.2bhujh.asia/arts/710937.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://wiki.2bhujh.asia/arts/281165.Doc

原标题：golang mysql 避免 select * 查询
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.2bhujh.asia/arts/842764.Doc

原标题：语义化版本依赖管理防错乱
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.2bhujh.asia/arts/768682.Doc

原标题：CI 持续集成自动构建流程
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.2bhujh.asia/arts/156522.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.2bhujh.asia/arts/805201.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.2bhujh.asia/arts/382367.Doc

原标题：全局本地依赖隔离冲突规避
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.2bhujh.asia/arts/815224.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.2bhujh.asia/arts/260017.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.2bhujh.asia/arts/467556.Doc

原标题：避坑：版本升级之后项目直接无法启动
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.2bhujh.asia/arts/796729.Doc

原标题：文件分片上传断点续传功能
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.2bhujh.asia/arts/575755.Doc

原标题：JSON XML 数据解析处理示例
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.2bhujh.asia/arts/431362.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.2bhujh.asia/arts/804337.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.2bhujh.asia/arts/738590.Doc

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.2bhujh.asia/arts/972905.Doc

原标题：golang redis 热点 key 业务规避
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.2bhujh.asia/arts/206143.Doc

原标题：golang gitlab ci 配置自动构建镜像
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://wiki.2bhujh.asia/arts/526234.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.2bhujh.asia/arts/144075.Doc

原标题：golang redis pipeline 原子性说明
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.2bhujh.asia/arts/248914.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.2bhujh.asia/arts/011911.Doc

原标题：golang 系统设计定时任务分布式锁
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.2bhujh.asia/arts/214520.Doc

四、架构设计｜Architecture
原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.2bhujh.asia/arts/960426.Doc

原标题：业务幂等键设计防重复逻辑
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.2bhujh.asia/arts/191130.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://wiki.2bhujh.asia/arts/477407.Doc

原标题：复盘总结：系统压测报告模板与分析思路
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.2bhujh.asia/arts/492068.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.2bhujh.asia/arts/633871.Doc

原标题：RPC 报文大小上限调优大请求
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.2bhujh.asia/arts/269830.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.2bhujh.asia/arts/273742.Doc

原标题：JWT 令牌过期异常处理
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.2bhujh.asia/arts/669148.Doc

原标题：golang 系统设计定时任务分布式锁
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.2bhujh.asia/arts/637508.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.2bhujh.asia/arts/377323.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.2bhujh.asia/arts/434215.Doc

原标题：不必要字符转义关闭业务异常
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.2bhujh.asia/arts/063815.Doc

原标题：零基础理解前后端简单交互流程
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.2bhujh.asia/arts/555083.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.2bhujh.asia/arts/890692.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://wiki.2bhujh.asia/arts/911270.Doc

原标题：请求工具封装统一异常处理
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.2bhujh.asia/arts/409411.Doc

原标题：golang mongodb 文档结构设计原则
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.2bhujh.asia/arts/359432.Doc

原标题：DNS 解析异常第三方调用故障
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.2bhujh.asia/arts/576246.Doc

?
