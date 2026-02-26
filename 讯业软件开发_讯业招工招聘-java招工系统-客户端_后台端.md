# <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">讯业软件开发/讯业招工招聘 - Java 招工系统（客户端 / 后台端）</font>
<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);"></font>

---

## <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">一、产品概述</font>
<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">本系统是围绕企业招工信息发布、用户报名、拉新返佣场景设计的管理软件，核心流程为：平台发布企业招工信息 → 用户报名应聘 → 用户邀请好友报名 → 好友入职成功 → 邀请人获得返现佣金。系统提供全流程的佣金核算、信息管理能力。  
</font><!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/21487038/1772100440996-b6fff839-ab14-4b8f-b28f-3f1c6896210e.png)<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/jpeg/21487038/1772100440747-dc7ca5d4-4014-4b8d-bcd1-bf2004aae93a.jpeg)<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/jpeg/21487038/1772100441470-174d730d-e4ba-4c7a-8fb3-8aa2d4aabf00.jpeg)<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/jpeg/21487038/1772100440812-55086ec3-68bf-467a-98c0-cb9230e8d744.jpeg)<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/jpeg/21487038/1772100440790-dc4a5053-1b16-44d3-a947-a3284a806e4a.jpeg)

---

## <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">二、系统端口说明</font>
<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">表格</font>

| **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">端口类型</font>** | **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">载体形式</font>** | **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">核心定位</font>** |
| --- | --- | --- |
| <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">用户端</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">微信小程序</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">招工信息浏览、报名、分享、佣金查询</font> |
| <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">后台总管理端</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">PC 网页</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">全平台数据管理、规则配置、审核结算</font> |


---

## <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">三、核心功能明细</font>
### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">（一）登录功能</font>
<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">支持微信小程序获取手机号一键登录，自动完成账号注册 / 登录流程，无需手动填写信息，提升用户操作效率。</font>

### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">（二）转发分享功能</font>
1. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">小程序转发</font>
    - <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">转发封面：自带平台 logo</font>
    - <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">固定配文：“好友喊你来工作，有活一起干，有钱一直赚”</font>
    - <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">自定义补充：支持添加个性化文字（如：长白班，两班倒，国外劳务，工友带）</font>
2. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">职位分享：支持分享当前职位详情页或小程序二维码，便于用户邀请好友参与报名。</font>

### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">（三）首页功能</font>
<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">表格</font>

| **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">模块名称</font>** | **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">功能详情</font>** |
| --- | --- |
| <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">顶部轮播图</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">循环展示 2 个固定画面：</font><font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">1. 好友喊你一起来工作，各种高薪岗位等您来挑</font><font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">2. 推荐有奖：推荐好友入职，达标最高奖励每人 1000 元</font> |
| <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">劳务招聘板块</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">1. 分类：长白班 / 两班倒 / 国外劳务</font><font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">2. 信息展示：工作场地视频、企业简介、工作内容、招聘要求、工作时间、薪资待遇、发薪时间、食宿介绍、年龄要求、其他说明</font><font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">3. 报名功能：用户填写姓名、年龄、电话、居住地址、性别后提交</font><font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">4. 技能培训：预留拓展板块</font><font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">5. 工友带：用户填写姓名、电话、身份证号、用途、申请金额，提交后同步至后台</font><font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">6. 招聘信息管理：后台可设置「招聘中 / 已停招」状态，展示发布时间</font> |
| <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">公司动态展示</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">支持直播待岗、1 分钟内短视频、图文新闻形式展示公司活动与动态</font> |
| <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">品牌标识</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">页面底部展示「logo + 汇聚你我他 幸福千万家」品牌宣传内容</font> |


### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">（四）导航栏功能</font>
<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">设置 3 个核心入口，支持快速切换：</font>

1. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">首页</font>
2. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">推荐有奖</font>
3. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">我的</font>

### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">（五）奖金体系功能</font>
1. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">奖金类型：直推奖、间推奖、月度奖</font>
2. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">发奖规则：工友上班满 1 个月达标后，经后台审核发放奖金</font>
3. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">奖金标准：</font>

<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">表格</font>

| **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">奖金类型</font>** | **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">国内岗位</font>** | **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">国外岗位</font>** | **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">补充说明</font>** |
| --- | --- | --- | --- |
| <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">直推奖</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">200 元</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">600 元</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">-</font> |
| <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">间推奖</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">60 元</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">300 元</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">-</font> |
| <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">月度奖</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">累计达标 10 人及以上：500 元</font><font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">累计达标 50 人：1000 元</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">同国内岗位</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">统计范围为直推 + 间推达标人数</font> |


### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">（六）「我的」模块功能</font>
<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">表格</font>

| **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">子模块</font>** | **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">功能详情</font>** |
| --- | --- |
| <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">平台介绍</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">展示平台核心定位、服务内容等介绍信息</font> |
| <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">个人信息展示</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">显示头像、昵称、手机号</font> |
| <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">邀约数据统计</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">展示直推人数、间推人数</font> |
| <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">奖金明细查询</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">1. 金额汇总：直推奖金、间推奖金、月度奖金总额</font><font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">2. 明细记录：如「直推工友张三，完成达标，获得奖金 600 元」「月度完成达标直推 + 间推 10 人，获得奖金 500 元」</font> |
| <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">记录查询</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">可查看本人的招工报名信息、资金申请信息</font> |


---

## <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">四、系统架构特性</font>
### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">（一）整体架构</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">前后端分离架构，独立开发，符合主流开发模式</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">前端：Vue3 + Vite 为主技术栈，AntdV 为 UI 框架</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">后端：SpringBoot3 为基础，MybatisPlus（数据操作）、Redis（缓存）为核心框架</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">Maven 多模块管理，插件化开发，支持安装 / 卸载 / 升级，降低模块耦合</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">业务模块与 API 抽离，模块间可便捷引用</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">数据库设计规范，字段统一、易于扩展</font>

### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">（二）适配能力</font>
1. **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">数据库支持</font>**
    - <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">主流数据库：MYSQL、ORACLE、SQLSERVER、PGSQL</font>
    - <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">国产数据库：达梦、人大金仓、南大通用、九有、瀚高、虚谷</font>
2. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">中间件支持：中创、宝蓝德、东方通</font>
3. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">操作系统支持：Windows、Linux、国产操作系统</font>
4. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">安全适配：支持国产密码算法加解密，满足等保测评要求</font>

---

## <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">五、系统功能特性</font>
### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">（一）基础功能</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">完善的系统基础能力（组织机构、权限管理、定时任务、系统配置等），避免重复开发</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">多端文件上传：本地文件、阿里云 OSS、腾讯云 COS、MINIO</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">多渠道邮件发送：本地邮件、阿里云邮件、腾讯云邮件</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">多平台短信发送：阿里云短信、腾讯云短信</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">B/C 端双账号认证体系，会话独立治理</font>

### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">（二）审计与监控</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">日志审计：登录日志、操作日志、异常日志全记录</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">系统监控：会话监控、数据源监控、系统资源监控</font>

---

## <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">六、系统安全特性</font>
### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">（一）权限认证</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">基于 SaToken 轻量级 Java 权限框架，支持登录认证、权限认证、单点登录、三方登录、OAuth2.0</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">增强 RBAC 权限设计：资源与接口独立授权，支持按钮级别细粒度授权，界面按钮动态展示</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">API 鉴权：注解式、路由拦截式双重鉴权，防止越界访问</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">数据范围机制：每个接口可配置独立数据范围，精准管控数据访问</font>

### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">（二）数据安全</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">限流防抖、防重复提交，避免脏数据产生</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">密码、手机号、身份证号等敏感信息采用国密算法加密传输 / 存储</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">操作日志使用 SM2 算法进行完整性保护，满足安全审计要求</font>

---

## <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">七、界面特性</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">技术栈：Vue3 + Vite + AntdV，视觉风格清新简洁</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">细节设计：精细化交互，操作友好</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">个性化配置：支持暗黑风格、经典菜单、双排菜单、多页签、目录坞、主题切换</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">统一框架：内置统一网络请求、API 接口拦截框架，开箱即用</font>

---

## <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">联系交流</font>
公司官网：[https://www.xunyeit.com](https://www.xunyeit.com)

案例库：[https://cms.xunyeit.com/](https://cms.xunyeit.com/)

交流微信：  
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/21487038/1772100527823-f173a1e6-39f1-4545-8520-beb1585ae407.png)

