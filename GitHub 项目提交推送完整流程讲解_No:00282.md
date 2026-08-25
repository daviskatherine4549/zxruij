最新前沿技术资讯

一、入门教程｜Getting Started
原标题：GitHub 项目提交推送完整流程讲解
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://uvw3.yyctmcg.asia/

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://nHlF.yyctmcg.asia/

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://jDhB.yyctmcg.asia/

原标题：批量操作分批处理防止 OOM
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://f9d7.yyctmcg.asia/

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://b5Z3.yyctmcg.asia/

原标题：接口签名校验防篡改实现
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://X1Vz.yyctmcg.asia/

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://TxRv.yyctmcg.asia/

原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://PtNr.yyctmcg.asia/

原标题：Debug：DNS缓存TTL设置不当服务切换无法生效
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://LpJn.yyctmcg.asia/

原标题：Architecture：事件溯源架构模式适用业务场景
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://HlFj.yyctmcg.asia/

原标题：golang traceId spanId 传递方案
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://DBf9.yyctmcg.asia/

原标题：golang 系统设计分布式锁不同场景选型对比
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://d7b5.yyctmcg.asia/

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://Z3X1.yyctmcg.asia/

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://VzTx.yyctmcg.asia/

原标题：调优方案：Docker容器内核参数性能调优
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://RvPt.yyctmcg.asia/

原标题：Architecture：服务注册发现架构原理与选型
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://NrLp.yyctmcg.asia/

原标题：golang ci 流水线单元测试集成测试
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://JnHl.yyctmcg.asia/

原标题：golang 系统设计传输加密 tls 配置要点
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://FjDh.yyctmcg.asia/

原标题：实战项目：实现分布式任务调度最小原型
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://Bf9d.yyctmcg.asia/

原标题：golang 系统设计容器健康检查设计思路
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://7b5Z.yyctmcg.asia/

原标题：golang 分库分表简单路由实现
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://X1Uy.yyctmcg.asia/

原标题：开源项目构建失败排查步骤
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://SwQu.yyctmcg.asia/

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://OsMq.yyctmcg.asia/

原标题：开发复盘：数据库批量更新优化性能实践
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://KoIm.yyctmcg.asia/

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://GkEi.yyctmcg.asia/

原标题：golang 系统设计监控告警阈值设置思路
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://CgAe.yyctmcg.asia/

原标题：golang 系统设计服务优雅停机完整流程
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://8c6a.yyctmcg.asia/

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://4Y2W.yyctmcg.asia/

原标题：golang 系统设计 git 分支流程 gitflow 实操
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://0UyS.yyctmcg.asia/

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wQuO.yyctmcg.asia/

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://MqKo.yyctmcg.asia/

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://ImGk.yyctmcg.asia/

原标题：golang es 索引生命周期管理思路
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://EiCg.yyctmcg.asia/

原标题：快速入门GraphQL基础查询语法示例
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://Ae8c.yyctmcg.asia/

原标题：前端工程化 webpack 打包优化
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://6a4Y.yyctmcg.asia/

原标题：数据库索引重建提升查询速度
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://2W0U.yyctmcg.asia/

原标题：Performance：后端接口性能优化完整分析流程
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://ySwQ.yyctmcg.asia/

原标题：golang 系统设计配置敏感信息加密存储
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://uOsM.yyctmcg.asia/

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://qKoI.yyctmcg.asia/

原标题：golang kafka 消费者组原理讲解
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://mGki.yyctmcg.asia/


二、踩坑排错｜Troubleshooting
原标题：业务错误码完整落地实践
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://CgAe.yyctmcg.asia/

原标题：golang validator 自定义校验规则
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://8c6Z.yyctmcg.asia/

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://3X1V.yyctmcg.asia/

原标题：安全复盘：业务接口越权测试与修复实践
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://zTxR.yyctmcg.asia/

原标题：golang 系统设计告警升级通知策略配置思路
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://vPtN.yyctmcg.asia/

原标题：Performance：JSON序列化性能优化实践
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://rLpJ.yyctmcg.asia/

原标题：golang 系统设计分布式锁选型对比
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://nHlF.yyctmcg.asia/

原标题：golang k8s pod 优雅关闭流程讲解
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://jDhB.yyctmcg.asia/

原标题：golang 系统设计服务优雅停机完整流程
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://f9d7.yyctmcg.asia/

原标题：pnpm 包管理工具实战避坑指南
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://b53X.yyctmcg.asia/

原标题：安全实践：防止JSON解析漏洞恶意payload
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://1VzT.yyctmcg.asia/

原标题：后端分页查询逻辑代码实现
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://xRvP.yyctmcg.asia/

原标题：golang 配置文件多环境加载
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://tNrL.yyctmcg.asia/

原标题：golang 项目目录分层规范设计
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://pJnH.yyctmcg.asia/

原标题：vite 插件开发自定义构建逻辑
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://lFjD.yyctmcg.asia/

原标题：golang etcd 配置中心简单使用
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://hBf9.yyctmcg.asia/

原标题：动态定时任务业务调度实现
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://d7b5.yyctmcg.asia/

原标题：golang 系统设计缓存故障降级处理方案
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://Z3X1.yyctmcg.asia/

原标题：全量回归测试提升代码质量
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://VzTx.yyctmcg.asia/

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://RPtN.yyctmcg.asia/

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://rLpJ.yyctmcg.asia/

原标题：golang context 上下文传参讲解
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://nHlF.yyctmcg.asia/

原标题：golang 系统设计限流服务架构讲解
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://jDhB.yyctmcg.asia/

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://f8c6.yyctmcg.asia/

原标题：golang redis 计数器防超卖示例
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://a4Y2.yyctmcg.asia/

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://W0Uy.yyctmcg.asia/

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://SwQu.yyctmcg.asia/

原标题：Performance：缓存策略优化，降低数据库压力
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://OsMq.yyctmcg.asia/

原标题：golang grpc protobuf 开发实操
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://KoIm.yyctmcg.asia/

原标题：SourceMap 生成线上报错定位
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://kEiC.yyctmcg.asia/

原标题：git cherry‑pick 规范操作防 bug
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://gAe8.yyctmcg.asia/

原标题：零基础理解读写分离基础思想
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://c6a4.yyctmcg.asia/

原标题：复盘总结：数据库迁移升级风险评估清单
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://Y2W0.yyctmcg.asia/

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://UySw.yyctmcg.asia/

原标题：Hands‑on：实现WebSocket聊天室完整前后端demo
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://QuOs.yyctmcg.asia/

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://MqKo.yyctmcg.asia/

原标题：前后端交互跨域问题完整处理
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://ImGk.yyctmcg.asia/

原标题：golang 系统设计埋点数据上报方案
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://EiCg.yyctmcg.asia/

原标题：golang 数据库连接泄露排查
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://Ae8c.yyctmcg.asia/

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://a4Y2.yyctmcg.asia/

三、实战开发｜Practice
原标题：golang 系统设计分布式会话方案对比
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://W0Uy.yyctmcg.asia/

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://SwQu.yyctmcg.asia/

原标题：从零学习基础的接口请求与参数处理
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://OsMq.yyctmcg.asia/

原标题：入门实践：简单的请求封装与异常捕获
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://KoIm.yyctmcg.asia/

原标题：golang k8s 资源请求限制配置
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://GkDh.yyctmcg.asia/

原标题：golang mysql 悲观锁乐观锁实现
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://Bf9d.yyctmcg.asia/

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://7b5Z.yyctmcg.asia/

原标题：css 变量主题切换方案实现
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://3X1V.yyctmcg.asia/

原标题：golang traceId spanId 传递方案
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://zTxv.yyctmcg.asia/

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://PtNr.yyctmcg.asia/

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://LpJn.yyctmcg.asia/

原标题：本地运行正常线上报错排查
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://HlFj.yyctmcg.asia/

原标题：优化实践：多级缓存减少下游服务调用压力
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://DhBf.yyctmcg.asia/

原标题：前端骨架屏提升页面体验
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://9d7b.yyctmcg.asia/

原标题：golang 系统设计 monorepo 仓库管理方案
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://5Z3X.yyctmcg.asia/

原标题：网络读取超时设置连接挂起防护
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://1VzT.yyctmcg.asia/

原标题：golang mysql 分表 id 路由逻辑
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://xRvP.yyctmcg.asia/

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://tNrL.yyctmcg.asia/

原标题：golang 系统设计定时任务执行超时中断防护
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://pJHl.yyctmcg.asia/

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://FjDh.yyctmcg.asia/

原标题：方案设计：分布式锁失效风险架构层面规避
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://Bf9d.yyctmcg.asia/

原标题：golang minio 存储桶权限管控配置
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://7b5Z.yyctmcg.asia/

原标题：golang http 请求重试封装工具
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://3X1V.yyctmcg.asia/

原标题：golang redis 过期策略内存淘汰
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://zTxR.yyctmcg.asia/

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://vPtN.yyctmcg.asia/

原标题：golang goroutine 池任务调度
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://rLpI.yyctmcg.asia/

原标题：前端水印防信息泄露实现
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://dx7y.yyctmcg.asia/

原标题：golang 系统设计基准测试 benchmark 编写
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://iCgA.yyctmcg.asia/

原标题：golang mysql 连接泄漏检测方法
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://ec6a.yyctmcg.asia/

原标题：Practice：实现多级缓存本地缓存+Redis实践
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://4Y2W.yyctmcg.asia/

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://0UyS.yyctmcg.asia/

原标题：golang 系统设计 protobuf 可选字段使用技巧
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wQuO.yyctmcg.asia/

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://sMqK.yyctmcg.asia/

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://oImG.yyctmcg.asia/

原标题：运维笔记：CI流水线缓存策略加速构建速度
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://kEiC.yyctmcg.asia/

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://gAe8.yyctmcg.asia/

原标题：性能复盘：数据库回滚日志过大性能影响优化
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://c6a4.yyctmcg.asia/

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://Y2W0.yyctmcg.asia/

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://ySwQ.yyctmcg.asia/

原标题：DevOps：日志标准输出容器日志收集方案
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://uOsM.yyctmcg.asia/

四、架构设计｜Architecture
原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://qKoI.yyctmcg.asia/

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://mGkE.yyctmcg.asia/

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://iCgA.yyctmcg.asia/

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://e8c6.yyctmcg.asia/

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://a4Y2.yyctmcg.asia/

原标题：Nginx 静态代理负载均衡全套配置
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://W0Uy.yyctmcg.asia/

原标题：golang es 查询语句 DSL 实操
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://SwQu.yyctmcg.asia/

原标题：文件锁正确使用避免死锁
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://OrLp.yyctmcg.asia/

原标题：golang ci 流水线代码质量扫描集成
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://nHlF.yyctmcg.asia/

原标题：极简 API 网关路由转发实现
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://jDhB.yyctmcg.asia/

原标题：大事务拆分防止连接池耗尽
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://f9d7.yyctmcg.asia/

原标题：golang 系统设计链路追踪架构简单讲解
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://b5Z3.yyctmcg.asia/

原标题：golang redis zset 排行榜业务实现
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://X1Vz.yyctmcg.asia/

原标题：入门实践：简单图片上传预览本地demo
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://TxRv.yyctmcg.asia/

原标题：新手教程：配置SSH‑Key免密访问GitHub
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://PtNr.yyctmcg.asia/

原标题：golang docker 网络模式桥接 host
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://LpJn.yyctmcg.asia/

原标题：性能复盘：数据库回滚日志过大性能影响优化
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://HlFj.yyctmcg.asia/

原标题：golang 系统设计 http 接口基准测试实操示例
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://DhB9.yyctmcg.asia/

?
