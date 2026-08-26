最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计日志检索排查线上问题实操技巧
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.s0rk9h.asia/arts/715684.Doc

原标题：OAuth2 第三方登录服务搭建
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.s0rk9h.asia/arts/671115.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.s0rk9h.asia/arts/782911.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.s0rk9h.asia/arts/352664.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.s0rk9h.asia/arts/664255.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.s0rk9h.asia/arts/124773.Doc

原标题：golang 系统设计接口返回格式统一规范
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.s0rk9h.asia/arts/647004.Doc

原标题：golang 系统设计秒杀防超卖方案
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.s0rk9h.asia/arts/501807.Doc

原标题：代理 HTTPS 证书访问异常处理
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.s0rk9h.asia/arts/626592.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.s0rk9h.asia/arts/893039.Doc

原标题：设计思考：系统容量评估架构前期估算思路
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.s0rk9h.asia/arts/312579.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.s0rk9h.asia/arts/105784.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.s0rk9h.asia/arts/677763.Doc

原标题：golang ci 流水线自动部署 k8s 示例
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.s0rk9h.asia/arts/566281.Doc

原标题：golang 系统设计状态字段枚举约束设计思路
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.s0rk9h.asia/arts/993682.Doc

原标题：golang mysql limit 大分页优化
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.s0rk9h.asia/arts/260081.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.s0rk9h.asia/arts/590732.Doc

原标题：golang mysql 读写分离简单实现
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.s0rk9h.asia/arts/502157.Doc

原标题：Practice：实现限流之后友好业务返回处理
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.s0rk9h.asia/arts/676551.Doc

原标题：golang 接口返回统一封装工具
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.s0rk9h.asia/arts/374069.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.s0rk9h.asia/arts/483965.Doc

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.s0rk9h.asia/arts/272522.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.s0rk9h.asia/arts/418330.Doc

原标题：golang redis zset 排行榜业务实现
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.s0rk9h.asia/arts/498710.Doc

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.s0rk9h.asia/arts/819416.Doc

原标题：Nginx 丢失请求头配置修正
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.s0rk9h.asia/arts/312951.Doc

原标题：golang 配置热更新不重启服务
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.s0rk9h.asia/arts/071776.Doc

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.s0rk9h.asia/arts/585001.Doc

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.s0rk9h.asia/arts/267285.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.s0rk9h.asia/arts/221811.Doc

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.s0rk9h.asia/arts/422707.Doc

原标题：记一次第三方SDK版本兼容引发线上故障
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.s0rk9h.asia/arts/640125.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.s0rk9h.asia/arts/908996.Doc

原标题：Git commit 钩子提交规范校验
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.s0rk9h.asia/arts/277259.Doc

原标题：golang http grpc 全链路埋点示例
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.s0rk9h.asia/arts/552412.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.s0rk9h.asia/arts/423356.Doc

原标题：时间同步修复令牌提前过期
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.s0rk9h.asia/arts/633052.Doc

原标题：从零搭建本地开发环境完整教程
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://wiki.s0rk9h.asia/arts/071222.Doc

原标题：golang docker 镜像体积优化技巧
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.s0rk9h.asia/arts/012095.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.s0rk9h.asia/arts/263722.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计磁盘满故障应急处理步骤
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.s0rk9h.asia/arts/519617.Doc

原标题：golang consul 健康检查服务注册
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.s0rk9h.asia/arts/452941.Doc

原标题：golang redis 五种数据结构实战
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.s0rk9h.asia/arts/087352.Doc

原标题：golang 系统设计代码仓库权限管理方案
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.s0rk9h.asia/arts/720215.Doc

原标题：新手快速上手 Git 版本控制实操指南
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.s0rk9h.asia/arts/822673.Doc

原标题：golang consul 服务发现简单示例
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.s0rk9h.asia/arts/952818.Doc

原标题：快速入门对象存储基础使用场景
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.s0rk9h.asia/arts/508136.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.s0rk9h.asia/arts/333533.Doc

原标题：golang cpu pprof 性能分析实操
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.s0rk9h.asia/arts/238627.Doc

原标题：缓存过期策略优化防业务故障
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.s0rk9h.asia/arts/464618.Doc

原标题：golang 优雅处理数据库事务
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.s0rk9h.asia/arts/713652.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.s0rk9h.asia/arts/423926.Doc

原标题：站内邮件消息通知功能开发
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.s0rk9h.asia/arts/388815.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.s0rk9h.asia/arts/936753.Doc

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.s0rk9h.asia/arts/460096.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.s0rk9h.asia/arts/605133.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.s0rk9h.asia/arts/215941.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.s0rk9h.asia/arts/657247.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.s0rk9h.asia/arts/755689.Doc

原标题：Mock 接口服务快速搭建实操
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.s0rk9h.asia/arts/592204.Doc

原标题：请求工具封装统一异常处理
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://wiki.s0rk9h.asia/arts/980462.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.s0rk9h.asia/arts/624652.Doc

原标题：Practice：实现跨机器文件同步脚本实践
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.s0rk9h.asia/arts/604543.Doc

原标题：跨平台 uniapp 多端开发实操
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.s0rk9h.asia/arts/497654.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.s0rk9h.asia/arts/294614.Doc

原标题：golang goroutine 协程基础实操
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.s0rk9h.asia/arts/014803.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.s0rk9h.asia/arts/605195.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://wiki.s0rk9h.asia/arts/860329.Doc

原标题：上传接口跨域配置特殊适配
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.s0rk9h.asia/arts/642100.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.s0rk9h.asia/arts/469541.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.s0rk9h.asia/arts/648813.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.s0rk9h.asia/arts/859511.Doc

原标题：安全实践：接口速率限制防止暴力破解
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.s0rk9h.asia/arts/267325.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.s0rk9h.asia/arts/156916.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.s0rk9h.asia/arts/423681.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.s0rk9h.asia/arts/805339.Doc

原标题：安全实践：接口错误信息不要暴露内部细节
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.s0rk9h.asia/arts/645836.Doc

原标题：项目实践：定时任务防重复执行落地实践
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.s0rk9h.asia/arts/644326.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.s0rk9h.asia/arts/034499.Doc

原标题：golang 系统设计分布式任务调度
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.s0rk9h.asia/arts/898399.Doc

三、实战开发｜Practice
原标题：实战：Docker资源监控查看容器状态实操
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.s0rk9h.asia/arts/029274.Doc

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.s0rk9h.asia/arts/311103.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.s0rk9h.asia/arts/826063.Doc

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.s0rk9h.asia/arts/370758.Doc

原标题：golang k8s 监控 prometheus 部署
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.s0rk9h.asia/arts/659836.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.s0rk9h.asia/arts/967186.Doc

原标题：golang prometheus 指标暴露实现
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.s0rk9h.asia/arts/754112.Doc

原标题：Practice：实现请求ID透传全链路日志实践
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.s0rk9h.asia/arts/097780.Doc

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.s0rk9h.asia/arts/356936.Doc

原标题：golang redis zset 排行榜业务实现
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.s0rk9h.asia/arts/637681.Doc

原标题：特殊输入字符过滤解析防护
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://wiki.s0rk9h.asia/arts/560160.Doc

原标题：golang 系统设计数据库查询优化完整流程
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.s0rk9h.asia/arts/970159.Doc

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.s0rk9h.asia/arts/304400.Doc

原标题：布隆过滤器数据高效去重实现
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.s0rk9h.asia/arts/862220.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.s0rk9h.asia/arts/671166.Doc

原标题：golang 系统设计配置敏感信息加密存储
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.s0rk9h.asia/arts/304046.Doc

原标题：安全实践：防止重放攻击接口签名方案
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.s0rk9h.asia/arts/327476.Doc

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.s0rk9h.asia/arts/188858.Doc

原标题：前端打包产物体积压缩优化
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.s0rk9h.asia/arts/528029.Doc

原标题：golang mongodb 聚合管道实操案例
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.s0rk9h.asia/arts/271455.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.s0rk9h.asia/arts/566926.Doc

原标题：优化实践：内存池思想减少频繁分配释放
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.s0rk9h.asia/arts/058263.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.s0rk9h.asia/arts/527073.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.s0rk9h.asia/arts/317075.Doc

原标题：golang grafana 面板变量模板制作
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.s0rk9h.asia/arts/481024.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.s0rk9h.asia/arts/121154.Doc

原标题：golang 系统设计 api 文档 swagger redoc 落地
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.s0rk9h.asia/arts/979577.Doc

原标题：实战：搭建日志收集分析简易完整演示环境
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.s0rk9h.asia/arts/499254.Doc

原标题：前端工程化 webpack 打包优化
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.s0rk9h.asia/arts/145732.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.s0rk9h.asia/arts/662352.Doc

原标题：golang ci 流水线单元测试集成测试
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.s0rk9h.asia/arts/248827.Doc

原标题：部署实践：数据库迁移脚本版本管理实践
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.s0rk9h.asia/arts/048135.Doc

原标题：golang http client 连接池调优
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.s0rk9h.asia/arts/988763.Doc

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.s0rk9h.asia/arts/190170.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.s0rk9h.asia/arts/760178.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.s0rk9h.asia/arts/697067.Doc

原标题：golang 系统设计缓存一致性方案对比
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.s0rk9h.asia/arts/121642.Doc

原标题：nodejs 集成测试业务流程编写
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://wiki.s0rk9h.asia/arts/240981.Doc

原标题：golang 系统设计分布式会话方案对比
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.s0rk9h.asia/arts/087653.Doc

原标题：调优方案：Web服务内核socket参数调优
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.s0rk9h.asia/arts/470408.Doc

四、架构设计｜Architecture
原标题：golang makefile 自动化构建脚本
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.s0rk9h.asia/arts/504469.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://wiki.s0rk9h.asia/arts/248271.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.s0rk9h.asia/arts/974583.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.s0rk9h.asia/arts/106591.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.s0rk9h.asia/arts/523428.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.s0rk9h.asia/arts/491792.Doc

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.s0rk9h.asia/arts/386061.Doc

原标题：golang 优雅停机服务关闭实现
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.s0rk9h.asia/arts/671049.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.s0rk9h.asia/arts/833099.Doc

原标题：golang 系统设计覆盖索引减少回表查询实现
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.s0rk9h.asia/arts/269968.Doc

原标题：实践：数据库回滚点业务调试实践
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.s0rk9h.asia/arts/448469.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.s0rk9h.asia/arts/752274.Doc

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.s0rk9h.asia/arts/993406.Doc

原标题：golang k8s 监控 prometheus 部署
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.s0rk9h.asia/arts/522282.Doc

原标题：golang 系统设计分库分表中间件思路
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.s0rk9h.asia/arts/882562.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.s0rk9h.asia/arts/053098.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.s0rk9h.asia/arts/369921.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.s0rk9h.asia/arts/636629.Doc

?
