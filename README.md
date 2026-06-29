# 台球综合盘
台球综合盘 TG:dszzz566

项目简介
台球赛事局 是基于 ThinkPHP 6 + FastAdmin（YFCMF-TP6） 二次开发的垂直行业系统。核心业务是 中式台球赛事自营投注（球员对阵、实时比分、多玩法盘口、直播观赛），同时集成 第三方游戏 API（NG / api-bet），在 H5 端提供体育、真人、电子、电竞、彩票、棋牌等综合盘入口。

系统采用 前后端分离 架构：

管理后台：FastAdmin 传统后台，负责赛事、会员、资金、返水、客服等运营
会员 H5：Vue 3 + Vite 单页应用，构建产物输出到 public/h5/
移动端：Capacitor 6 打包 Android APK（vue源码/android/）
功能亮点
台球自营盘
模块	说明
球员管理
球员资料、头像、批量种子数据
赛事管理
A/B 对阵、开盘时间、赛况（可投注 / 比赛中 / 已结束）
多玩法盘口
独赢（含让分）、大小、单双，JSON 结构化存储
实时比分
H5 轮询比分，后台录入后自动结算
赛事直播
支持 HLS（.m3u8）直播流，H5 内嵌播放
注单管理
投注、结算、流局退还、流水冲正
随机对战
后台一键生成随机球员对阵
会员与资金
模块	说明
会员体系
注册 / 登录 / Token 鉴权，与后台管理员账号完全独立
充值审核
微信 / 支付宝 / USDT 等多通道，后台人工审核入账
提现审核
绑定收款方式，流水倍数校验，后台审核出款
提款密码
独立提款密码，与登录密码分离
资金流水
余额变动明细
营销与分销
模块	说明
邀请分销
三级返佣，按下级台球投注本金比例结算
返水系统
台球自营 + 接口游戏分类返水，自动入账
活动公告
活动图文、首页轮播、弹窗公告
综合娱乐盘（NG 三方）
模块	说明
游戏大厅
体育 / 真人 / 电子 / 电竞 / 彩票 / 棋牌分类入口
钱包划转
主钱包 ↔ 三方平台额度转入转出
注单同步
上游注单导入、返水计算
平台开关
后台配置可用平台、禁用列表
客服系统
模块	说明
多通道客服
综合 / 充值 / 提现 / VIP 等通道
实时会话
H5 聊天 + 后台回复，未读计数
技术栈
层级	技术
后端框架
ThinkPHP 6、FastAdmin / YFCMF-TP6
数据库
MySQL 5.7+ / 8.0（表前缀 fa_）
管理后台
Bootstrap、AdminLTE、RequireJS
H5 前端
Vue 3.4、Vue Router 4、Vite 5
直播播放
hls.js
移动端
Capacitor 6 + Android Gradle
其他
PHPMailer、PhpSpreadsheet、Endroid QR Code

<img width="429" height="932" alt="QQ20260630-034427" src="https://github.com/user-attachments/assets/601639ac-f15c-4fa1-9887-a77b23881cf0" />
<img width="432" height="930" alt="QQ20260630-034413" src="https://github.com/user-attachments/assets/a881680e-4517-4f87-a9bf-e8dec7375ac1" />
<img width="430" height="932" alt="QQ20260630-034405" src="https://github.com/user-attachments/assets/b5720576-f932-40bd-acfb-972e8dfb2873" />
<img width="429" height="932" alt="QQ20260630-034356" src="https://github.com/user-attachments/assets/6b461583-e567-4a84-96c1-fdc68ba6950a" />
<img width="431" height="931" alt="QQ20260630-034344" src="https://github.com/user-attachments/assets/cf4a26a2-5c91-4df2-ad46-40f9f1c7b564" />
<img width="429" height="932" alt="QQ20260630-034439" src="https://github.com/user-attachments/assets/63813483-5c93-4cdc-bae4-a51860adb8a2" />



演示：https://tq.2t21.my/h5/  


