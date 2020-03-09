# 九五云客服WebCall接口规范及定义
本文档主要说明WebCall接口的定义及使用规范，方便开发人员对接实现电话呼叫<br/>
[PDF文档](https://github.com/95ykf/webcall_doc/blob/master/%E4%B9%9D%E4%BA%94%E4%BA%91%E5%AE%A2%E6%9C%8DWebCall%E6%8E%A5%E5%8F%A3%E8%A7%84%E8%8C%83%E5%8F%8A%E5%AE%9A%E4%B9%89.pdf)
# 适用范围
该文档中所有接口仅适用与由服务端发起调用API接口，请不要在客户端如WEB前端页面、小程序和手机应用等中调用，否则会存在鉴权码泄漏的风险。
# 接入流程
1. 申请企业账户；
2. 开发者提供异步通知地址；
3. 创建应用，分配client_id和client_secret，用于请求授权；
4. 根据接口开发业务逻辑；

