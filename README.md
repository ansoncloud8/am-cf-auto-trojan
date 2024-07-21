# am-cf-trojan
这是Cloudflare搭建Trojan节点自建优选域名生成订阅节点免费科学上网

- 官网教程：[AM科技](https://am.809098.xyz)
- YouTube频道：[@AM_CLUB](https://youtube.com/@AM_CLUB)
- Telegram交流群：[@AM_CLUBS](https://t.me/AM_CLUBS)
- 免费订阅：[进群发送关键字: 订阅](https://t.me/AM_CLUBS)

### 变量说明

| 变量名     | 示例                                                         | 备注                                                         |
| ---------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| TOKEN      | auto                                                         | 快速订阅内置节点的订阅路径地址 /auto (支持多元素, 元素之间使用`,`作间隔) |
| HOST       | page-us-17m.pages.dev                                     | 快速订阅内置节点的伪装域名                                   |
| PASSWORD   | amclub                                                    | 快速订阅内置节点的密码                                       |
| PATH       | /?ed=2560                                                    | 快速订阅内置节点的路径信息                                   |
| ADD        | icook.tw:2053#官方优选域名                                   | 对应`addresses`字段 (支持多元素, 元素之间使用`,`作间隔)      |
| ADDAPI     | [https://raw.github.../ipv4.txt](https://raw.githubusercontent.com/ansoncloud8/am-tunnel/dev/ipv4.txt) | 对应`ipv4`字段 (支持多元素, 元素之间使用`,`作间隔)   |
| ADDCSV     | [https://raw.github.../ipv4.csv](https://raw.githubusercontent.com/ansoncloud8/am-tunnel/dev/ipv4.csv) | 对应`ipv4`字段 (支持多元素, 元素之间使用`,`作间隔)   |
| DLS        | 8                                                            | `addressescsv`测速结果满足速度下限                           |
| TGTOKEN    | 6894123456:XXXXXXXXXX0qExVsBPUhHDAbXXXXXqWXgBA               | 发送TG通知的机器人token                                      |
| TGID       | 6946912345                                                   | 接收TG通知的账户数字ID                                       |
| SUBAPI     | api.v1.mk                                                    | clash、singbox等 订阅转换后端                                |
| SUBCONFIG  | [https://raw.github.../ACL4SSR_Online_Full_MultiMode.ini](https://raw.githubusercontent.com/cmliu/ACL4SSR/main/Clash/config/ACL4SSR_Online_Full_MultiMode.ini) | clash、singbox等 订阅转换配置文件                            |
| SUBNAME    | amcftrojan                                             | 订阅生成器名称                                               |
| PS         | 【请勿测速】                                                 | 节点名备注消息                                               |
| PROXYIP    | ts.hpc.tw                                        | 默认分配的ProxyIP, 多ProxyIP将随机分配(支持多元素, 元素之间使用`,`作间隔) |
| CMPROXYIPS | ts.hpc.tw:HK                              | 识别HK后分配对应的ProxyIP(支持多元素, 元素之间使用`,`作间隔) |