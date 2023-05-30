### 参考链接
查阅链接:
- 爱奇艺落地实践 https://apisix.apache.org/zh/blog/2021/09/07/iqiyi-usercase/
- ABAC模型鉴权 http://coding.idealworld.group/2021/09/03/apisix-plugin-development/

### 请求鉴权
- 自定义鉴权方式,现有鉴权不贴合云直通实际应用
    - 平台请求网关验签
    - 请求API权限验证(联动管理后台权限同步)
- 参考 https://apisix.apache.org/zh/blog/2021/09/07/how-to-use-apisix-auth/

### 插件开发
- Java开发
    - https://segmentfault.com/a/1190000040231967

### 云直通Kong应用
- 自定义API鉴权
- API限流
- 路由转发Request-id生成
- 灰度

### APISIX 逻辑灰度
https://apisix.apache.org/zh/blog/2022/06/14/how-mse-supports-canary-release-with-apache-apisix/#%E4%B8%9A%E5%8A%A1%E5%9C%BA%E6%99%AF

### 云直通应用下差异化比对(KONG VS APISIX)

####插件开发
- APISIX在Lua基础上同时支持多语言插件开发
    - https://apisix.apache.org/zh/docs/apisix/external-plugin/
    - Java
    - GO
    - Python

- 同基于OpenResty 技术
- 系统保护定义接口限速
- 故障节点摘取
