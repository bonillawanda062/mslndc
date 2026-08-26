最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计雪花算法 id 原理剖析
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.lluziz.asia/arts/832348.Doc

原标题：golang gin 框架接口开发实战
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.lluziz.asia/arts/719922.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.lluziz.asia/arts/646101.Doc

原标题：Practice：实现限流之后友好业务返回处理
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.lluziz.asia/arts/601728.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.lluziz.asia/arts/604988.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.lluziz.asia/arts/765817.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.lluziz.asia/arts/793084.Doc

原标题：批量异步处理系统业务落地
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.lluziz.asia/arts/829927.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.lluziz.asia/arts/007479.Doc

原标题：golang 系统设计定时任务失败重试告警实现
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://wiki.lluziz.asia/arts/866135.Doc

原标题：golang 系统设计参数校验统一处理方案
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.lluziz.asia/arts/983903.Doc

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.lluziz.asia/arts/203366.Doc

原标题：操作系统内核版本适配服务
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.lluziz.asia/arts/699868.Doc

原标题：服务熔断防止故障级联传播
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.lluziz.asia/arts/172313.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.lluziz.asia/arts/685525.Doc

原标题：golang 系统设计敏感数据加密存储方案
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.lluziz.asia/arts/390192.Doc

原标题：golang es 高亮搜索结果实现方案
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.lluziz.asia/arts/110648.Doc

原标题：Practice：实现异步任务结果查询回调实践
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.lluziz.asia/arts/887531.Doc

原标题：golang 系统设计技术方案文档模板参考
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.lluziz.asia/arts/687277.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.lluziz.asia/arts/122171.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.lluziz.asia/arts/960936.Doc

原标题：nodejs 读取大文件 csv 处理方案
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.lluziz.asia/arts/670760.Doc

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.lluziz.asia/arts/721650.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.lluziz.asia/arts/433771.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.lluziz.asia/arts/758476.Doc

原标题：OpenAPI 自动接口文档生成
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.lluziz.asia/arts/675594.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.lluziz.asia/arts/759659.Doc

原标题：前端国际化多语言方案落地
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.lluziz.asia/arts/394420.Doc

原标题：设计思考：业务系统如何做故障隔离架构
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.lluziz.asia/arts/269795.Doc

原标题：前端防抖节流高频事件处理
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.lluziz.asia/arts/283495.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.lluziz.asia/arts/388985.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.lluziz.asia/arts/003792.Doc

原标题：golang 布隆过滤器实现去重
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.lluziz.asia/arts/597295.Doc

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.lluziz.asia/arts/059023.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.lluziz.asia/arts/171587.Doc

原标题：golang es 分词器选型业务适配
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.lluziz.asia/arts/065598.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.lluziz.asia/arts/490418.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.lluziz.asia/arts/068720.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.lluziz.asia/arts/798840.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.lluziz.asia/arts/985847.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.lluziz.asia/arts/234808.Doc

原标题：golang mysql limit 大分页优化
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.lluziz.asia/arts/014825.Doc

原标题：实践：Git大仓库历史清理减小仓库体积实践
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.lluziz.asia/arts/675863.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.lluziz.asia/arts/298612.Doc

原标题：分布式 ID 全局唯一生成方案
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.lluziz.asia/arts/072034.Doc

原标题：react hooks 常见陷阱避坑指南
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.lluziz.asia/arts/320596.Doc

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.lluziz.asia/arts/693361.Doc

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.lluziz.asia/arts/178466.Doc

原标题：golang redis 热点 key 业务规避
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.lluziz.asia/arts/267260.Doc

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.lluziz.asia/arts/781820.Doc

原标题：用户敏感数据脱敏代码实现
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.lluziz.asia/arts/700769.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.lluziz.asia/arts/572947.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.lluziz.asia/arts/031860.Doc

原标题：开源实践：给开源项目写单元测试贡献代码
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.lluziz.asia/arts/891404.Doc

原标题：从零搭建简单定时任务demo
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://wiki.lluziz.asia/arts/343725.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.lluziz.asia/arts/980832.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.lluziz.asia/arts/866151.Doc

原标题：golang 系统设计读写分离架构示例
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.lluziz.asia/arts/154464.Doc

原标题：golang redis 缓存预热实现思路
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.lluziz.asia/arts/122507.Doc

原标题：请求重试组件退避策略实现
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.lluziz.asia/arts/113128.Doc

原标题：golang gorm ORM 数据库操作
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.lluziz.asia/arts/863257.Doc

原标题：golang 系统设计延迟队列业务实现
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.lluziz.asia/arts/246439.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.lluziz.asia/arts/011339.Doc

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.lluziz.asia/arts/828613.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.lluziz.asia/arts/854736.Doc

原标题：Practice：实现IP黑名单拦截中间件实践
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.lluziz.asia/arts/990939.Doc

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.lluziz.asia/arts/910872.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.lluziz.asia/arts/297274.Doc

原标题：golang 系统设计告警升级通知策略配置思路
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.lluziz.asia/arts/615920.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.lluziz.asia/arts/994193.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.lluziz.asia/arts/563340.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.lluziz.asia/arts/933274.Doc

原标题：优化实践：内存池思想减少频繁分配释放
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.lluziz.asia/arts/576705.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.lluziz.asia/arts/194430.Doc

原标题：golang 容器健康检查接口开发
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.lluziz.asia/arts/547191.Doc

原标题：golang kafka 消费者组原理讲解
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.lluziz.asia/arts/239237.Doc

原标题：Git 代码冲突正确处理方式
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.lluziz.asia/arts/531119.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.lluziz.asia/arts/002430.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.lluziz.asia/arts/097596.Doc

原标题：golang redis 缓存更新策略讲解
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.lluziz.asia/arts/524170.Doc

三、实战开发｜Practice
原标题：批量操作分批处理防止 OOM
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.lluziz.asia/arts/411505.Doc

原标题：GitHub 项目提交推送完整流程讲解
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.lluziz.asia/arts/137170.Doc

原标题：golang 简单爬虫请求防封禁
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.lluziz.asia/arts/245129.Doc

原标题：数据库读写分离性能优化
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.lluziz.asia/arts/884898.Doc

原标题：Performance：数据库join优化，大表join规避
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.lluziz.asia/arts/132950.Doc

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.lluziz.asia/arts/614695.Doc

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.lluziz.asia/arts/615668.Doc

原标题：nodejs 流处理大文件不占内存
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.lluziz.asia/arts/966043.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.lluziz.asia/arts/896521.Doc

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://wiki.lluziz.asia/arts/172766.Doc

原标题：Practice：实现业务id生成不连续有序ID方案
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.lluziz.asia/arts/043909.Doc

原标题：golang 系统设计分布式锁不同场景选型对比
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.lluziz.asia/arts/987587.Doc

原标题：程序信号中断退出处理逻辑
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.lluziz.asia/arts/461831.Doc

原标题：开源实践：开源项目如何写好PullRequest
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.lluziz.asia/arts/891261.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.lluziz.asia/arts/237739.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.lluziz.asia/arts/390838.Doc

原标题：零基础理解读写分离基础思想
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.lluziz.asia/arts/234550.Doc

原标题：golang 系统设计分布式锁选型对比
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.lluziz.asia/arts/958921.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.lluziz.asia/arts/293662.Doc

原标题：golang 系统设计开源项目依赖版本升级维护
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.lluziz.asia/arts/944810.Doc

原标题：golang mysql 悲观锁乐观锁实现
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.lluziz.asia/arts/748975.Doc

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.lluziz.asia/arts/206228.Doc

原标题：golang k8s 持久化 pv pvc 使用实操
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.lluziz.asia/arts/388367.Doc

原标题：Security：开源项目安全审计简易检查清单
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.lluziz.asia/arts/239287.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.lluziz.asia/arts/153748.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.lluziz.asia/arts/227118.Doc

原标题：golang 系统设计接口幂等架构设计
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.lluziz.asia/arts/853305.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.lluziz.asia/arts/647880.Doc

原标题：项目实践：多环境配置管理组件设计与实现
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.lluziz.asia/arts/201400.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.lluziz.asia/arts/012620.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.lluziz.asia/arts/444188.Doc

原标题：golang 令牌桶限流中间件 gin
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.lluziz.asia/arts/101573.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.lluziz.asia/arts/296263.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.lluziz.asia/arts/790399.Doc

原标题：golang k8s rbac 权限控制配置示例
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.lluziz.asia/arts/259452.Doc

原标题：新手教程：配置SSH‑Key免密访问GitHub
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.lluziz.asia/arts/207140.Doc

原标题：golang 消息死信处理业务逻辑
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.lluziz.asia/arts/273165.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.lluziz.asia/arts/527750.Doc

原标题：golang 链路 traceId 透传中间件
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.lluziz.asia/arts/766713.Doc

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.lluziz.asia/arts/860688.Doc

四、架构设计｜Architecture
原标题：批量异步处理系统业务落地
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.lluziz.asia/arts/305129.Doc

原标题：全局异常处理器接口返回统一
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.lluziz.asia/arts/464735.Doc

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.lluziz.asia/arts/301130.Doc

原标题：实践：实现Redis分布式锁完整可运行代码
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.lluziz.asia/arts/310807.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.lluziz.asia/arts/775977.Doc

原标题：golang 系统设计监控大盘故障快速定位思路
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.lluziz.asia/arts/897173.Doc

原标题：golang gin 中间件执行顺序讲解
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.lluziz.asia/arts/275725.Doc

原标题：golang redis 大 key 识别处理方案
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.lluziz.asia/arts/985149.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.lluziz.asia/arts/602765.Doc

原标题：golang 系统设计日志采样降低存储开销方案
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.lluziz.asia/arts/670355.Doc

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.lluziz.asia/arts/422214.Doc

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.lluziz.asia/arts/860491.Doc

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.lluziz.asia/arts/661174.Doc

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.lluziz.asia/arts/297427.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.lluziz.asia/arts/083012.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.lluziz.asia/arts/945732.Doc

原标题：golang 系统设计监控告警阈值设置思路
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.lluziz.asia/arts/820737.Doc

原标题：golang 时间时区处理避坑指南
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.lluziz.asia/arts/041285.Doc

?
