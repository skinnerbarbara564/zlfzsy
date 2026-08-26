最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计契约测试接口兼容性保障思路
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://book.13tfn9.asia/blog/370058.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://book.13tfn9.asia/blog/010366.Doc

原标题：golang docker 网络模式桥接 host
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.13tfn9.asia/blog/013928.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.13tfn9.asia/blog/703012.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://book.13tfn9.asia/blog/245248.Doc

原标题：数据库读写分离性能优化
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.13tfn9.asia/blog/087704.Doc

原标题：golang 系统设计读写分离架构示例
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.13tfn9.asia/blog/432920.Doc

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://book.13tfn9.asia/blog/350775.Doc

原标题：golang lru 缓存淘汰算法编写
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://book.13tfn9.asia/blog/603062.Doc

原标题：消息队列重复消费业务处理
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.13tfn9.asia/blog/025473.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.13tfn9.asia/blog/498004.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://book.13tfn9.asia/blog/967234.Doc

原标题：从零学习简单分布式ID生成思路
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://book.13tfn9.asia/blog/765447.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://book.13tfn9.asia/blog/164254.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://book.13tfn9.asia/blog/834055.Doc

原标题：Practice：实现业务id生成不连续有序ID方案
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.13tfn9.asia/blog/017406.Doc

原标题：无用对象回收抑制内存上涨
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://book.13tfn9.asia/blog/946258.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://book.13tfn9.asia/blog/758585.Doc

原标题：方案设计：批量大数据导出系统架构拆解
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://book.13tfn9.asia/blog/944274.Doc

原标题：golang http grpc 全链路埋点示例
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.13tfn9.asia/blog/199355.Doc

原标题：DevOps：CI构建产物缓存复用加速编译
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.13tfn9.asia/blog/673336.Doc

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.13tfn9.asia/blog/424346.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://book.13tfn9.asia/blog/597862.Doc

原标题：并发数据覆盖加锁安全处理
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://book.13tfn9.asia/blog/798721.Doc

原标题：方案对比：同步事务vs事务消息最终一致性
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://book.13tfn9.asia/blog/570241.Doc

原标题：golang 系统设计分库分表中间件思路
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://book.13tfn9.asia/blog/822314.Doc

原标题：golang kafka offset 提交策略
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://book.13tfn9.asia/blog/536516.Doc

原标题：新手指南：看懂开源项目的Issue与PR
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://book.13tfn9.asia/blog/799271.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://book.13tfn9.asia/blog/113667.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://book.13tfn9.asia/blog/679560.Doc

原标题：golang redis 客户端业务使用
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.13tfn9.asia/blog/428303.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://book.13tfn9.asia/blog/010217.Doc

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://book.13tfn9.asia/blog/007768.Doc

原标题：缓存过期打散防止缓存雪崩
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://book.13tfn9.asia/blog/206037.Doc

原标题：nodejs 数据库连接池配置调优
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.13tfn9.asia/blog/374491.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://book.13tfn9.asia/blog/235955.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.13tfn9.asia/blog/868349.Doc

原标题：golang redis set 集合去重业务
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://book.13tfn9.asia/blog/311933.Doc

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://book.13tfn9.asia/blog/502320.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://book.13tfn9.asia/blog/259672.Doc


二、踩坑排错｜Troubleshooting
原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://book.13tfn9.asia/blog/628249.Doc

原标题：Practice：模拟主从延迟业务兼容方案实践
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://book.13tfn9.asia/blog/236088.Doc

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.13tfn9.asia/blog/757137.Doc

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.13tfn9.asia/blog/647546.Doc

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.13tfn9.asia/blog/035487.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://book.13tfn9.asia/blog/694285.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.13tfn9.asia/blog/254640.Doc

原标题：方案设计：接口版本管理架构向前兼容策略
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://book.13tfn9.asia/blog/465945.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://book.13tfn9.asia/blog/176897.Doc

原标题：零基础理解版本控制核心概念与工作流
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://book.13tfn9.asia/blog/756060.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.13tfn9.asia/blog/809247.Doc

原标题：正则表达式优化 CPU 占满问题
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://book.13tfn9.asia/blog/758663.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.13tfn9.asia/blog/757047.Doc

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://book.13tfn9.asia/blog/336076.Doc

原标题：golang es 更新文档注意版本冲突
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://book.13tfn9.asia/blog/147607.Doc

原标题：golang grafana 监控面板简单配置
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://book.13tfn9.asia/blog/001835.Doc

原标题：golang 时间时区处理避坑指南
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://book.13tfn9.asia/blog/868943.Doc

原标题：nodejs 信号处理优雅关闭服务
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://book.13tfn9.asia/blog/353185.Doc

原标题：golang 灰度权重流量分发简单实现
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://book.13tfn9.asia/blog/022688.Doc

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.13tfn9.asia/blog/579463.Doc

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.13tfn9.asia/blog/049587.Doc

原标题：本地简易配置中心动态管理
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://book.13tfn9.asia/blog/465434.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.13tfn9.asia/blog/689070.Doc

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.13tfn9.asia/blog/901218.Doc

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.13tfn9.asia/blog/689579.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://book.13tfn9.asia/blog/597846.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.13tfn9.asia/blog/452874.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://book.13tfn9.asia/blog/785850.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.13tfn9.asia/blog/735982.Doc

原标题：设计思考：业务系统中什么时候不要用微服务
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://book.13tfn9.asia/blog/240439.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://book.13tfn9.asia/blog/454809.Doc

原标题：golang 系统设计数据库慢请求排查流程
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://book.13tfn9.asia/blog/540090.Doc

原标题：golang 系统设计容器健康检查设计思路
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://book.13tfn9.asia/blog/017929.Doc

原标题：nodejs 流处理大文件不占内存
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://book.13tfn9.asia/blog/504400.Doc

原标题：golang grafana 面板变量模板制作
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.13tfn9.asia/blog/488902.Doc

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://book.13tfn9.asia/blog/314428.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.13tfn9.asia/blog/714480.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.13tfn9.asia/blog/411397.Doc

原标题：入门实战：搭建简易静态网页项目
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.13tfn9.asia/blog/358449.Doc

原标题：内存溢出问题现象识别排查
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.13tfn9.asia/blog/465189.Doc

三、实战开发｜Practice
原标题：动态定时任务业务调度实现
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.13tfn9.asia/blog/414044.Doc

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://book.13tfn9.asia/blog/321040.Doc

原标题：golang 系统设计定时任务调度时间校准要点
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://book.13tfn9.asia/blog/617113.Doc

原标题：DNS TTL 配置域名切换生效
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.13tfn9.asia/blog/491609.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.13tfn9.asia/blog/151442.Doc

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.13tfn9.asia/blog/539597.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://book.13tfn9.asia/blog/203769.Doc

原标题：分布式事务最终一致性实现
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://book.13tfn9.asia/blog/717114.Doc

原标题：内存泄漏定位分析完整流程
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.13tfn9.asia/blog/114655.Doc

原标题：golang 系统设计多级缓存更新策略
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://book.13tfn9.asia/blog/991636.Doc

原标题：golang 分库分表简单路由实现
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://book.13tfn9.asia/blog/884014.Doc

原标题：golang 系统设计序列化性能选型对比
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://book.13tfn9.asia/blog/659374.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.13tfn9.asia/blog/200692.Doc

原标题：零基础理解读写分离基础思想
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.13tfn9.asia/blog/070876.Doc

原标题：golang context 上下文传参讲解
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://book.13tfn9.asia/blog/120074.Doc

原标题：golang 互斥锁读写锁并发安全
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://book.13tfn9.asia/blog/144406.Doc

原标题：golang 系统设计 monorepo 仓库管理方案
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://book.13tfn9.asia/blog/180141.Doc

原标题：手写简易 ORM 理解对象映射
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://book.13tfn9.asia/blog/934200.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.13tfn9.asia/blog/259603.Doc

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://book.13tfn9.asia/blog/307492.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.13tfn9.asia/blog/370473.Doc

原标题：golang 内存 pprof 定位内存泄漏
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://book.13tfn9.asia/blog/209811.Doc

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.13tfn9.asia/blog/140808.Doc

原标题：golang kafka offset 提交策略
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://book.13tfn9.asia/blog/054033.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.13tfn9.asia/blog/575446.Doc

原标题：设计思考：系统限流熔断降级完整防护体系
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://book.13tfn9.asia/blog/897791.Doc

原标题：从零搭建简单的健康检查接口示例
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://book.13tfn9.asia/blog/275289.Doc

原标题：golang redis 发布订阅简单示例
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.13tfn9.asia/blog/743229.Doc

原标题：golang 系统设计大文件上传架构
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.13tfn9.asia/blog/856540.Doc

原标题：golang 系统设计接口超时设计原则梳理
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.13tfn9.asia/blog/355707.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.13tfn9.asia/blog/633074.Doc

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://book.13tfn9.asia/blog/464448.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://book.13tfn9.asia/blog/900153.Doc

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://book.13tfn9.asia/blog/525662.Doc

原标题：golang 系统设计代码仓库权限管理方案
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.13tfn9.asia/blog/352480.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.13tfn9.asia/blog/146747.Doc

原标题：Cookie Session 会话状态管理
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.13tfn9.asia/blog/495847.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://book.13tfn9.asia/blog/970726.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.13tfn9.asia/blog/411448.Doc

原标题：golang 系统设计混沌测试故障注入简单示例
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.13tfn9.asia/blog/588322.Doc

四、架构设计｜Architecture
原标题：Performance：批量导入数据性能优化实践
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://book.13tfn9.asia/blog/226707.Doc

原标题：golang 系统设计缓存基准测试对比方案
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.13tfn9.asia/blog/914544.Doc

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.13tfn9.asia/blog/181398.Doc

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://book.13tfn9.asia/blog/244818.Doc

原标题：热更新开发环境配置教程
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.13tfn9.asia/blog/317711.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://book.13tfn9.asia/blog/126580.Doc

原标题：无用对象回收抑制内存上涨
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://book.13tfn9.asia/blog/710178.Doc

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://book.13tfn9.asia/blog/155911.Doc

原标题：快速入门消息通知简单实现方案
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://book.13tfn9.asia/blog/302806.Doc

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://book.13tfn9.asia/blog/661748.Doc

原标题：golang minio 存储桶权限管控配置
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://book.13tfn9.asia/blog/649927.Doc

原标题：golang 系统设计分库分表中间件思路
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.13tfn9.asia/blog/269169.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.13tfn9.asia/blog/182442.Doc

原标题：跨域偶现失败配置修复
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.13tfn9.asia/blog/806692.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.13tfn9.asia/blog/896127.Doc

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.13tfn9.asia/blog/697205.Doc

原标题：golang mysql 行锁表锁场景区分
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://book.13tfn9.asia/blog/409832.Doc

原标题：golang etcd watch 监听配置变更
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.13tfn9.asia/blog/634717.Doc

?
