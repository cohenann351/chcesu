最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：实现异步任务结果查询回调实践
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.t786yd.asia/arts/155643.Doc

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.t786yd.asia/arts/972846.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.t786yd.asia/arts/296509.Doc

原标题：golang 系统设计内部 rpc 接口设计原则梳理
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.t786yd.asia/arts/900340.Doc

原标题：前后端交互跨域问题完整处理
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.t786yd.asia/arts/791047.Doc

原标题：磁盘占满服务不可用清理方案
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.t786yd.asia/arts/055418.Doc

原标题：异步任务堆积消费能力优化
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://wiki.t786yd.asia/arts/237392.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.t786yd.asia/arts/535227.Doc

原标题：程序日志分级输出规范实践
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.t786yd.asia/arts/857698.Doc

原标题：Hands‑on：模板渲染引擎最小原型实现
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.t786yd.asia/arts/093962.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.t786yd.asia/arts/723563.Doc

原标题：golang docker compose 完整语法
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://wiki.t786yd.asia/arts/700295.Doc

原标题：golang mysql limit 大分页优化
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.t786yd.asia/arts/374702.Doc

原标题：安全实践：最小权限原则数据库账号管控
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.t786yd.asia/arts/834977.Doc

原标题：golang k8s helm chart 简单编写
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.t786yd.asia/arts/218918.Doc

原标题：Practice：实现防爬虫简单拦截中间件实践
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.t786yd.asia/arts/759402.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.t786yd.asia/arts/548762.Doc

原标题：eslint prettier 代码规范落地
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.t786yd.asia/arts/240762.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.t786yd.asia/arts/417883.Doc

原标题：程序信号中断退出处理逻辑
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.t786yd.asia/arts/045279.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://wiki.t786yd.asia/arts/089434.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.t786yd.asia/arts/194146.Doc

原标题：提交第一个开源 PR 完整流程
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.t786yd.asia/arts/388501.Doc

原标题：golang 系统设计告警规则阈值设置方法论
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.t786yd.asia/arts/544289.Doc

原标题：golang docker 容器资源限制设置
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.t786yd.asia/arts/961443.Doc

原标题：golang 结构体 json 序列化坑点
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.t786yd.asia/arts/452877.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.t786yd.asia/arts/460765.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.t786yd.asia/arts/489012.Doc

原标题：前端骨架屏提升页面体验
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.t786yd.asia/arts/060525.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.t786yd.asia/arts/205293.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.t786yd.asia/arts/971097.Doc

原标题：从零搭建简单Mock接口服务
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.t786yd.asia/arts/619009.Doc

原标题：实战项目：百万日志文件解析处理脚本实践
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.t786yd.asia/arts/270268.Doc

原标题：golang kafka 死信队列业务落地
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.t786yd.asia/arts/594320.Doc

原标题：golang 系统设计大流量削峰处理方案
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.t786yd.asia/arts/328531.Doc

原标题：golang 系统设计开源项目协作流程梳理
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.t786yd.asia/arts/938743.Doc

原标题：golang 告警推送钉钉机器人实现
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.t786yd.asia/arts/553036.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.t786yd.asia/arts/241335.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.t786yd.asia/arts/789285.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.t786yd.asia/arts/296430.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计分布式事务几种方案优缺点
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://wiki.t786yd.asia/arts/299320.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.t786yd.asia/arts/618034.Doc

原标题：golang 接口请求日志记录中间件
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.t786yd.asia/arts/551085.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.t786yd.asia/arts/297257.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.t786yd.asia/arts/193398.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.t786yd.asia/arts/644594.Doc

原标题：golang kafka 死信队列业务落地
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.t786yd.asia/arts/428011.Doc

原标题：安全复盘：消息队列未授权访问安全加固
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.t786yd.asia/arts/308743.Doc

原标题：golang mysql 主从同步延迟兼容
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.t786yd.asia/arts/575732.Doc

原标题：项目目录结构规范化最佳实践
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.t786yd.asia/arts/896281.Doc

原标题：golang 协程泄露问题排查方法
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://wiki.t786yd.asia/arts/924795.Doc

原标题：golang 优雅处理数据库事务
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.t786yd.asia/arts/270636.Doc

原标题：前端静态缓存更新生效处理
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.t786yd.asia/arts/644220.Doc

原标题：WSL 搭建 Windows Linux 开发环境
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.t786yd.asia/arts/420990.Doc

原标题：golang mysql 批量导入数据实操
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.t786yd.asia/arts/715774.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.t786yd.asia/arts/561413.Doc

原标题：服务健康检查监控接口开发
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.t786yd.asia/arts/084524.Doc

原标题：golang redis 过期 key 监听业务
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.t786yd.asia/arts/230914.Doc

原标题：golang docker compose 依赖启动顺序
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.t786yd.asia/arts/295585.Doc

原标题：golang redis 布隆过滤器安装使用
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.t786yd.asia/arts/155795.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.t786yd.asia/arts/045544.Doc

原标题：数据库分表存储大表优化方案
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.t786yd.asia/arts/756683.Doc

原标题：golang mysql 避免 select * 查询
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.t786yd.asia/arts/828136.Doc

原标题：golang 系统设计 git 分支流程 gitflow 实操
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.t786yd.asia/arts/774767.Doc

原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.t786yd.asia/arts/783575.Doc

原标题：项目实践：本地模拟多节点分布式系统实践
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.t786yd.asia/arts/126016.Doc

原标题：golang 系统设计熔断算法 hystrix 思路
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.t786yd.asia/arts/542830.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.t786yd.asia/arts/277651.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.t786yd.asia/arts/683907.Doc

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.t786yd.asia/arts/021411.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.t786yd.asia/arts/587968.Doc

原标题：开发复盘：统一错误码体系设计落地实践
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.t786yd.asia/arts/130582.Doc

原标题：方案设计：分布式分页查询架构难点处理
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.t786yd.asia/arts/270103.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.t786yd.asia/arts/927770.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.t786yd.asia/arts/619333.Doc

原标题：hosts 配置本地回环访问修复
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.t786yd.asia/arts/633681.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.t786yd.asia/arts/300311.Doc

原标题：golang websocket 服务端开发
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.t786yd.asia/arts/618224.Doc

原标题：超大数据集分页性能优化方案
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.t786yd.asia/arts/118138.Doc

原标题：并发数据覆盖加锁安全处理
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.t786yd.asia/arts/032912.Doc

三、实战开发｜Practice
原标题：golang toml 配置文件解析教程
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.t786yd.asia/arts/864030.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.t786yd.asia/arts/579554.Doc

原标题：golang 系统设计第三方调用超时重试熔断
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.t786yd.asia/arts/723693.Doc

原标题：nestjs 权限守卫鉴权实现方案
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://wiki.t786yd.asia/arts/561745.Doc

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.t786yd.asia/arts/019484.Doc

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.t786yd.asia/arts/741742.Doc

原标题：前端错误监控上报系统搭建
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.t786yd.asia/arts/885060.Doc

原标题：动态定时任务业务调度实现
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://wiki.t786yd.asia/arts/140101.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.t786yd.asia/arts/486512.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.t786yd.asia/arts/564412.Doc

原标题：静态站点自动部署发布方案
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.t786yd.asia/arts/206203.Doc

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.t786yd.asia/arts/086655.Doc

原标题：Practice：模拟第三方接口超时服务降级验证
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.t786yd.asia/arts/656603.Doc

原标题：golang docker 部署 redis 配置要点
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.t786yd.asia/arts/608772.Doc

原标题：网关超时时间调优后端等待
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.t786yd.asia/arts/235752.Doc

原标题：golang kafka 消息丢失重复消费
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.t786yd.asia/arts/463166.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.t786yd.asia/arts/762291.Doc

原标题：新手教程：gitstash暂存工作区变更实操
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://wiki.t786yd.asia/arts/783441.Doc

原标题：golang k8s 监控 prometheus 部署
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://wiki.t786yd.asia/arts/273047.Doc

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.t786yd.asia/arts/934951.Doc

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.t786yd.asia/arts/677970.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.t786yd.asia/arts/790581.Doc

原标题：golang mysql 索引失效常见场景
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.t786yd.asia/arts/012037.Doc

原标题：golang 系统设计接口防刷 ip 限流实现
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://wiki.t786yd.asia/arts/856986.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.t786yd.asia/arts/820033.Doc

原标题：golang docker 镜像体积优化技巧
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.t786yd.asia/arts/857004.Doc

原标题：从零学习简单分布式ID生成思路
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.t786yd.asia/arts/642223.Doc

原标题：golang es 分页深分页性能优化
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.t786yd.asia/arts/162111.Doc

原标题：golang 系统设计技术方案评审关注点清单参考
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.t786yd.asia/arts/562392.Doc

原标题：数据库排序规则统一结果一致
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.t786yd.asia/arts/671044.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://wiki.t786yd.asia/arts/826239.Doc

原标题：零基础理解会话、Cookie、Session基础
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.t786yd.asia/arts/638928.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.t786yd.asia/arts/488300.Doc

原标题：业务接口幂等完整落地案例
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.t786yd.asia/arts/385922.Doc

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.t786yd.asia/arts/019852.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.t786yd.asia/arts/856578.Doc

原标题：线程池拒绝策略任务丢失防护
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.t786yd.asia/arts/686516.Doc

原标题：OpenSource：开源项目许可证License选型指南
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.t786yd.asia/arts/805113.Doc

原标题：golang mysql 批量导入数据实操
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.t786yd.asia/arts/167687.Doc

原标题：上传接口跨域配置特殊适配
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.t786yd.asia/arts/275448.Doc

四、架构设计｜Architecture
原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.t786yd.asia/arts/325747.Doc

原标题：系统文件描述符上限调大
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.t786yd.asia/arts/204382.Doc

原标题：零基础学习简单正则表达式实战案例
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.t786yd.asia/arts/145735.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.t786yd.asia/arts/616621.Doc

原标题：golang 系统设计序列化性能选型对比
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.t786yd.asia/arts/552132.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.t786yd.asia/arts/542087.Doc

原标题：golang url 参数编码处理方案
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.t786yd.asia/arts/153204.Doc

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.t786yd.asia/arts/080081.Doc

原标题：golang cron 定时任务防并发执行
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.t786yd.asia/arts/591530.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.t786yd.asia/arts/046688.Doc

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.t786yd.asia/arts/123342.Doc

原标题：golang 系统设计日志脱敏敏感字段过滤处理
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.t786yd.asia/arts/890601.Doc

原标题：实战：基于内存实现简单消息广播组件
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.t786yd.asia/arts/127761.Doc

原标题：golang grpc protobuf 开发实操
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.t786yd.asia/arts/941053.Doc

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.t786yd.asia/arts/242389.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.t786yd.asia/arts/890586.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.t786yd.asia/arts/343727.Doc

原标题：限流组件计数器令牌桶模式实现
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.t786yd.asia/arts/577792.Doc

?
