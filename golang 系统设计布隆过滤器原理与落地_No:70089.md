最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计布隆过滤器原理与落地
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.d0lohs.asia/arts/771296.Doc

原标题：golang docker 镜像构建最佳实践
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.d0lohs.asia/arts/735919.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.d0lohs.asia/arts/049912.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.d0lohs.asia/arts/616373.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.d0lohs.asia/arts/523450.Doc

原标题：golang redis 主从复制哨兵原理
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.d0lohs.asia/arts/323063.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.d0lohs.asia/arts/723037.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.d0lohs.asia/arts/572281.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.d0lohs.asia/arts/104448.Doc

原标题：nodejs 定时任务生产环境避坑
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.d0lohs.asia/arts/837815.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.d0lohs.asia/arts/949557.Doc

原标题：多规则数据脱敏组件开发
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.d0lohs.asia/arts/790203.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.d0lohs.asia/arts/137967.Doc

原标题：零基础理解依赖管理与包管理器
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.d0lohs.asia/arts/728993.Doc

原标题：golang 项目目录分层规范设计
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.d0lohs.asia/arts/801507.Doc

原标题：开源项目构建失败排查步骤
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.d0lohs.asia/arts/837860.Doc

原标题：操作系统内核版本适配服务
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.d0lohs.asia/arts/809756.Doc

原标题：golang 系统设计网关 websocket 转发配置要点
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.d0lohs.asia/arts/107544.Doc

原标题：Security：Web常见安全漏洞原理与修复清单
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.d0lohs.asia/arts/035289.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.d0lohs.asia/arts/068015.Doc

原标题：方案对比：定时任务框架选型与架构对比
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.d0lohs.asia/arts/841809.Doc

原标题：golang 单元测试 table‑driven
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.d0lohs.asia/arts/087263.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.d0lohs.asia/arts/128552.Doc

原标题：golang 系统设计多租户数据隔离方案
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.d0lohs.asia/arts/169691.Doc

原标题：golang es 查询语句 DSL 实操
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://wiki.d0lohs.asia/arts/091812.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.d0lohs.asia/arts/716165.Doc

原标题：golang 系统设计埋点数据上报方案
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.d0lohs.asia/arts/924816.Doc

原标题：golang 系统设计内部服务调用超时设置要点
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.d0lohs.asia/arts/485973.Doc

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.d0lohs.asia/arts/169391.Doc

原标题：HTTPS 证书过期更新操作
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.d0lohs.asia/arts/221640.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.d0lohs.asia/arts/431998.Doc

原标题：实战项目：前端资源打包体积优化完整实操
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.d0lohs.asia/arts/492638.Doc

原标题：golang redis 发布订阅简单示例
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.d0lohs.asia/arts/643772.Doc

原标题：golang docker 网络模式桥接 host
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.d0lohs.asia/arts/728182.Doc

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.d0lohs.asia/arts/530030.Doc

原标题：Debug：网关超时时间小于后端接口超时设置
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.d0lohs.asia/arts/752938.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.d0lohs.asia/arts/579668.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.d0lohs.asia/arts/866137.Doc

原标题：Security：RPC调用身份认证安全加固
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.d0lohs.asia/arts/157140.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.d0lohs.asia/arts/178396.Doc


二、踩坑排错｜Troubleshooting
原标题：Git commit 钩子提交规范校验
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.d0lohs.asia/arts/155616.Doc

原标题：golang kafka 同步异步消费对比
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.d0lohs.asia/arts/085681.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.d0lohs.asia/arts/837652.Doc

原标题：踩坑记录：端口被占用导致服务启动失败
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.d0lohs.asia/arts/832316.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.d0lohs.asia/arts/828915.Doc

原标题：系统字符集统一乱码修复
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.d0lohs.asia/arts/170543.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.d0lohs.asia/arts/495918.Doc

原标题：架构笔记：分库分表中间件选型业务约束
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.d0lohs.asia/arts/535459.Doc

原标题：golang es 分词器选型业务适配
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.d0lohs.asia/arts/698210.Doc

原标题：TCP 心跳检测清理僵死连接
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://wiki.d0lohs.asia/arts/501244.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.d0lohs.asia/arts/683285.Doc

原标题：WSL 搭建 Windows Linux 开发环境
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.d0lohs.asia/arts/008545.Doc

原标题：实践：灰度流量切分简易实现方案
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.d0lohs.asia/arts/919752.Doc

原标题：多版本开发环境共存配置
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.d0lohs.asia/arts/572071.Doc

原标题：项目语义化版本号规范管理
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.d0lohs.asia/arts/595071.Doc

原标题：前端下载导出文件功能实现
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.d0lohs.asia/arts/024549.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.d0lohs.asia/arts/791471.Doc

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://wiki.d0lohs.asia/arts/047549.Doc

原标题：nodejs 数据库连接池配置调优
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.d0lohs.asia/arts/586001.Doc

原标题：golang 系统设计配置本地缓存降级策略方案
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.d0lohs.asia/arts/335359.Doc

原标题：HTTPS 证书过期更新操作
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.d0lohs.asia/arts/129408.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.d0lohs.asia/arts/840440.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.d0lohs.asia/arts/622672.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.d0lohs.asia/arts/420469.Doc

原标题：golang html 模板渲染简单示例
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.d0lohs.asia/arts/422299.Doc

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.d0lohs.asia/arts/197176.Doc

原标题：golang 消息死信处理业务逻辑
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.d0lohs.asia/arts/564854.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.d0lohs.asia/arts/655642.Doc

原标题：golang 日志脱敏敏感字段过滤
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.d0lohs.asia/arts/633050.Doc

原标题：golang 优雅关闭 grpc 服务示例
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.d0lohs.asia/arts/174605.Doc

原标题：磁盘占满服务不可用清理方案
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.d0lohs.asia/arts/862091.Doc

原标题：日志驱动异常日志不输出修复
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.d0lohs.asia/arts/018515.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.d0lohs.asia/arts/206350.Doc

原标题：nestjs 框架模块化项目搭建
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.d0lohs.asia/arts/942528.Doc

原标题：调优方案：CDN优化静态资源访问延迟
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.d0lohs.asia/arts/324889.Doc

原标题：golang 系统设计日志系统架构思路
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.d0lohs.asia/arts/439760.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.d0lohs.asia/arts/903106.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.d0lohs.asia/arts/027103.Doc

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.d0lohs.asia/arts/561363.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.d0lohs.asia/arts/167084.Doc

三、实战开发｜Practice
原标题：开发生产环境资源路径统一
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.d0lohs.asia/arts/354031.Doc

原标题：golang redis 锁超时业务处理
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.d0lohs.asia/arts/390240.Doc

原标题：golang ci 流水线单元测试集成测试
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.d0lohs.asia/arts/916791.Doc

原标题：golang k8s job 一次性任务执行
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.d0lohs.asia/arts/772956.Doc

原标题：排错：GitLFS大文件推送失败完整排障
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.d0lohs.asia/arts/454465.Doc

原标题：golang gitlab runner 部署与注册实操
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.d0lohs.asia/arts/445962.Doc

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.d0lohs.asia/arts/164521.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.d0lohs.asia/arts/094423.Doc

原标题：容器内存扩容 OOM 被杀死修复
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://wiki.d0lohs.asia/arts/617584.Doc

原标题：golang mysql 读写分离简单实现
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.d0lohs.asia/arts/109864.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.d0lohs.asia/arts/532368.Doc

原标题：接口幂等性防重复请求实现
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.d0lohs.asia/arts/561584.Doc

原标题：Practice：实现文件监控自动重启开发服务工具
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.d0lohs.asia/arts/461187.Doc

原标题：Nginx 丢失请求头配置修正
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.d0lohs.asia/arts/416672.Doc

原标题：排错：前端sourcemap错误线上无法定位报错
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.d0lohs.asia/arts/846140.Doc

原标题：代理 HTTPS 证书访问异常处理
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://wiki.d0lohs.asia/arts/940474.Doc

原标题：golang redis 位图用户签到统计
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.d0lohs.asia/arts/537878.Doc

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.d0lohs.asia/arts/851481.Doc

原标题：golang 系统信号信号量处理
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.d0lohs.asia/arts/544236.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.d0lohs.asia/arts/961873.Doc

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.d0lohs.asia/arts/624178.Doc

原标题：golang consul 健康检查服务注册
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.d0lohs.asia/arts/654529.Doc

原标题：极简方式搭建个人技术文档站点
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.d0lohs.asia/arts/704985.Doc

原标题：开发测试生产多环境配置区分
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.d0lohs.asia/arts/432393.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.d0lohs.asia/arts/279657.Doc

原标题：从零搭建本地开发环境完整教程
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.d0lohs.asia/arts/689630.Doc

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.d0lohs.asia/arts/246734.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.d0lohs.asia/arts/902448.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.d0lohs.asia/arts/748494.Doc

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.d0lohs.asia/arts/450130.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.d0lohs.asia/arts/324289.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.d0lohs.asia/arts/151206.Doc

原标题：golang 系统设计告警规则阈值设置方法论
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.d0lohs.asia/arts/827148.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.d0lohs.asia/arts/806684.Doc

原标题：golang 系统设计接口防刷 ip 限流实现
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.d0lohs.asia/arts/222927.Doc

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.d0lohs.asia/arts/562365.Doc

原标题：特殊输入字符过滤解析防护
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.d0lohs.asia/arts/464755.Doc

原标题：golang 大文件读取内存优化
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://wiki.d0lohs.asia/arts/699615.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.d0lohs.asia/arts/794993.Doc

原标题：golang minio 存储桶权限管控配置
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.d0lohs.asia/arts/568559.Doc

四、架构设计｜Architecture
原标题：golang 系统设计大文件上传架构
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.d0lohs.asia/arts/885354.Doc

原标题：新手快速上手 Git 版本控制实操指南
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.d0lohs.asia/arts/324431.Doc

原标题：golang 项目 docker compose 本地调试
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.d0lohs.asia/arts/148746.Doc

原标题：部署复盘：数据库主从备份恢复演练实践
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.d0lohs.asia/arts/714173.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.d0lohs.asia/arts/163675.Doc

原标题：nodejs 多进程任务分发处理
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.d0lohs.asia/arts/830862.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.d0lohs.asia/arts/438207.Doc

原标题：golang 系统设计定时任务动态启停配置方案
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.d0lohs.asia/arts/969055.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.d0lohs.asia/arts/656608.Doc

原标题：灰度发布策略服务平滑升级
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.d0lohs.asia/arts/824170.Doc

原标题：Security：反序列化漏洞风险识别与规避
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.d0lohs.asia/arts/116957.Doc

原标题：零基础理解内存溢出基础现象与表现
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.d0lohs.asia/arts/788508.Doc

原标题：安全复盘：业务数据脱敏防止泄露实践
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.d0lohs.asia/arts/358339.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.d0lohs.asia/arts/886995.Doc

原标题：项目实践：分布式会话Redis存储落地实践
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.d0lohs.asia/arts/595764.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.d0lohs.asia/arts/658135.Doc

原标题：golang gitlab ci 配置自动构建镜像
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.d0lohs.asia/arts/051216.Doc

原标题：简易网关请求路由过滤模拟
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.d0lohs.asia/arts/954596.Doc

?
