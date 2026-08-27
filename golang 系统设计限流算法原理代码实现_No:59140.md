最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计限流算法原理代码实现
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.lywfgk.asia/blog/4776737.sHtMl

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://book.lywfgk.asia/blog/8670701.sHtMl

原标题：nodejs http 服务性能调优实战
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://book.lywfgk.asia/blog/9257747.sHtMl

原标题：golang 单元测试 table‑driven
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://book.lywfgk.asia/blog/2360949.sHtMl

原标题：开发生产环境资源路径统一
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://book.lywfgk.asia/blog/3824176.sHtMl

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://book.lywfgk.asia/blog/0947813.sHtMl

原标题：golang gorm 预加载关联查询优化
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.lywfgk.asia/blog/1768099.sHtMl

原标题：golang 系统设计数据库慢请求排查流程
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.lywfgk.asia/blog/4809129.sHtMl

原标题：灰度发布策略服务平滑升级
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://book.lywfgk.asia/blog/7805024.sHtMl

原标题：CI 流水线构建失败日志排查
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://book.lywfgk.asia/blog/8721860.sHtMl

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.lywfgk.asia/blog/0969005.sHtMl

原标题：golang 系统设计代码仓库权限管理方案
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.lywfgk.asia/blog/8974106.sHtMl

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://book.lywfgk.asia/blog/7544596.sHtMl

原标题：golang redis 缓存预热实现思路
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://book.lywfgk.asia/blog/0560897.sHtMl

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://book.lywfgk.asia/blog/8687334.sHtMl

原标题：golang 链路 traceId 透传中间件
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.lywfgk.asia/blog/7240445.sHtMl

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://book.lywfgk.asia/blog/6434820.sHtMl

原标题：OOMKilled 容器被杀完整排查
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://book.lywfgk.asia/blog/6586390.sHtMl

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.lywfgk.asia/blog/3332120.sHtMl

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://book.lywfgk.asia/blog/9211047.sHtMl

原标题：golang toml 配置文件解析教程
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.lywfgk.asia/blog/2280004.sHtMl

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://book.lywfgk.asia/blog/8924534.sHtMl

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.lywfgk.asia/blog/4190838.sHtMl

原标题：Performance：后端接口性能优化完整分析流程
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.lywfgk.asia/blog/5236572.sHtMl

原标题：golang 系统设计技术方案评审关注点清单参考
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://book.lywfgk.asia/blog/3449542.sHtMl

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://book.lywfgk.asia/blog/1505151.sHtMl

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://book.lywfgk.asia/blog/2601696.sHtMl

原标题：golang 系统设计 api 网关核心能力完整梳理
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://book.lywfgk.asia/blog/1275029.sHtMl

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://book.lywfgk.asia/blog/7503317.sHtMl

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://book.lywfgk.asia/blog/9025018.sHtMl

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.lywfgk.asia/blog/5385158.sHtMl

原标题：安全复盘：日志打印敏感信息泄露治理
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://book.lywfgk.asia/blog/3144943.sHtMl

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.lywfgk.asia/blog/0099755.sHtMl

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.lywfgk.asia/blog/8874716.sHtMl

原标题：golang mysql 防止 sql 注入实践
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.lywfgk.asia/blog/4590619.sHtMl

原标题：golang http client 连接池调优
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://book.lywfgk.asia/blog/0832783.sHtMl

原标题：数据库分表存储大表优化方案
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.lywfgk.asia/blog/5545233.sHtMl

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://book.lywfgk.asia/blog/6497955.sHtMl

原标题：Hands‑on：简易事件驱动架构原型开发
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://book.lywfgk.asia/blog/5967015.sHtMl

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://book.lywfgk.asia/blog/9735896.sHtMl


二、踩坑排错｜Troubleshooting
原标题：Security：接口鉴权越权漏洞检测与修复
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://book.lywfgk.asia/blog/1313900.sHtMl

原标题：5分钟快速搭建个人技术文档站点
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.lywfgk.asia/blog/5423891.sHtMl

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://book.lywfgk.asia/blog/9393609.sHtMl

原标题：文件锁正确使用避免死锁
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://book.lywfgk.asia/blog/9479123.sHtMl

原标题：GitHub Markdown 文档语法汇总
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://book.lywfgk.asia/blog/9423388.sHtMl

原标题：golang 系统设计线程协程泄露定位方法
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.lywfgk.asia/blog/9544555.sHtMl

原标题：跨平台 uniapp 多端开发实操
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://book.lywfgk.asia/blog/3458552.sHtMl

原标题：轻量 API 后端接口服务快速开发
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.lywfgk.asia/blog/8514774.sHtMl

原标题：golang prometheus histogram 指标
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://book.lywfgk.asia/blog/1905501.sHtMl

原标题：内存广播本地进程消息通知
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.lywfgk.asia/blog/3783133.sHtMl

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.lywfgk.asia/blog/0098165.sHtMl

原标题：golang 静态编译缩小镜像体积
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.lywfgk.asia/blog/2971595.sHtMl

原标题：OpenAPI 自动接口文档生成
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://book.lywfgk.asia/blog/3488530.sHtMl

原标题：golang redis 大 key 识别处理方案
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://book.lywfgk.asia/blog/2655577.sHtMl

原标题：golang 系统设计接口防刷 ip 限流实现
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://book.lywfgk.asia/blog/6703325.sHtMl

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://book.lywfgk.asia/blog/5098198.sHtMl

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.lywfgk.asia/blog/5592247.sHtMl

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.lywfgk.asia/blog/5396204.sHtMl

原标题：golang 系统设计混沌测试故障注入简单示例
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://book.lywfgk.asia/blog/6732877.sHtMl

原标题：GET POST 接口请求参数处理
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://book.lywfgk.asia/blog/8501617.sHtMl

原标题：端口占用访问失败排查方案
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.lywfgk.asia/blog/4386092.sHtMl

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://book.lywfgk.asia/blog/1168697.sHtMl

原标题：Git 误提交撤销回退实操教程
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.lywfgk.asia/blog/0858655.sHtMl

原标题：golang k8s devops 流水线简单思路
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://book.lywfgk.asia/blog/2180619.sHtMl

原标题：CORS 跨域问题多种解决方案
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://book.lywfgk.asia/blog/2653423.sHtMl

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://book.lywfgk.asia/blog/5372457.sHtMl

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://book.lywfgk.asia/blog/0333200.sHtMl

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://book.lywfgk.asia/blog/6711025.sHtMl

原标题：安全实践：防止重放攻击接口签名方案
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.lywfgk.asia/blog/0835062.sHtMl

原标题：golang 系统设计短信发送限流降级
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.lywfgk.asia/blog/4874618.sHtMl

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://book.lywfgk.asia/blog/8836241.sHtMl

原标题：DevOps：GitLabCI完整流水线配置示例
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://book.lywfgk.asia/blog/7869195.sHtMl

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://book.lywfgk.asia/blog/8457315.sHtMl

原标题：Issue：本地可以访问，容器内部网络不通
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://book.lywfgk.asia/blog/2840329.sHtMl

原标题：复盘总结：数据库迁移升级风险评估清单
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.lywfgk.asia/blog/3191636.sHtMl

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://book.lywfgk.asia/blog/1430630.sHtMl

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://book.lywfgk.asia/blog/0134469.sHtMl

原标题：golang lru 缓存淘汰算法编写
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://book.lywfgk.asia/blog/2316585.sHtMl

原标题：部署实践：数据库迁移脚本版本管理实践
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.lywfgk.asia/blog/9463332.sHtMl

原标题：golang k8s devops 流水线简单思路
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://book.lywfgk.asia/blog/0511617.sHtMl

三、实战开发｜Practice
原标题：golang mysql 行锁表锁场景区分
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.lywfgk.asia/blog/6926012.sHtMl

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.lywfgk.asia/blog/3784772.sHtMl

原标题：golang k8s 镜像拉取密钥配置
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://book.lywfgk.asia/blog/5314690.sHtMl

原标题：golang 系统设计内网外网服务隔离方案
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.lywfgk.asia/blog/5011991.sHtMl

原标题：HTTPS 证书过期更新操作
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://book.lywfgk.asia/blog/6176696.sHtMl

原标题：nodejs 跨域中间件配置细节
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://book.lywfgk.asia/blog/5531717.sHtMl

原标题：css 动画性能优化 GPU 加速
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.lywfgk.asia/blog/1343163.sHtMl

原标题：golang 系统设计第三方接口调用封装思路
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://book.lywfgk.asia/blog/0167500.sHtMl

原标题：开源实践：维护开源项目Issue管理经验总结
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.lywfgk.asia/blog/5763359.sHtMl

原标题：golang 系统设计容量评估简单方法论
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://book.lywfgk.asia/blog/5068071.sHtMl

原标题：踩坑：大事务引发数据库连接池耗尽
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://book.lywfgk.asia/blog/0168970.sHtMl

原标题：Hands‑on：简易反向代理中间件实现
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.lywfgk.asia/blog/0442980.sHtMl

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://book.lywfgk.asia/blog/5315852.sHtMl

原标题：编译打包产物依赖分析解读
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://book.lywfgk.asia/blog/3170385.sHtMl

原标题：部署复盘：数据库主从备份恢复演练实践
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://book.lywfgk.asia/blog/6746907.sHtMl

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://book.lywfgk.asia/blog/9427672.sHtMl

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://book.lywfgk.asia/blog/3499723.sHtMl

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://book.lywfgk.asia/blog/2249923.sHtMl

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.lywfgk.asia/blog/8514384.sHtMl

原标题：新手向：开源项目依赖安装失败排查
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://book.lywfgk.asia/blog/1561447.sHtMl

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.lywfgk.asia/blog/7193388.sHtMl

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.lywfgk.asia/blog/0592245.sHtMl

原标题：golang es 查询语句 DSL 实操
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://book.lywfgk.asia/blog/7191420.sHtMl

原标题：golang 系统设计用户签到统计方案
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://book.lywfgk.asia/blog/9046263.sHtMl

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.lywfgk.asia/blog/0587806.sHtMl

原标题：移动端适配 rem vw 方案对比
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://book.lywfgk.asia/blog/5070266.sHtMl

原标题：golang 项目 makefile 脚本编写
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.lywfgk.asia/blog/8324945.sHtMl

原标题：前端权限路由动态生成实现
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://book.lywfgk.asia/blog/3868182.sHtMl

原标题：golang kafka 消息丢失重复消费
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.lywfgk.asia/blog/0739461.sHtMl

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://book.lywfgk.asia/blog/7855092.sHtMl

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://book.lywfgk.asia/blog/1086860.sHtMl

原标题：golang docker compose 部署 minio
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.lywfgk.asia/blog/1866230.sHtMl

原标题：运维笔记：线上服务健康检查脚本编写
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://book.lywfgk.asia/blog/8754005.sHtMl

原标题：golang 布隆过滤器实现去重
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://book.lywfgk.asia/blog/7233725.sHtMl

原标题：Practice：实现限流之后友好业务返回处理
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://book.lywfgk.asia/blog/3746003.sHtMl

原标题：CI 持续集成自动构建流程
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://book.lywfgk.asia/blog/1906873.sHtMl

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.lywfgk.asia/blog/9376704.sHtMl

原标题：golang 系统设计消息队列降级业务开关实现
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.lywfgk.asia/blog/9871203.sHtMl

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.lywfgk.asia/blog/1304301.sHtMl

原标题：安全笔记：GitHubAction密钥安全管理
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://book.lywfgk.asia/blog/5747382.sHtMl

四、架构设计｜Architecture
原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.lywfgk.asia/blog/8675860.sHtMl

原标题：golang 系统设计索引设计通用方法论汇总
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://book.lywfgk.asia/blog/6922577.sHtMl

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.lywfgk.asia/blog/6092205.sHtMl

原标题：安全复盘：Redis命令注入风险防护手段
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://book.lywfgk.asia/blog/7272315.sHtMl

原标题：内存溢出问题现象识别排查
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.lywfgk.asia/blog/4383428.sHtMl

原标题：新手指南：读懂项目构建脚本作用
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://book.lywfgk.asia/blog/5516112.sHtMl

原标题：golang redis 过期策略内存淘汰
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.lywfgk.asia/blog/1678730.sHtMl

原标题：golang dockerfile 多阶段构建详解
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://book.lywfgk.asia/blog/7104844.sHtMl

原标题：线上接口超时故障排查思路
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.lywfgk.asia/blog/2394328.sHtMl

原标题：golang 系统设计缓存预热缓存降级实现
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://book.lywfgk.asia/blog/8491096.sHtMl

原标题：项目实践：MySQL读写分离本地模拟实践
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://book.lywfgk.asia/blog/1612999.sHtMl

原标题：golang 系统设计定时任务分布式锁
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://book.lywfgk.asia/blog/6339775.sHtMl

原标题：不必要字符转义关闭业务异常
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.lywfgk.asia/blog/0783893.sHtMl

原标题：golang 优雅处理 http 超时设置
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.lywfgk.asia/blog/1608862.sHtMl

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.lywfgk.asia/blog/7991458.sHtMl

原标题：golang ci 流水线代码质量扫描集成
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://book.lywfgk.asia/blog/7556664.sHtMl

原标题：golang 系统设计对象池复用减少内存分配
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://book.lywfgk.asia/blog/7931474.sHtMl

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.lywfgk.asia/blog/7047479.sHtMl

?
