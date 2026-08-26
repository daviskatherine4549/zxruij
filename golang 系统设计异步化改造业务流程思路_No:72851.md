最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计异步化改造业务流程思路
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.o78ojz.asia/arts/851507.Doc

原标题：Practice：模拟磁盘满，验证服务降级表现
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.o78ojz.asia/arts/781703.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.o78ojz.asia/arts/784584.Doc

原标题：golang 系统设计大事务拆分实战思路
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.o78ojz.asia/arts/183552.Doc

原标题：golang 系统设计短链接服务实现思路
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.o78ojz.asia/arts/936558.Doc

原标题：golang 系统设计 commit 提交规范约定
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.o78ojz.asia/arts/607287.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.o78ojz.asia/arts/673217.Doc

原标题：golang etcd 配置中心简单使用
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.o78ojz.asia/arts/576395.Doc

原标题：Nginx 请求头大小上限调整
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.o78ojz.asia/arts/458395.Doc

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.o78ojz.asia/arts/642077.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.o78ojz.asia/arts/699149.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.o78ojz.asia/arts/996384.Doc

原标题：Hands‑on：实现WebSocket聊天室完整前后端demo
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.o78ojz.asia/arts/481322.Doc

原标题：golang 日志 zap 结构化日志实践
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.o78ojz.asia/arts/375054.Doc

原标题：golang 系统设计配置敏感信息加密存储方案
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.o78ojz.asia/arts/043395.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.o78ojz.asia/arts/750544.Doc

原标题：golang cpu pprof 性能分析实操
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.o78ojz.asia/arts/995584.Doc

原标题：排错：前端缓存304异常更新不及时
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.o78ojz.asia/arts/381544.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.o78ojz.asia/arts/592677.Doc

原标题：Architecture：大文件上传下载系统架构设计
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.o78ojz.asia/arts/134595.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.o78ojz.asia/arts/010397.Doc

原标题：golang 系统设计状态字段枚举约束设计思路
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.o78ojz.asia/arts/600168.Doc

原标题：从零搭建本地数据库开发环境
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.o78ojz.asia/arts/630047.Doc

原标题：Hands‑on：简易链路追踪原型开发实践
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.o78ojz.asia/arts/895718.Doc

原标题：日志敏感信息脱敏泄露防护
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.o78ojz.asia/arts/580039.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.o78ojz.asia/arts/346341.Doc

原标题：golang github actions 多平台构建
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.o78ojz.asia/arts/362929.Doc

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.o78ojz.asia/arts/532048.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.o78ojz.asia/arts/549625.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.o78ojz.asia/arts/110844.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.o78ojz.asia/arts/506230.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.o78ojz.asia/arts/234096.Doc

原标题：golang 大文件读取内存优化
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.o78ojz.asia/arts/858922.Doc

原标题：golang docker compose 依赖启动顺序
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.o78ojz.asia/arts/883994.Doc

原标题：golang http 代理客户端配置
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.o78ojz.asia/arts/688658.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.o78ojz.asia/arts/663555.Doc

原标题：API 接口调试与异常处理实战
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.o78ojz.asia/arts/488963.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.o78ojz.asia/arts/352777.Doc

原标题：新手教程：本地环境变量配置全流程
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.o78ojz.asia/arts/443757.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.o78ojz.asia/arts/721037.Doc


二、踩坑排错｜Troubleshooting
原标题：开发记录：表单参数校验统一中间件实现
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.o78ojz.asia/arts/606166.Doc

原标题：程序日志分级输出规范实践
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.o78ojz.asia/arts/374255.Doc

原标题：快速入门容器基础概念，理解镜像与容器
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.o78ojz.asia/arts/538296.Doc

原标题：nodejs 事件循环机制完整讲解
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.o78ojz.asia/arts/554137.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.o78ojz.asia/arts/124171.Doc

原标题：程序预加载加快服务启动速度
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.o78ojz.asia/arts/721803.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.o78ojz.asia/arts/310455.Doc

原标题：golang 优雅关闭 grpc 服务示例
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.o78ojz.asia/arts/566226.Doc

原标题：golang goroutine 协程基础实操
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.o78ojz.asia/arts/347500.Doc

原标题：golang redis 发布订阅简单示例
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.o78ojz.asia/arts/114572.Doc

原标题：golang redis 大 key 识别处理方案
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.o78ojz.asia/arts/595539.Doc

原标题：Security：Docker镜像安全扫描漏洞修复
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.o78ojz.asia/arts/936528.Doc

原标题：快速上手简单信号处理脚本编写
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.o78ojz.asia/arts/851821.Doc

原标题：golang redis 批量 pipeline 实践
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.o78ojz.asia/arts/598822.Doc

原标题：golang 系统设计监控告警阈值设置思路
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.o78ojz.asia/arts/009499.Doc

原标题：golang es 高亮搜索结果实现方案
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.o78ojz.asia/arts/663300.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.o78ojz.asia/arts/520135.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.o78ojz.asia/arts/832094.Doc

原标题：方案设计：分布式锁失效风险架构层面规避
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.o78ojz.asia/arts/547433.Doc

原标题：axios 二次封装请求拦截处理
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.o78ojz.asia/arts/843324.Doc

原标题：前端打包分包加载提速方案
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.o78ojz.asia/arts/041480.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.o78ojz.asia/arts/592794.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://wiki.o78ojz.asia/arts/477480.Doc

原标题：golang 配置文件多环境加载
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.o78ojz.asia/arts/730290.Doc

原标题：大文件导出内存溢出防护
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.o78ojz.asia/arts/143983.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.o78ojz.asia/arts/176124.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.o78ojz.asia/arts/140493.Doc

原标题：从零搭建简单CLI命令行工具
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.o78ojz.asia/arts/006066.Doc

原标题：golang 系统设计内部服务调用超时设置要点
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.o78ojz.asia/arts/335865.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.o78ojz.asia/arts/726804.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.o78ojz.asia/arts/591666.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.o78ojz.asia/arts/769942.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.o78ojz.asia/arts/973757.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.o78ojz.asia/arts/055905.Doc

原标题：golang 系统设计服务优雅停机完整流程
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.o78ojz.asia/arts/158837.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.o78ojz.asia/arts/897117.Doc

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.o78ojz.asia/arts/627787.Doc

原标题：nodejs 中间件模式原理剖析
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.o78ojz.asia/arts/905302.Doc

原标题：golang 系统设计 monorepo 仓库管理方案
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.o78ojz.asia/arts/198677.Doc

原标题：跨平台换行符统一异常修复
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.o78ojz.asia/arts/839436.Doc

三、实战开发｜Practice
原标题：golang ci 流水线代码质量扫描集成
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.o78ojz.asia/arts/581167.Doc

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.o78ojz.asia/arts/087533.Doc

原标题：golang 系统设计日志脱敏防止信息泄露
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.o78ojz.asia/arts/459138.Doc

原标题：golang 静态编译缩小镜像体积
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://wiki.o78ojz.asia/arts/654485.Doc

原标题：Performance：大事务拆分，减少锁持有时间
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.o78ojz.asia/arts/303929.Doc

原标题：nodejs 脚手架工具开发完整教程
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.o78ojz.asia/arts/958166.Doc

原标题：运维笔记：备份策略数据库定时备份脚本
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.o78ojz.asia/arts/787798.Doc

原标题：静态资源 404 路径打包修复
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.o78ojz.asia/arts/303179.Doc

原标题：golang 结构体 json 序列化坑点
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.o78ojz.asia/arts/784368.Doc

原标题：内存广播本地进程消息通知
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.o78ojz.asia/arts/962000.Doc

原标题：排错：GitLFS大文件推送失败完整排障
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.o78ojz.asia/arts/591643.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.o78ojz.asia/arts/480533.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.o78ojz.asia/arts/811228.Doc

原标题：数据库主从延迟业务兼容处理
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.o78ojz.asia/arts/755244.Doc

原标题：文件监控服务自动重启开发
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.o78ojz.asia/arts/414609.Doc

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.o78ojz.asia/arts/085596.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.o78ojz.asia/arts/925518.Doc

原标题：golang ip 限流黑名单实现方案
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.o78ojz.asia/arts/501413.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.o78ojz.asia/arts/543748.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.o78ojz.asia/arts/347531.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.o78ojz.asia/arts/442987.Doc

原标题：golang k8s liveness readiness 探针
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.o78ojz.asia/arts/020257.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.o78ojz.asia/arts/680621.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.o78ojz.asia/arts/077326.Doc

原标题：OpenSource：开源项目许可证License选型指南
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.o78ojz.asia/arts/649896.Doc

原标题：golang k8s helm chart 简单编写
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.o78ojz.asia/arts/373283.Doc

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.o78ojz.asia/arts/573997.Doc

原标题：WebSocket 断线重连稳定优化
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.o78ojz.asia/arts/676284.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.o78ojz.asia/arts/796323.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.o78ojz.asia/arts/357033.Doc

原标题：golang prometheus histogram 指标
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.o78ojz.asia/arts/014638.Doc

原标题：Practice：实现请求重试组件支持退避策略
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.o78ojz.asia/arts/253963.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.o78ojz.asia/arts/155517.Doc

原标题：方案设计：多租户系统架构三种实现模式对比
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.o78ojz.asia/arts/228445.Doc

原标题：golang 令牌桶限流中间件 gin
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.o78ojz.asia/arts/768465.Doc

原标题：CI 构建缓存加速编译速度
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.o78ojz.asia/arts/411614.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.o78ojz.asia/arts/381132.Doc

原标题：DevOps：制品仓库管理二进制产物版本
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.o78ojz.asia/arts/428943.Doc

原标题：Debug：多线程共享可变变量产生脏数据
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://wiki.o78ojz.asia/arts/048431.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.o78ojz.asia/arts/667908.Doc

四、架构设计｜Architecture
原标题：入门实践：简易导出导入文件功能实现
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.o78ojz.asia/arts/141743.Doc

原标题：golang 系统设计告警渠道钉钉邮件企业微信集成
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.o78ojz.asia/arts/823306.Doc

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.o78ojz.asia/arts/170801.Doc

原标题：golang 系统设计数据库扩容几种方式
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.o78ojz.asia/arts/304622.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://wiki.o78ojz.asia/arts/978510.Doc

原标题：Practice：实现熔断降级组件简单原型代码
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.o78ojz.asia/arts/282471.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.o78ojz.asia/arts/571454.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.o78ojz.asia/arts/591823.Doc

原标题：开发复盘：统一错误码体系设计落地实践
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.o78ojz.asia/arts/938036.Doc

原标题：Git 仓库瘦身加快克隆下载速度
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.o78ojz.asia/arts/647252.Doc

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.o78ojz.asia/arts/425417.Doc

原标题：macOS 脚本执行权限开启
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.o78ojz.asia/arts/085819.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://wiki.o78ojz.asia/arts/158781.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.o78ojz.asia/arts/998063.Doc

原标题：Hands‑on：实现WebSocket聊天室完整前后端demo
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.o78ojz.asia/arts/043770.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.o78ojz.asia/arts/996798.Doc

原标题：方案对比：同步事务vs事务消息最终一致性
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.o78ojz.asia/arts/778723.Doc

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.o78ojz.asia/arts/927506.Doc

?
