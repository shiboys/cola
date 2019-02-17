#Cola 
## 简介
Cola是一个互联网项目基础平台，着重解决基于SpringBoot+SpringSecurity的认证，也包含其他支撑系统，例如：用户中心、安全中心、消息中心。能够满足所有互联网应用的所有认证需求，并通过基础组件来支撑互联网应用开发。

## 组件列表
| 组件代码 | 组件名称 | 说明 |
| ------ | ------ | ------ |
| cola-auth | 认证组件 | 提供认证服务 |
| cola-user | 用户中心 | 提供用户服务 |
| cola-security | 安全中心 | 提供凭证验证等安全服务 |
| cola-notify | 通知中心 | 提供消息通知服务 |

## 认证模式
- Web Session认证
- Jwt Token认证
- OAuth2 Token认证
## 登录方式
- 账号密码登录
- 短信验证码登录
- 第三方集成登录(支付宝、微信、QQ)
## 可构建平台
- SSO 基于OAuth2构建SSO平台
- OpenAPI 基于OAuth2构建开放平台
## OAuth2扩展
- 通过短信验证码获取Token
- 通过第三方OpenId获取Token
- 通过第三方AuthorizationCode获取Token

## 实例项目
- cola-sample-jwt 基于Jwt进行无Session认证，适用于APP和小程序
- cola-sample-oauth2 基于OAuth2进行无Session认证，适用于APP和小程序，也可以作为开放平台和微服务平台的认证服务
- cola-sample-sso 基于OAuth2构建SSO服务
- cola-sample-web 基于WebSession认证
- cola-sample-social 基于SpringSocial集成第三方登录(需要配置第三方APPID和APPSECRET)