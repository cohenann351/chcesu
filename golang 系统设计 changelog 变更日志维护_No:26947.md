最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 changelog 变更日志维护
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.83i556.asia/arts/644491.Doc

原标题：GitHub Markdown 文档语法汇总
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.83i556.asia/arts/719931.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.83i556.asia/arts/682859.Doc

原标题：golang 系统设计 tcp keepalive 参数调优实践
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.83i556.asia/arts/968106.Doc

原标题：golang 配置文件多环境加载
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.83i556.asia/arts/486422.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.83i556.asia/arts/785535.Doc

原标题：接口压测定位系统性能瓶颈
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.83i556.asia/arts/381101.Doc

原标题：Practice：实现文件监控自动重启开发服务工具
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.83i556.asia/arts/081069.Doc

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.83i556.asia/arts/290980.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.83i556.asia/arts/196411.Doc

原标题：golang 系统设计排行榜几种实现
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://wiki.83i556.asia/arts/822555.Doc

原标题：零基础理解依赖管理与包管理器
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://wiki.83i556.asia/arts/775572.Doc

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://wiki.83i556.asia/arts/135985.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.83i556.asia/arts/217216.Doc

原标题：golang docker 运行 etcd 本地测试
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.83i556.asia/arts/322290.Doc

原标题：RPC 报文大小上限调优大请求
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.83i556.asia/arts/245625.Doc

原标题：从零搭建本地数据库开发环境
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.83i556.asia/arts/594488.Doc

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.83i556.asia/arts/346000.Doc

原标题：开发代理服务网络限制解决
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.83i556.asia/arts/715274.Doc

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.83i556.asia/arts/385006.Doc

原标题：golang docker compose 完整语法
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://wiki.83i556.asia/arts/524107.Doc

原标题：golang 系统设计定时任务失败重试告警实现
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.83i556.asia/arts/197187.Doc

原标题：golang alertmanager 钉钉告警推送
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://wiki.83i556.asia/arts/300022.Doc

原标题：golang 系统设计数据库死锁分析规避
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://wiki.83i556.asia/arts/300981.Doc

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.83i556.asia/arts/086392.Doc

原标题：CDN 缓存刷新获取最新静态资源
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.83i556.asia/arts/056066.Doc

原标题：golang k8s 资源请求限制配置
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.83i556.asia/arts/426659.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.83i556.asia/arts/966687.Doc

原标题：Practice：实现简单信号处理优雅停机实践
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.83i556.asia/arts/120270.Doc

原标题：性能调优：MySQL查询性能优化实战清单
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.83i556.asia/arts/052536.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.83i556.asia/arts/971265.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.83i556.asia/arts/205656.Doc

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.83i556.asia/arts/633699.Doc

原标题：前后端会话登录状态持久化
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.83i556.asia/arts/905022.Doc

原标题：批量操作分批处理防止 OOM
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.83i556.asia/arts/084167.Doc

原标题：golang 系统设计多租户数据隔离方案
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.83i556.asia/arts/933052.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.83i556.asia/arts/277658.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.83i556.asia/arts/534177.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.83i556.asia/arts/786887.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.83i556.asia/arts/260189.Doc


二、踩坑排错｜Troubleshooting
原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.83i556.asia/arts/328761.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.83i556.asia/arts/771975.Doc

原标题：配置与镜像分离防止信息泄露
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.83i556.asia/arts/046865.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.83i556.asia/arts/314870.Doc

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.83i556.asia/arts/139940.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.83i556.asia/arts/421535.Doc

原标题：golang 信号量控制并发数量
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.83i556.asia/arts/897622.Doc

原标题：零基础理解内存溢出基础现象与表现
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.83i556.asia/arts/501034.Doc

原标题：系统文件描述符上限调大
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.83i556.asia/arts/918877.Doc

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.83i556.asia/arts/400305.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.83i556.asia/arts/085323.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.83i556.asia/arts/059717.Doc

原标题：golang redis 分布式锁 redisson 思路
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.83i556.asia/arts/368419.Doc

原标题：nodejs 接口限流防刷代码实现
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.83i556.asia/arts/551396.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.83i556.asia/arts/517024.Doc

原标题：游标分页大数据查询性能提升
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.83i556.asia/arts/133663.Doc

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.83i556.asia/arts/688867.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.83i556.asia/arts/973983.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.83i556.asia/arts/812878.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://wiki.83i556.asia/arts/379919.Doc

原标题：调优方案：Nginx性能参数调优高并发配置
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.83i556.asia/arts/462180.Doc

原标题：前端 pdf 预览渲染方案对比
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.83i556.asia/arts/218627.Doc

原标题：golang 静态文件服务搭建教程
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.83i556.asia/arts/078483.Doc

原标题：浏览器缓存强制刷新方案
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.83i556.asia/arts/106346.Doc

原标题：golang 系统设计容器健康检查设计思路
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.83i556.asia/arts/385586.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.83i556.asia/arts/196983.Doc

原标题：消息队列生产消费模型入门
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.83i556.asia/arts/785250.Doc

原标题：缓存穿透防护保护数据库
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.83i556.asia/arts/617214.Doc

原标题：Docker Compose 一键搭建本地栈
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.83i556.asia/arts/508111.Doc

原标题：Nginx 请求头大小上限调整
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.83i556.asia/arts/578073.Doc

原标题：golang prometheus metrics 埋点开发
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.83i556.asia/arts/782847.Doc

原标题：TCP 心跳检测清理僵死连接
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.83i556.asia/arts/459331.Doc

原标题：golang 系统设计灰度发布实现思路
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.83i556.asia/arts/940369.Doc

原标题：Hands‑on：简易链路追踪原型开发实践
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.83i556.asia/arts/691747.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.83i556.asia/arts/953962.Doc

原标题：golang 系统设计本地缓存更新失效方案实现
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.83i556.asia/arts/122614.Doc

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.83i556.asia/arts/135517.Doc

原标题：方案设计：多租户系统架构三种实现模式对比
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.83i556.asia/arts/528683.Doc

原标题：CI 流水线超时时间延长配置
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.83i556.asia/arts/791922.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://wiki.83i556.asia/arts/577333.Doc

三、实战开发｜Practice
原标题：golang 系统设计分库分表 id 全局生成策略
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.83i556.asia/arts/103339.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.83i556.asia/arts/275938.Doc

原标题：golang 数据库连接泄露排查
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.83i556.asia/arts/374402.Doc

原标题：程序性能指标 CPU 内存监控
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.83i556.asia/arts/334825.Doc

原标题：golang 系统设计网络超时故障排查思路
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.83i556.asia/arts/561534.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.83i556.asia/arts/715833.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.83i556.asia/arts/676349.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.83i556.asia/arts/563380.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.83i556.asia/arts/813383.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.83i556.asia/arts/810772.Doc

原标题：golang 系统设计海量数据分页查询
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://wiki.83i556.asia/arts/271880.Doc

原标题：golang mongodb 事务多文档使用
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.83i556.asia/arts/190302.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.83i556.asia/arts/698180.Doc

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.83i556.asia/arts/078418.Doc

原标题：设计思考：容器化业务应用架构改造要点
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.83i556.asia/arts/400075.Doc

原标题：Docker 容器网络不通排查
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.83i556.asia/arts/078885.Doc

原标题：Practice：实现业务操作日志记录中间件实践
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.83i556.asia/arts/023916.Doc

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://wiki.83i556.asia/arts/963460.Doc

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.83i556.asia/arts/156383.Doc

原标题：golang redis zset 延时队列实现
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://wiki.83i556.asia/arts/093919.Doc

原标题：golang 系统设计错误码体系完整设计
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.83i556.asia/arts/787097.Doc

原标题：golang aes 对称加密解密示例
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.83i556.asia/arts/537722.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://wiki.83i556.asia/arts/948621.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.83i556.asia/arts/653389.Doc

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.83i556.asia/arts/602971.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.83i556.asia/arts/942864.Doc

原标题：golang 系统设计熔断降级架构讲解
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.83i556.asia/arts/107391.Doc

原标题：golang 结构体深拷贝几种实现
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.83i556.asia/arts/266298.Doc

原标题：极简方式搭建个人技术文档站点
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.83i556.asia/arts/266800.Doc

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.83i556.asia/arts/820259.Doc

原标题：golang redis 过期策略内存淘汰
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.83i556.asia/arts/415961.Doc

原标题：架构复盘：消息死信处理架构避免消息丢失
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.83i556.asia/arts/710630.Doc

原标题：排错：多实例部署session共享失效登录失效
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.83i556.asia/arts/781177.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.83i556.asia/arts/107181.Doc

原标题：从零学习简单分页逻辑实现思路
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.83i556.asia/arts/875417.Doc

原标题：golang mysql 字符集排序规则设置
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://wiki.83i556.asia/arts/111201.Doc

原标题：golang mongodb 文档结构设计原则
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.83i556.asia/arts/080871.Doc

原标题：CLI 批量处理工具文件操作开发
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.83i556.asia/arts/232900.Doc

原标题：golang ci 流水线制品仓库上传下载
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://wiki.83i556.asia/arts/838517.Doc

原标题：Security：服务器最小权限账号运维实践
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://wiki.83i556.asia/arts/931707.Doc

四、架构设计｜Architecture
原标题：编译打包产物依赖分析解读
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.83i556.asia/arts/089825.Doc

原标题：Hands‑on：简易频率统计组件Redis实现
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.83i556.asia/arts/192627.Doc

原标题：入门实践：实现简单文件读写功能
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.83i556.asia/arts/600579.Doc

原标题：golang 日志 zap 结构化日志实践
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.83i556.asia/arts/041818.Doc

原标题：golang redis 地理位置 geo 使用
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.83i556.asia/arts/734274.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.83i556.asia/arts/891866.Doc

原标题：golang 系统设计短信发送限流降级
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.83i556.asia/arts/451123.Doc

原标题：nodejs 流处理大文件不占内存
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.83i556.asia/arts/634548.Doc

原标题：消息队列生产消费模型入门
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.83i556.asia/arts/126242.Doc

原标题：Architecture：对象存储接入业务整体架构
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.83i556.asia/arts/504547.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.83i556.asia/arts/615511.Doc

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.83i556.asia/arts/116390.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.83i556.asia/arts/199659.Doc

原标题：golang docker compose 部署 minio
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.83i556.asia/arts/596969.Doc

原标题：golang 系统设计分库分表 id 全局生成策略
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.83i556.asia/arts/725652.Doc

原标题：开源源码阅读拆解学习思路
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.83i556.asia/arts/592128.Doc

原标题：新手快速上手 Git 版本控制实操指南
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.83i556.asia/arts/125705.Doc

原标题：service‑worker 离线缓存实践
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.83i556.asia/arts/045418.Doc

?
