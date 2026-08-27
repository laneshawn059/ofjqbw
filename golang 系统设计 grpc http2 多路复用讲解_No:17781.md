最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.dtxuzri.asia/blog/6999578.sHtMl

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.dtxuzri.asia/blog/5679697.sHtMl

原标题：golang 系统设计大流量削峰处理方案
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://book.dtxuzri.asia/blog/1597706.sHtMl

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.dtxuzri.asia/blog/6149112.sHtMl

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.dtxuzri.asia/blog/4096674.sHtMl

原标题：golang docker volume 数据持久化
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://book.dtxuzri.asia/blog/6481626.sHtMl

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://book.dtxuzri.asia/blog/7835076.sHtMl

原标题：golang 分布式锁 redis 实现
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.dtxuzri.asia/blog/9672710.sHtMl

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://book.dtxuzri.asia/blog/5824330.sHtMl

原标题：Practice：实现请求重试组件支持退避策略
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://book.dtxuzri.asia/blog/1773987.sHtMl

原标题：实战：Nginx实现文件限速下载配置实践
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.dtxuzri.asia/blog/2002884.sHtMl

原标题：golang 系统设计分布式锁选型对比
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://book.dtxuzri.asia/blog/9620834.sHtMl

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.dtxuzri.asia/blog/1453202.sHtMl

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.dtxuzri.asia/blog/3069723.sHtMl

原标题：灰度发布策略服务平滑升级
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://book.dtxuzri.asia/blog/8092319.sHtMl

原标题：部署复盘：静态资源版本哈希缓存策略
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://book.dtxuzri.asia/blog/3107995.sHtMl

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://book.dtxuzri.asia/blog/6367859.sHtMl

原标题：golang gorm 批量插入性能调优
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://book.dtxuzri.asia/blog/9256232.sHtMl

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://book.dtxuzri.asia/blog/5848420.sHtMl

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://book.dtxuzri.asia/blog/8464731.sHtMl

原标题：vite 项目配置与构建提速技巧
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.dtxuzri.asia/blog/2154645.sHtMl

原标题：序列化版本不一致解析失败
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://book.dtxuzri.asia/blog/3172748.sHtMl

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.dtxuzri.asia/blog/9485566.sHtMl

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.dtxuzri.asia/blog/9536099.sHtMl

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://book.dtxuzri.asia/blog/5600262.sHtMl

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.dtxuzri.asia/blog/5220476.sHtMl

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://book.dtxuzri.asia/blog/9616686.sHtMl

原标题：从零学习基础的接口请求与参数处理
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://book.dtxuzri.asia/blog/6186659.sHtMl

原标题：golang yaml 解析配置加载实操
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.dtxuzri.asia/blog/5056449.sHtMl

原标题：golang 系统设计回调重试幂等完整处理
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.dtxuzri.asia/blog/9133424.sHtMl

原标题：golang 简易埋点日志上报实现
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.dtxuzri.asia/blog/4674828.sHtMl

原标题：golang k8s helm chart 简单编写
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://book.dtxuzri.asia/blog/6208941.sHtMl

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.dtxuzri.asia/blog/4789208.sHtMl

原标题：Practice：实现IP黑名单拦截中间件实践
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.dtxuzri.asia/blog/0866675.sHtMl

原标题：业务幂等键设计防重复逻辑
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://book.dtxuzri.asia/blog/4085122.sHtMl

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.dtxuzri.asia/blog/6480852.sHtMl

原标题：Practice：模拟第三方接口超时服务降级验证
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://book.dtxuzri.asia/blog/8584084.sHtMl

原标题：golang 系统设计配置灰度下发简单实现思路
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://book.dtxuzri.asia/blog/1014856.sHtMl

原标题：Hands‑on：简易网关路由转发组件开发
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://book.dtxuzri.asia/blog/5154986.sHtMl

原标题：golang 系统设计 canary 金丝雀部署实操
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.dtxuzri.asia/blog/5077960.sHtMl


二、踩坑排错｜Troubleshooting
原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://book.dtxuzri.asia/blog/2786635.sHtMl

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.dtxuzri.asia/blog/4249780.sHtMl

原标题：Hands‑on：简易配置中心本地原型实现
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://book.dtxuzri.asia/blog/3622694.sHtMl

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.dtxuzri.asia/blog/9475105.sHtMl

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://book.dtxuzri.asia/blog/5212538.sHtMl

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.dtxuzri.asia/blog/4517710.sHtMl

原标题：Redis 分布式锁高并发安全实现
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.dtxuzri.asia/blog/1154049.sHtMl

原标题：eslint prettier 代码规范落地
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.dtxuzri.asia/blog/8636823.sHtMl

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://book.dtxuzri.asia/blog/0349498.sHtMl

原标题：golang 系统设计异步化改造业务流程思路
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.dtxuzri.asia/blog/1297597.sHtMl

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.dtxuzri.asia/blog/4865468.sHtMl

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.dtxuzri.asia/blog/8950097.sHtMl

原标题：集成测试业务流程编写示例
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://book.dtxuzri.asia/blog/1937094.sHtMl

原标题：实战项目：WSL开发环境完整配置实操
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://book.dtxuzri.asia/blog/2677990.sHtMl

原标题：从零搭建本地开发环境完整教程
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.dtxuzri.asia/blog/2949148.sHtMl

原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://book.dtxuzri.asia/blog/8238931.sHtMl

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://book.dtxuzri.asia/blog/3356430.sHtMl

原标题：golang k8s job 一次性任务执行
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://book.dtxuzri.asia/blog/5503794.sHtMl

原标题：优化实践：多级缓存减少下游服务调用压力
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://book.dtxuzri.asia/blog/5286440.sHtMl

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://book.dtxuzri.asia/blog/6097534.sHtMl

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.dtxuzri.asia/blog/4377768.sHtMl

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.dtxuzri.asia/blog/9261928.sHtMl

原标题：避坑：版本升级之后项目直接无法启动
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.dtxuzri.asia/blog/4936660.sHtMl

原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.dtxuzri.asia/blog/4867031.sHtMl

原标题：Redis 热点 key 拆分降低集群压力
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://book.dtxuzri.asia/blog/2637951.sHtMl

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://book.dtxuzri.asia/blog/7683705.sHtMl

原标题：golang 系统设计 commit 提交规范约定
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://book.dtxuzri.asia/blog/0483085.sHtMl

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://book.dtxuzri.asia/blog/3802594.sHtMl

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://book.dtxuzri.asia/blog/6843030.sHtMl

原标题：Architecture：监控告警架构避免告警风暴设计
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://book.dtxuzri.asia/blog/2221299.sHtMl

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://book.dtxuzri.asia/blog/9402860.sHtMl

原标题：Practice：实现异步回调处理通用组件封装
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://book.dtxuzri.asia/blog/7127176.sHtMl

原标题：项目构建脚本编译打包解析
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.dtxuzri.asia/blog/9667680.sHtMl

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://book.dtxuzri.asia/blog/9885079.sHtMl

原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://book.dtxuzri.asia/blog/5239362.sHtMl

原标题：零基础理解JSON、XML数据格式处理
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://book.dtxuzri.asia/blog/9291522.sHtMl

原标题：Practice：实现接口签名、验签完整示例代码
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.dtxuzri.asia/blog/8585427.sHtMl

原标题：方案设计：短链接系统完整架构方案拆解
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.dtxuzri.asia/blog/3715251.sHtMl

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://book.dtxuzri.asia/blog/1934839.sHtMl

原标题：系统文件描述符上限调大
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.dtxuzri.asia/blog/3183548.sHtMl

三、实战开发｜Practice
原标题：部署实践：Nginx高可用配置方案实践
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.dtxuzri.asia/blog/0034089.sHtMl

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://book.dtxuzri.asia/blog/6915664.sHtMl

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.dtxuzri.asia/blog/3198372.sHtMl

原标题：golang redis zset 排行榜业务实现
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://book.dtxuzri.asia/blog/9578754.sHtMl

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://book.dtxuzri.asia/blog/8488627.sHtMl

原标题：开发记录：接口请求日志记录完整中间件实现
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.dtxuzri.asia/blog/7553378.sHtMl

原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.dtxuzri.asia/blog/6332046.sHtMl

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://book.dtxuzri.asia/blog/1864414.sHtMl

原标题：Hands‑on：简易配置热更新组件开发实践
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.dtxuzri.asia/blog/0801915.sHtMl

原标题：Architecture：鉴权授权系统架构设计思路
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.dtxuzri.asia/blog/2356418.sHtMl

原标题：Architecture：文件处理服务架构大文件内存规避
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.dtxuzri.asia/blog/2634270.sHtMl

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.dtxuzri.asia/blog/4965158.sHtMl

原标题：DevOps：容器健康探针livenessreadiness配置
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.dtxuzri.asia/blog/8155522.sHtMl

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.dtxuzri.asia/blog/7940690.sHtMl

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.dtxuzri.asia/blog/9264960.sHtMl

原标题：短信服务封装失败自动重试
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://book.dtxuzri.asia/blog/1239902.sHtMl

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.dtxuzri.asia/blog/6915228.sHtMl

原标题：快速入门GraphQL基础查询语法示例
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.dtxuzri.asia/blog/9192873.sHtMl

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://book.dtxuzri.asia/blog/2715168.sHtMl

原标题：golang 系统设计本地缓存更新失效方案实现
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.dtxuzri.asia/blog/2734167.sHtMl

原标题：golang 系统设计接口幂等架构设计
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://book.dtxuzri.asia/blog/3489936.sHtMl

原标题：从零学习基础的接口请求与参数处理
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://book.dtxuzri.asia/blog/5983642.sHtMl

原标题：零基础理解模块化与组件化基础思想
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://book.dtxuzri.asia/blog/0275119.sHtMl

原标题：golang 系统设计架构图绘图工具选型对比
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://book.dtxuzri.asia/blog/9668336.sHtMl

原标题：golang grpc protobuf 开发实操
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.dtxuzri.asia/blog/4846532.sHtMl

原标题：安全复盘：定时任务权限过大风险管控
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://book.dtxuzri.asia/blog/0975084.sHtMl

原标题：golang 系统设计内存瓶颈定位优化思路
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://book.dtxuzri.asia/blog/6483456.sHtMl

原标题：Practice：实现请求重试组件支持退避策略
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.dtxuzri.asia/blog/1107823.sHtMl

原标题：无用对象回收抑制内存上涨
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://book.dtxuzri.asia/blog/3786018.sHtMl

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.dtxuzri.asia/blog/0815218.sHtMl

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.dtxuzri.asia/blog/7424206.sHtMl

原标题：性能调优：MySQL查询性能优化实战清单
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://book.dtxuzri.asia/blog/0655015.sHtMl

原标题：调优方案：Docker容器内核参数性能调优
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.dtxuzri.asia/blog/9390508.sHtMl

原标题：前端防抖节流高频事件处理
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://book.dtxuzri.asia/blog/1889850.sHtMl

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.dtxuzri.asia/blog/6719123.sHtMl

原标题：golang 系统设计 webhook 回调处理架构
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.dtxuzri.asia/blog/7020268.sHtMl

原标题：包管理器依赖冲突解决方案
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://book.dtxuzri.asia/blog/4138340.sHtMl

原标题：golang 系统信号信号量处理
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.dtxuzri.asia/blog/6431384.sHtMl

原标题：golang mysql 分表自增 id 方案
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.dtxuzri.asia/blog/0093416.sHtMl

原标题：golang 系统设计网关请求日志 traceId 透传实现
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.dtxuzri.asia/blog/5300661.sHtMl

四、架构设计｜Architecture
原标题：环境变量不生效问题修复
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.dtxuzri.asia/blog/4542400.sHtMl

原标题：golang 系统设计开发环境本地调试最佳实践
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://book.dtxuzri.asia/blog/0131939.sHtMl

原标题：部署实践：数据库迁移脚本版本管理实践
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://book.dtxuzri.asia/blog/6945527.sHtMl

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://book.dtxuzri.asia/blog/6134330.sHtMl

原标题：Performance：避免全表扫描索引失效场景汇总
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.dtxuzri.asia/blog/7887979.sHtMl

原标题：gRPC 服务端客户端入门示例
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://book.dtxuzri.asia/blog/2647750.sHtMl

原标题：golang 分页查询封装通用工具
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://book.dtxuzri.asia/blog/8057321.sHtMl

原标题：开源实践：给开源项目写单元测试贡献代码
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.dtxuzri.asia/blog/6644662.sHtMl

原标题：快速入门容器基础概念，理解镜像与容器
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.dtxuzri.asia/blog/7401470.sHtMl

原标题：Practice：实现请求ID透传全链路日志实践
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.dtxuzri.asia/blog/5932558.sHtMl

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://book.dtxuzri.asia/blog/5600153.sHtMl

原标题：golang redis 主从复制哨兵原理
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://book.dtxuzri.asia/blog/6724289.sHtMl

原标题：vite 插件开发自定义构建逻辑
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.dtxuzri.asia/blog/7199834.sHtMl

原标题：部署实践：告警收敛避免告警风暴配置
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://book.dtxuzri.asia/blog/6084591.sHtMl

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.dtxuzri.asia/blog/8967532.sHtMl

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.dtxuzri.asia/blog/7851639.sHtMl

原标题：代理 HTTPS 证书访问异常处理
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.dtxuzri.asia/blog/8795465.sHtMl

原标题：golang 系统设计数据库索引设计方法论
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://book.dtxuzri.asia/blog/3656895.sHtMl

?
