# 会议日期—2021-08-10 21:30~23:10

## 讨论摘要



- 无声：
  - 市面上APP功能点比较复杂
  - 界面文字有点小，扩展过多，有点脱离实质
- 小南：
  - todo的重要的目的是养成良好的习惯
  - 有的时候APP成了一个收集箱，和人的联系不够深入
  - 不想app只作为一个缓存，还想app成为一个可以feeback的东西
- ch3ng：
  - 目前的app界面设计比较倾向于IT行业、办公一类
- 25：
  - 希望可以语音记录事项
  - 希望app可以融合极简和多功能两个方面

### 背景知识支持



- 项目的特殊需求
  - 按用户的需求进行扩展或缩减（可以参考即刻（小宇宙、小卖部）插件的使用，使用H5预览等）
- 开源项目特点
  - 可以利用技术栈规避功能改动过大的问题（如非关系型和关系型数据库的差异）
  - 开源项目允许大版本之间不兼容的问题
  - 开源项目，除了bug，可以让大伙一起去改动
  - 开源项目做到最后，根据需求和实际情况的变动，可能会发展成半开源的状态
- 用户登录背景
  - 需要服务器
  - 一个微信第三方平台——如果要微信一键登录
  - 域名——前端开发
  - 服务器代码数据和用户数据——需要保存6个月以上（国家规定）
- docker
  - 对硬件有一定的要求
- 服务器
  - 可以按量付费购买负载均衡
  - 大学生账号申请云服务器开发有优惠
  - 多台服务器，最好都部署在同一个区域
- 登录功能
  - 国家规定——APP需要实名认证，而手机号有这个能力，可作为登录使用，顺便存档
  - 邮箱登录——邮件发送有一定的阈值，一般用于找回密码
- 手机短信验证码
  - 需要设置阈值，否则容易被恶意刷光



### 基础核心功能实现

- 用户登录
  - 用户名、密码登录
  - 手机号+验证码登录
- 待办事项（详见：[项目介绍](./IntroOfProject.md)）
  - 添加事项
  - 编辑事项

### 项目分工



- 后台：spring
  - ch3n90
  - kevin
  - 随他去
  - ShawnKung
  - gkirito
- web前端
  - echo
  - istommao
- 安卓：peterbanban
- IOS：？
- PC：ifun
- UI：Crystal雨婕

### 需要做的事情



- 给项目起个名字（原则：越不实用越通用）
- win11可以安排app放到应用商店中
- 开发项目的时候，不同的功能需要讨论，避免多人饶进同一个功能的实现当中





