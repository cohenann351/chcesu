最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计监控体系指标分类方法论梳理
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.tt9301.asia/arts/492282.Doc

原标题：Debug：DNS缓存TTL设置不当服务切换无法生效
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.tt9301.asia/arts/830710.Doc

原标题：接口幂等性防重复请求实现
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.tt9301.asia/arts/402640.Doc

原标题：Practice：实现业务id生成不连续有序ID方案
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.tt9301.asia/arts/519430.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.tt9301.asia/arts/120666.Doc

原标题：浏览器本地存储安全使用技巧
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://wiki.tt9301.asia/arts/208322.Doc

原标题：日志驱动异常日志不输出修复
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.tt9301.asia/arts/160952.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.tt9301.asia/arts/953563.Doc

原标题：优化实践：多级缓存减少下游服务调用压力
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://wiki.tt9301.asia/arts/971659.Doc

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.tt9301.asia/arts/852905.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.tt9301.asia/arts/150076.Doc

原标题：golang nginx 反向代理 go 服务配置
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.tt9301.asia/arts/160069.Doc

原标题：前端静态缓存更新生效处理
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.tt9301.asia/arts/439414.Doc

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.tt9301.asia/arts/452524.Doc

原标题：线上接口超时故障排查思路
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.tt9301.asia/arts/429733.Doc

原标题：golang 系统设计缓存与数据库一致性权衡
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.tt9301.asia/arts/139662.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.tt9301.asia/arts/770329.Doc

原标题：golang 系统设计大表加索引线上执行方案
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.tt9301.asia/arts/207089.Doc

原标题：golang 系统设计网关路由规则动态配置实现
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.tt9301.asia/arts/753976.Doc

原标题：Architecture：大文件上传下载系统架构设计
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.tt9301.asia/arts/227848.Doc

原标题：golang 静态编译缩小镜像体积
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.tt9301.asia/arts/942773.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.tt9301.asia/arts/488816.Doc

原标题：golang 系统设计压测指标确定与分析
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.tt9301.asia/arts/041181.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.tt9301.asia/arts/052114.Doc

原标题：golang docker 多阶段构建 go 镜像
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.tt9301.asia/arts/431458.Doc

原标题：golang es 分词器选型业务适配
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.tt9301.asia/arts/630738.Doc

原标题：安全笔记：CSP内容安全策略配置实践
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.tt9301.asia/arts/417331.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.tt9301.asia/arts/137347.Doc

原标题：golang docker 容器资源限制设置
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.tt9301.asia/arts/049770.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.tt9301.asia/arts/014925.Doc

原标题：golang docker 镜像构建最佳实践
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.tt9301.asia/arts/858991.Doc

原标题：nodejs 中间件模式原理剖析
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.tt9301.asia/arts/785343.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.tt9301.asia/arts/422065.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.tt9301.asia/arts/898778.Doc

原标题：golang 系统设计大文件上传架构
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.tt9301.asia/arts/875200.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.tt9301.asia/arts/901547.Doc

原标题：golang docker compose 部署 minio
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.tt9301.asia/arts/129334.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.tt9301.asia/arts/093998.Doc

原标题：开发记录：敏感数据加密存储解密业务实践
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.tt9301.asia/arts/934665.Doc

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.tt9301.asia/arts/248953.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.tt9301.asia/arts/059761.Doc

原标题：golang etcd 租约 lease 过期机制
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.tt9301.asia/arts/889149.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.tt9301.asia/arts/604548.Doc

原标题：快速入门简单签名校验实现思路
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.tt9301.asia/arts/896435.Doc

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.tt9301.asia/arts/727663.Doc

原标题：golang docker compose 环境变量
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.tt9301.asia/arts/481430.Doc

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.tt9301.asia/arts/838636.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.tt9301.asia/arts/645299.Doc

原标题：golang github actions 发布 release 包
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.tt9301.asia/arts/667331.Doc

原标题：复盘总结：技术方案文档模板架构设计文档
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.tt9301.asia/arts/362503.Doc

原标题：零基础学习简单正则表达式实战案例
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.tt9301.asia/arts/490252.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.tt9301.asia/arts/022395.Doc

原标题：ORM 框架数据库增删改查实操
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.tt9301.asia/arts/952951.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.tt9301.asia/arts/498879.Doc

原标题：环境变量不生效问题修复
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.tt9301.asia/arts/597323.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.tt9301.asia/arts/536576.Doc

原标题：零基础理解前后端简单交互流程
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://wiki.tt9301.asia/arts/760627.Doc

原标题：项目构建脚本编译打包解析
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.tt9301.asia/arts/852105.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.tt9301.asia/arts/885880.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.tt9301.asia/arts/412188.Doc

原标题：golang 系统设计技术方案评审关注点清单参考
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.tt9301.asia/arts/344390.Doc

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.tt9301.asia/arts/452424.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.tt9301.asia/arts/185995.Doc

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.tt9301.asia/arts/775371.Doc

原标题：CI 流水线超时时间延长配置
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.tt9301.asia/arts/059859.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.tt9301.asia/arts/726312.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.tt9301.asia/arts/393250.Doc

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.tt9301.asia/arts/757997.Doc

原标题：接口限流逻辑简单模拟实现
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.tt9301.asia/arts/677989.Doc

原标题：服务启动依赖顺序配置正确
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.tt9301.asia/arts/017421.Doc

原标题：Cookie 跨环境登录配置调整
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.tt9301.asia/arts/372523.Doc

原标题：大事务拆分防止连接池耗尽
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.tt9301.asia/arts/460966.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.tt9301.asia/arts/751275.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.tt9301.asia/arts/374838.Doc

原标题：文件编码统一随机乱码修复
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.tt9301.asia/arts/433900.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.tt9301.asia/arts/769234.Doc

原标题：新手向：项目目录结构规范与含义解析
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.tt9301.asia/arts/975215.Doc

原标题：开发测试生产多环境配置区分
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.tt9301.asia/arts/166201.Doc

原标题：golang 系统设计缓存降级开关快速切库实现
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.tt9301.asia/arts/058504.Doc

原标题：消息队列生产消费模型入门
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.tt9301.asia/arts/161884.Doc

三、实战开发｜Practice
原标题：架构复盘：消息死信处理架构避免消息丢失
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.tt9301.asia/arts/941162.Doc

原标题：实践：静态站点自动化部署到GitHubPages
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.tt9301.asia/arts/838416.Doc

原标题：分布式 ID 全局唯一生成方案
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.tt9301.asia/arts/632690.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.tt9301.asia/arts/426398.Doc

原标题：开发记录：敏感数据加密存储解密业务实践
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.tt9301.asia/arts/134061.Doc

原标题：系统时间同步定时任务偏移
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.tt9301.asia/arts/600479.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.tt9301.asia/arts/861305.Doc

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.tt9301.asia/arts/666179.Doc

原标题：站内邮件消息通知功能开发
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.tt9301.asia/arts/520693.Doc

原标题：文件监控服务自动重启开发
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.tt9301.asia/arts/233590.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.tt9301.asia/arts/301336.Doc

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.tt9301.asia/arts/048444.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.tt9301.asia/arts/185690.Doc

原标题：Git commit 钩子提交规范校验
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.tt9301.asia/arts/267319.Doc

原标题：golang 错误包装 errors.wrap 用法
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.tt9301.asia/arts/190887.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.tt9301.asia/arts/752438.Doc

原标题：避坑：批量操作未分批次，一次性内存打爆
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.tt9301.asia/arts/304072.Doc

原标题：快速入门消息队列基础概念模型
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.tt9301.asia/arts/275094.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.tt9301.asia/arts/786009.Doc

原标题：golang 分布式锁防死锁处理
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.tt9301.asia/arts/020227.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.tt9301.asia/arts/918057.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.tt9301.asia/arts/286982.Doc

原标题：golang 系统设计分布式锁选型对比
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.tt9301.asia/arts/559524.Doc

原标题：缓存过期策略优化防业务故障
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.tt9301.asia/arts/634039.Doc

原标题：hosts 配置本地回环访问修复
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.tt9301.asia/arts/567361.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://wiki.tt9301.asia/arts/348276.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.tt9301.asia/arts/011338.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.tt9301.asia/arts/603135.Doc

原标题：部署复盘：容器OOM问题完整排查流程
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.tt9301.asia/arts/564116.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.tt9301.asia/arts/501280.Doc

原标题：golang mongodb 聚合管道实操案例
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://wiki.tt9301.asia/arts/263928.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.tt9301.asia/arts/345075.Doc

原标题：快速入门WebSocket，实现简易双向通信demo
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.tt9301.asia/arts/426586.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://wiki.tt9301.asia/arts/630583.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.tt9301.asia/arts/591588.Doc

原标题：golang 系统设计消息发送确认机制配置实操
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.tt9301.asia/arts/060721.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.tt9301.asia/arts/113696.Doc

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.tt9301.asia/arts/073590.Doc

原标题：实战：基于DockerCompose搭建本地开发栈
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.tt9301.asia/arts/753179.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.tt9301.asia/arts/935319.Doc

四、架构设计｜Architecture
原标题：JSON XML 数据解析处理示例
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.tt9301.asia/arts/373279.Doc

原标题：golang http grpc 全链路埋点示例
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.tt9301.asia/arts/720302.Doc

原标题：golang 互斥锁读写锁并发安全
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.tt9301.asia/arts/203052.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.tt9301.asia/arts/767579.Doc

原标题：golang redis zset 延时队列实现
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.tt9301.asia/arts/317645.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.tt9301.asia/arts/331425.Doc

原标题：macOS 脚本执行权限开启
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.tt9301.asia/arts/885143.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.tt9301.asia/arts/472222.Doc

原标题：零基础理解内存溢出基础现象与表现
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.tt9301.asia/arts/158735.Doc

原标题：golang http 请求重试封装工具
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.tt9301.asia/arts/037726.Doc

原标题：全平台系统环境变量配置
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.tt9301.asia/arts/019165.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.tt9301.asia/arts/674924.Doc

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://wiki.tt9301.asia/arts/558870.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://wiki.tt9301.asia/arts/137929.Doc

原标题：golang 系统设计布隆过滤器原理与落地
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.tt9301.asia/arts/718902.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.tt9301.asia/arts/755968.Doc

原标题：Practice：实现文件监控自动重启开发服务工具
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.tt9301.asia/arts/830631.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.tt9301.asia/arts/079521.Doc

?
