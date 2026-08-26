最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：模拟主从延迟业务兼容方案实践
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.t2kuti.asia/arts/616545.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.t2kuti.asia/arts/533556.Doc

原标题：golang 系统设计架构图绘制规范简单建议
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.t2kuti.asia/arts/756563.Doc

原标题：golang 参数校验业务接口处理
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.t2kuti.asia/arts/575747.Doc

原标题：golang 系统设计架构图绘制规范简单建议
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.t2kuti.asia/arts/304322.Doc

原标题：开发记录：容器日志标准输出采集实践方案
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.t2kuti.asia/arts/673458.Doc

原标题：部署实践：数据库迁移脚本版本管理实践
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.t2kuti.asia/arts/648834.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.t2kuti.asia/arts/264518.Doc

原标题：golang 系统设计防重复提交实现
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.t2kuti.asia/arts/308147.Doc

原标题：新手教程：如何给开源项目提交第一个PR
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wiki.t2kuti.asia/arts/946359.Doc

原标题：golang 大文件读取内存优化
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.t2kuti.asia/arts/995119.Doc

原标题：方案对比：定时任务框架选型与架构对比
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.t2kuti.asia/arts/552547.Doc

原标题：golang 系统设计服务优雅停机完整流程
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.t2kuti.asia/arts/326228.Doc

原标题：实战：数据库explain执行计划分析实操演练
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.t2kuti.asia/arts/565233.Doc

原标题：golang http 服务性能优化调参
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wiki.t2kuti.asia/arts/822313.Doc

原标题：数值类型溢出错乱问题修复
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.t2kuti.asia/arts/205174.Doc

原标题：安全复盘：消息队列未授权访问安全加固
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.t2kuti.asia/arts/475776.Doc

原标题：golang 系统设计故障止损降级回滚执行原则
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.t2kuti.asia/arts/578454.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://wiki.t2kuti.asia/arts/357081.Doc

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.t2kuti.asia/arts/304736.Doc

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.t2kuti.asia/arts/871737.Doc

原标题：golang 系统设计混沌测试故障注入简单示例
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.t2kuti.asia/arts/357042.Doc

原标题：golang grafana 监控面板简单配置
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.t2kuti.asia/arts/840005.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.t2kuti.asia/arts/503601.Doc

原标题：golang 系统设计数据库版本迁移回滚方案
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.t2kuti.asia/arts/831413.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.t2kuti.asia/arts/341841.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.t2kuti.asia/arts/989228.Doc

原标题：golang 跨域处理中间件编写
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.t2kuti.asia/arts/067486.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.t2kuti.asia/arts/824023.Doc

原标题：快速上手搭建简易内网测试服务
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.t2kuti.asia/arts/706674.Doc

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.t2kuti.asia/arts/531859.Doc

原标题：golang mysql 主从同步延迟兼容
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.t2kuti.asia/arts/619877.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.t2kuti.asia/arts/730448.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://wiki.t2kuti.asia/arts/161798.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.t2kuti.asia/arts/454106.Doc

原标题：从零编写简易 CLI 命令行工具
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.t2kuti.asia/arts/531563.Doc

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.t2kuti.asia/arts/867501.Doc

原标题：安全笔记：CSP内容安全策略配置实践
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.t2kuti.asia/arts/746953.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.t2kuti.asia/arts/368098.Doc

原标题：实践：接口参数自动校验业务落地实践
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.t2kuti.asia/arts/205089.Doc


二、踩坑排错｜Troubleshooting
原标题：CI 持续集成自动构建流程
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.t2kuti.asia/arts/854365.Doc

原标题：golang 系统设计大表结构变更不停机方案
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.t2kuti.asia/arts/712613.Doc

原标题：golang kafka 死信队列业务落地
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.t2kuti.asia/arts/963465.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.t2kuti.asia/arts/975895.Doc

原标题：静态资源 404 路径打包修复
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.t2kuti.asia/arts/937368.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.t2kuti.asia/arts/275689.Doc

原标题：golang docker 部署 prometheus 整套
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://wiki.t2kuti.asia/arts/178615.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.t2kuti.asia/arts/285699.Doc

原标题：ORM 框架数据库增删改查实操
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.t2kuti.asia/arts/913436.Doc

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.t2kuti.asia/arts/041915.Doc

原标题：golang 系统设计 json 解析性能优化实操
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.t2kuti.asia/arts/885361.Doc

原标题：golang 重试退避机制代码实现
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.t2kuti.asia/arts/938125.Doc

原标题：golang 系统设计数据库索引设计方法论
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.t2kuti.asia/arts/629818.Doc

原标题：Nginx 静态代理负载均衡全套配置
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.t2kuti.asia/arts/182477.Doc

原标题：golang viper 配置热更新实操
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://wiki.t2kuti.asia/arts/013292.Doc

原标题：golang pprof 线上采集性能数据
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.t2kuti.asia/arts/053714.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.t2kuti.asia/arts/114991.Doc

原标题：golang 灰度权重流量分发简单实现
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.t2kuti.asia/arts/734871.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.t2kuti.asia/arts/113765.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.t2kuti.asia/arts/111088.Doc

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.t2kuti.asia/arts/163211.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.t2kuti.asia/arts/283847.Doc

原标题：SourceMap 生成线上报错定位
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.t2kuti.asia/arts/459977.Doc

原标题：零基础理解内存溢出基础现象与表现
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.t2kuti.asia/arts/434840.Doc

原标题：nodejs 事件循环机制完整讲解
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.t2kuti.asia/arts/480369.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.t2kuti.asia/arts/052225.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.t2kuti.asia/arts/121222.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.t2kuti.asia/arts/672170.Doc

原标题：golang 系统设计会话共享多实例部署
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.t2kuti.asia/arts/306236.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.t2kuti.asia/arts/198002.Doc

原标题：golang nginx 反向代理 go 服务配置
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.t2kuti.asia/arts/047030.Doc

原标题：踩坑记录：端口被占用导致服务启动失败
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.t2kuti.asia/arts/485861.Doc

原标题：golang 系统设计故障演练简单思路
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://wiki.t2kuti.asia/arts/529144.Doc

原标题：分布式 ID 生成器高并发实现
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.t2kuti.asia/arts/015263.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.t2kuti.asia/arts/426793.Doc

原标题：部署实践：数据库迁移脚本版本管理实践
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.t2kuti.asia/arts/134930.Doc

原标题：golang 系统设计大文件上传架构
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://wiki.t2kuti.asia/arts/437182.Doc

原标题：图片上传预览格式大小处理
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.t2kuti.asia/arts/798892.Doc

原标题：分布式 ID 全局唯一生成方案
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.t2kuti.asia/arts/374115.Doc

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.t2kuti.asia/arts/127007.Doc

三、实战开发｜Practice
原标题：golang 系统设计消息体序列化选型对比
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.t2kuti.asia/arts/195324.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.t2kuti.asia/arts/898570.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.t2kuti.asia/arts/012590.Doc

原标题：架构笔记：分库分表中间件选型业务约束
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.t2kuti.asia/arts/158747.Doc

原标题：快速上手搭建简易内网测试服务
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.t2kuti.asia/arts/130080.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.t2kuti.asia/arts/823711.Doc

原标题：坑点：gitcherry‑pick引入不兼容代码
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.t2kuti.asia/arts/576996.Doc

原标题：golang 系统设计分布式配置中心思路
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.t2kuti.asia/arts/118479.Doc

原标题：golang grpc protobuf 开发实操
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.t2kuti.asia/arts/060115.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.t2kuti.asia/arts/671498.Doc

原标题：异步异常捕获避免进程崩溃
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.t2kuti.asia/arts/945818.Doc

原标题：实战：Redis管道批量操作性能优化实践
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.t2kuti.asia/arts/415067.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.t2kuti.asia/arts/853003.Doc

原标题：golang 系统设计状态字段枚举约束设计思路
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.t2kuti.asia/arts/139547.Doc

原标题：golang redis bitmap 位图统计实现
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.t2kuti.asia/arts/453529.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.t2kuti.asia/arts/008711.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.t2kuti.asia/arts/232019.Doc

原标题：macOS 脚本执行权限开启
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.t2kuti.asia/arts/966241.Doc

原标题：数据库分表路由写入分片修正
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.t2kuti.asia/arts/998177.Doc

原标题：手写简易 RPC 服务通信原型
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.t2kuti.asia/arts/268711.Doc

原标题：golang docker compose 环境变量
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.t2kuti.asia/arts/424081.Doc

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://wiki.t2kuti.asia/arts/578339.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.t2kuti.asia/arts/522829.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.t2kuti.asia/arts/619866.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.t2kuti.asia/arts/767171.Doc

原标题：golang base64 编码解码实操
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.t2kuti.asia/arts/640460.Doc

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.t2kuti.asia/arts/800431.Doc

原标题：golang go test 覆盖率统计实操
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.t2kuti.asia/arts/385636.Doc

原标题：golang 项目 makefile 脚本编写
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.t2kuti.asia/arts/978167.Doc

原标题：方案对比：同步事务vs事务消息最终一致性
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.t2kuti.asia/arts/018625.Doc

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.t2kuti.asia/arts/199795.Doc

原标题：golang 数据库批量更新性能优化
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.t2kuti.asia/arts/240398.Doc

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.t2kuti.asia/arts/653981.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.t2kuti.asia/arts/133545.Doc

原标题：分布式 ID 生成器高并发实现
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.t2kuti.asia/arts/626334.Doc

原标题：快速上手简单性能监控指标查看
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.t2kuti.asia/arts/852299.Doc

原标题：golang 系统设计延迟队列业务实现
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.t2kuti.asia/arts/582450.Doc

原标题：从零搭建本地开发环境完整教程
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.t2kuti.asia/arts/902439.Doc

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.t2kuti.asia/arts/338876.Doc

原标题：CI 流水线构建失败日志排查
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.t2kuti.asia/arts/670802.Doc

四、架构设计｜Architecture
原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://wiki.t2kuti.asia/arts/612338.Doc

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.t2kuti.asia/arts/413212.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.t2kuti.asia/arts/357106.Doc

原标题：实战：数据库索引设计，复合索引最佳实践
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.t2kuti.asia/arts/490494.Doc

原标题：golang redis 缓存更新策略讲解
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.t2kuti.asia/arts/350373.Doc

原标题：消息消费重试次数限制防爆炸
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.t2kuti.asia/arts/190721.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.t2kuti.asia/arts/971036.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.t2kuti.asia/arts/898004.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.t2kuti.asia/arts/507112.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.t2kuti.asia/arts/278509.Doc

原标题：golang ci 流水线自动部署 k8s 示例
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.t2kuti.asia/arts/757620.Doc

原标题：零基础理解会话、Cookie、Session基础
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.t2kuti.asia/arts/123768.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.t2kuti.asia/arts/927296.Doc

原标题：golang cpu pprof 性能分析实操
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.t2kuti.asia/arts/469853.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.t2kuti.asia/arts/752033.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.t2kuti.asia/arts/123921.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://wiki.t2kuti.asia/arts/582398.Doc

原标题：golang 系统设计 changelog 变更日志维护
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.t2kuti.asia/arts/673655.Doc

?
