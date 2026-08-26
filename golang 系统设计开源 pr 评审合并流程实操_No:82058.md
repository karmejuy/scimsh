最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计开源 pr 评审合并流程实操
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.24ogeb.asia/arts/928365.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.24ogeb.asia/arts/000323.Doc

原标题：golang 系统设计分布式锁不同场景选型对比
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.24ogeb.asia/arts/562910.Doc

原标题：golang es 分词器选型业务适配
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.24ogeb.asia/arts/148217.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.24ogeb.asia/arts/078697.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.24ogeb.asia/arts/387924.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://wiki.24ogeb.asia/arts/631026.Doc

原标题：分页逻辑错误数据漏查修复
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.24ogeb.asia/arts/697642.Doc

原标题：文件分片上传断点续传功能
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.24ogeb.asia/arts/464621.Doc

原标题：开源实践：维护开源项目Issue管理经验总结
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.24ogeb.asia/arts/853146.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.24ogeb.asia/arts/307980.Doc

原标题：golang k8s 镜像拉取密钥配置
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.24ogeb.asia/arts/825692.Doc

原标题：安全笔记：文件下载接口路径校验安全
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.24ogeb.asia/arts/096103.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.24ogeb.asia/arts/178687.Doc

原标题：项目实践：MySQL读写分离本地模拟实践
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.24ogeb.asia/arts/380928.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.24ogeb.asia/arts/748356.Doc

原标题：golang 系统设计限流服务架构讲解
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.24ogeb.asia/arts/077679.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.24ogeb.asia/arts/574222.Doc

原标题：golang gorm 批量插入性能调优
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.24ogeb.asia/arts/371099.Doc

原标题：Debug：序列化反序列化版本不一致解析失败
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.24ogeb.asia/arts/892403.Doc

原标题：安全组端口开放网络访问
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.24ogeb.asia/arts/838110.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.24ogeb.asia/arts/044629.Doc

原标题：项目实践：本地模拟多节点分布式系统实践
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.24ogeb.asia/arts/678150.Doc

原标题：golang 数据库批量更新性能优化
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.24ogeb.asia/arts/592403.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.24ogeb.asia/arts/784586.Doc

原标题：golang traceId spanId 传递方案
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.24ogeb.asia/arts/748305.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.24ogeb.asia/arts/935416.Doc

原标题：golang redis 缓存更新策略讲解
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.24ogeb.asia/arts/486219.Doc

原标题：分页逻辑错误数据漏查修复
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.24ogeb.asia/arts/314689.Doc

原标题：RPC 接口字段增减兼容处理
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.24ogeb.asia/arts/636832.Doc

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.24ogeb.asia/arts/153923.Doc

原标题：开发复盘：统一错误码体系设计落地实践
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.24ogeb.asia/arts/419846.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.24ogeb.asia/arts/833690.Doc

原标题：全局异常处理器接口返回统一
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.24ogeb.asia/arts/647923.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.24ogeb.asia/arts/563668.Doc

原标题：golang k8s 资源请求限制配置
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.24ogeb.asia/arts/589212.Doc

原标题：golang redis 发布订阅简单示例
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.24ogeb.asia/arts/042727.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.24ogeb.asia/arts/571929.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.24ogeb.asia/arts/803856.Doc

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.24ogeb.asia/arts/741996.Doc


二、踩坑排错｜Troubleshooting
原标题：设计思考：分布式会话架构选型对比
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.24ogeb.asia/arts/644536.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.24ogeb.asia/arts/502358.Doc

原标题：入门实践：简单错误码设计与使用规范
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.24ogeb.asia/arts/151351.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.24ogeb.asia/arts/237336.Doc

原标题：Practice：实现跨机器文件同步脚本实践
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.24ogeb.asia/arts/919258.Doc

原标题：nodejs 跨域中间件配置细节
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.24ogeb.asia/arts/331866.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.24ogeb.asia/arts/785800.Doc

原标题：golang 系统设计日志采样降低存储开销方案
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://wiki.24ogeb.asia/arts/482152.Doc

原标题：手写简易 ORM 理解对象映射
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.24ogeb.asia/arts/536984.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.24ogeb.asia/arts/781246.Doc

原标题：golang mock 单元测试编写技巧
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.24ogeb.asia/arts/803447.Doc

原标题：golang 系统设计 json 解析性能优化实操
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.24ogeb.asia/arts/482003.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.24ogeb.asia/arts/222066.Doc

原标题：nodejs 全局异常捕获进程防护
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.24ogeb.asia/arts/066572.Doc

原标题：调优方案：Nginx性能参数调优高并发配置
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.24ogeb.asia/arts/671188.Doc

原标题：golang redis 事务 multi exec 使用
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.24ogeb.asia/arts/330579.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.24ogeb.asia/arts/904664.Doc

原标题：nodejs 中间件模式原理剖析
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.24ogeb.asia/arts/441363.Doc

原标题：运维笔记：服务器故障排查常用命令清单
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.24ogeb.asia/arts/182246.Doc

原标题：新手教程：如何给开源项目提交第一个PR
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.24ogeb.asia/arts/745586.Doc

原标题：开发复盘：统一错误码体系设计落地实践
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.24ogeb.asia/arts/959620.Doc

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://wiki.24ogeb.asia/arts/549188.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.24ogeb.asia/arts/161331.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.24ogeb.asia/arts/485132.Doc

原标题：golang k8s liveness readiness 探针
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.24ogeb.asia/arts/180658.Doc

原标题：安全复盘：业务登录暴力破解防护完整方案
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.24ogeb.asia/arts/375618.Doc

原标题：前端权限路由动态生成实现
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.24ogeb.asia/arts/488229.Doc

原标题：golang 接口限流中间件开发
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.24ogeb.asia/arts/304955.Doc

原标题：golang docker 镜像构建最佳实践
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://wiki.24ogeb.asia/arts/927757.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.24ogeb.asia/arts/152098.Doc

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.24ogeb.asia/arts/125433.Doc

原标题：golang etcd 分布式锁实现原理
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.24ogeb.asia/arts/592703.Doc

原标题：golang websocket 消息广播实现
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.24ogeb.asia/arts/858592.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.24ogeb.asia/arts/721154.Doc

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.24ogeb.asia/arts/892062.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.24ogeb.asia/arts/342717.Doc

原标题：特殊输入字符过滤解析防护
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.24ogeb.asia/arts/263209.Doc

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.24ogeb.asia/arts/968444.Doc

原标题：实践：多配置文件合并加载组件实现
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.24ogeb.asia/arts/556841.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.24ogeb.asia/arts/631993.Doc

三、实战开发｜Practice
原标题：golang 系统设计 vscode go 插件调试配置实操
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.24ogeb.asia/arts/959873.Doc

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.24ogeb.asia/arts/641799.Doc

原标题：开发记录：分布式锁超时业务安全处理实践
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.24ogeb.asia/arts/343412.Doc

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.24ogeb.asia/arts/599815.Doc

原标题：服务器时钟同步任务错乱修复
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.24ogeb.asia/arts/906846.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.24ogeb.asia/arts/789553.Doc

原标题：架构笔记：海量日志处理架构选型与实践
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.24ogeb.asia/arts/014065.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.24ogeb.asia/arts/789039.Doc

原标题：golang 系统设计定时任务调度时间校准要点
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.24ogeb.asia/arts/751491.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.24ogeb.asia/arts/121486.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.24ogeb.asia/arts/428973.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.24ogeb.asia/arts/225677.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.24ogeb.asia/arts/001152.Doc

原标题：golang pprof 线上采集性能数据
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.24ogeb.asia/arts/222402.Doc

原标题：Practice：实现IP黑名单拦截中间件实践
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.24ogeb.asia/arts/658422.Doc

原标题：golang mysql 长连接短连接对比
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.24ogeb.asia/arts/744055.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.24ogeb.asia/arts/378758.Doc

原标题：golang lru 缓存淘汰算法编写
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.24ogeb.asia/arts/230324.Doc

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.24ogeb.asia/arts/307781.Doc

原标题：vite 插件开发自定义构建逻辑
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.24ogeb.asia/arts/760693.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.24ogeb.asia/arts/573331.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.24ogeb.asia/arts/962183.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.24ogeb.asia/arts/154238.Doc

原标题：文件分片上传断点续传功能
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.24ogeb.asia/arts/330383.Doc

原标题：golang redis 网络超时参数调优
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.24ogeb.asia/arts/704004.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.24ogeb.asia/arts/721728.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://wiki.24ogeb.asia/arts/881476.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.24ogeb.asia/arts/719317.Doc

原标题：开发记录：分布式锁超时业务安全处理实践
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.24ogeb.asia/arts/891779.Doc

原标题：设计思考：系统限流熔断降级完整防护体系
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.24ogeb.asia/arts/695118.Doc

原标题：方案设计：多租户系统架构三种实现模式对比
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.24ogeb.asia/arts/905733.Doc

原标题：架构笔记：海量日志处理架构选型与实践
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.24ogeb.asia/arts/222409.Doc

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.24ogeb.asia/arts/775810.Doc

原标题：快速上手阅读开源项目源码的入门思路
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.24ogeb.asia/arts/976721.Doc

原标题：golang mysql 行锁表锁场景区分
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.24ogeb.asia/arts/375146.Doc

原标题：golang 参数校验业务接口处理
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.24ogeb.asia/arts/367089.Doc

原标题：golang 系统设计接口返回格式统一规范
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.24ogeb.asia/arts/330408.Doc

原标题：golang 优雅处理数据库事务
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.24ogeb.asia/arts/359499.Doc

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.24ogeb.asia/arts/394588.Doc

原标题：golang 系统设计分布式配置中心思路
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.24ogeb.asia/arts/232233.Doc

四、架构设计｜Architecture
原标题：golang docker 镜像体积优化技巧
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.24ogeb.asia/arts/173244.Doc

原标题：golang 系统设计数据库慢查询治理方案
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.24ogeb.asia/arts/298487.Doc

原标题：实践：静态站点自动化部署到GitHubPages
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.24ogeb.asia/arts/364472.Doc

原标题：golang 系统设计状态字段枚举约束设计思路
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.24ogeb.asia/arts/740094.Doc

原标题：前端 pdf 预览渲染方案对比
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.24ogeb.asia/arts/372170.Doc

原标题：golang 系统设计接口超时设计原则梳理
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.24ogeb.asia/arts/850093.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.24ogeb.asia/arts/339903.Doc

原标题：golang k8s secret 加密敏感信息
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.24ogeb.asia/arts/427896.Doc

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.24ogeb.asia/arts/145872.Doc

原标题：golang 系统设计服务优雅停机完整流程
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.24ogeb.asia/arts/257387.Doc

原标题：golang 布隆过滤器实现去重
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.24ogeb.asia/arts/853003.Doc

原标题：浏览器内存泄漏排查前端页面
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.24ogeb.asia/arts/283796.Doc

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.24ogeb.asia/arts/700281.Doc

原标题：多实例部署 Session 共享方案
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.24ogeb.asia/arts/400981.Doc

原标题：golang redis 缓存击穿防护实现
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.24ogeb.asia/arts/538112.Doc

原标题：Architecture：日志、监控、告警整套可观测架构
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.24ogeb.asia/arts/897276.Doc

原标题：项目实践：消息队列消息确认机制业务实践
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.24ogeb.asia/arts/441682.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.24ogeb.asia/arts/923654.Doc

?
