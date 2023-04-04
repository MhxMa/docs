# 洛谷更新日志

## 2023 年

### 3 月

**帮助中心**  
基于 Docusaurus 构建洛谷帮助中心(<https://help.luogu.com.cn>)，涵盖洛谷主站、网校等产品的帮助文档以及洛谷社区以及学术规范文档。

**后端**  
针对大量并发连接的场景进行了针对性优化，内部部分模块执行效率得到提高。

**洛谷开放平台**  
API v1 开始测试，具体详见<https://docs.lgapi.cn/open>  
目前正在限量邀请测试中。

## 2022 年

### 12 月  

**支付网关**  
Refactor with PHP 8.2 & Symfony 6.2 & Lentille

**数据库**  
数据库从 RDS MySQL 5.6 迁移并升级至PolarDB MySQL引擎 8.0

### 11 月

**WEB 后端**  
云服务器架构更新（原架构从 2017 年至今未重大变更），使用新一代高线程虚拟机并且更换底层系统，重写负载均衡系统等。由于此次后端整体架构更新重大，细节很多，可能还有部分 bug 存在，开发组会尽快修复。

### 10 月

**个人中心**  
优化做题记录显示，增加按难度分组显示已通过题目

**题库**  
ATcoder 题号变更

**题目列表、题目详情**  
超长题目名称显示优化  

### 5 月

**题目详情**  
复制题面 Markdown 功能

**个人资料**  
新前端页面上线个人浮动卡片  
个人中心页面的昵称后面增加称号和奖项认证图标

**洛谷网校**

- LILS 界面优化，增加提示
- 课程详情页面优化调整课程目录列表为双行，增加进入课时的按钮。

## 2021 年

### 12 月

**冬日绘版**

- 更新页面
- 重写后端，使用 token 作为 api 唯一验证方式

**洛谷网校**  

- 支持 IPv6 访问
- 后端架构更新
- 启用新版后台

**支付网关**  

- 开票信息可留言备注

### 8 月

**支付网关**

- 支持手机微信内支付

**网校**

- 优化课程包回放有效期显示，现在购买课程前就显示。

### 7 月

**题库**

- 新增“入门与面试”题库，序号为 B 开头，如遇到题目问题可[反馈至此帖](https://www.luogu.com.cn/discuss/show?postid=325040)
- 新增“洛谷月赛”标签，可在来源中选中
- 题库筛选器取消默认折叠

### 6 月

**洛谷网校**  

- 课程详情页面翻新
- lils课程页面修复了些bug

### 5 月

**视频内容**

- md 格式内容现在支持嵌入 bilibili 视频，[语法格式](https://www.luogu.com.cn/paste/l9faoe0v)  
- 推荐在题解内使用，其他地方内请合理使用，不要对他人造成困扰。

**洛谷网校**

- 学习中心上线新列表页面，之后还有支持筛选功能。
- 课程详情内的课程目录优化，添加视频课程的状态信息。  

### 4 月

**新版标签：**  

- 重写底层逻辑，从原本固定的数据格式切换成可自由扩展的数据格式。
- 前端标签选择器更新，应用于题目列表筛选、题目编辑。
- 标签颜色调整：调整算法标签、来源标签的颜色。

### 2 月  

团队文件：团队新增文件存储空间，所有成员可上传文件，团队管理员可管理文件。

### 1 月

题目详情页：收藏按钮升级为加入题单按钮  ，可以将一个题目很方便的加入到自己可以管理的题单中。

题单详情页：转存题单现在可以直接转存到所处团队（需要有对应权限），同时可以支持排序

## 2020 年  

### 12 月

题目列表：根据用户反馈，增加“暂未评定”的难度筛选项

验证码邮件：更新了邮件的模板  

主页：更新友情链接内容

团队：

- 题目、作业、题单增加排序与搜索功能。  
- 优化比赛、作业排行榜以及导出表格的用户备注显示。

编辑界面：题目、比赛、题单、作业增加未保存时的提醒功能，防止误操作导致的内容未保存直接退出页面。  

记录详情：fix code overflow  

### 11 月

团队：团队作业排行榜默认显示备注名，光标移过去时显示UID和用户名。

个人中心：在关注页面新增黑名单列表，现在你可以知道你一共拉黑了多少人了  

以及一些零碎的bug修复。

### 10 月  

RMJ：Luogu上已有的atcoder题目可以提交评测了。  

个人私信：现在发送消息后会自动滚动到最底了。  

比赛排行：可以显示自己的成绩了，排名暂时不行。  

高级团队：高级成员管理上线，并且修复了一些bug。  

### 9 月  

比赛排行：修复因为比赛临时延长时间带来的一血判断问题，目前比赛最多可临时延长1天，超过1天还是会出现一血被顶替的问题。

洛谷有题：升级网站后端依赖组件版本，解决稳定性问题。  

主站后端：修复连接性问题。  

高级团队：高级团队相关功能。团队主负责人可以在团队设置内开通/试用高级团队功能。  

团队作业：新版作业正式上线，旧版数据将保留至2020年底，请及时迁移。

支付网关：将网校支付功能抽出，独立。  

成员管理：现在可以正常显示申请者的验证信息了。  

题目列表：修复通过率toptip显示问题。

评测机：禁止`pragmas`头文件，在比赛中禁止用户开启 O2 优化（由举办者统一设置）

### 8 月  

个人设置：新增个人博客后台入口

编辑题目：新增帮助信息 、修复部分题目数据上传bug

复制题目：允许在编辑题目时复制题目，高级团队允许复制公共题目的数据。  

评测机：修复清理环境的进程执行完毕后无法释放pid的bug  

讨论区：增加验证码，限制频繁发帖行为。之后验证码的出现逻辑会更合理，减少对正常用户的干扰。

博客：some fix，现在博主可查看隐藏的文章了

LFE：Add worker edition VueHighlightJS、组件样式更新。

后端：修复部分cookie问题。

团队：修复成员编辑无效的问题、优化系统通知信息。

奖项认证：  
    - 优化OIerDB，对学校数据优化合并拆分，应该解决了9成7的学校错误问题
    - 奖项列表按年份排序  

搜索页面：修复了些奇怪的错误

倒计时：根据官方修正CSP的举办日期

Tabs交互动画：添加了Selected-hover效果

### 7 月

博客：修复部分主题bug

洛谷推荐：推荐系统绝赞上线

LFE：更新了一些组件  

LILS：系统更新，入门课程准备封测（有意者联系kkk）

RMJ：临时修复CF接口，但不保证稳定性。  

评测机：

- 优化评测机稳定性，解决部分评测机波动的情况。  
- 更新rustc为nightly版本。

个人菜单：修正 log out 文案及图标。  

移动端：调整页面样式，提升阅读浏览体验。

- 对除首页与讨论区之外的所有页面隐藏footer。
- 优化tinyheader排版。

ListBlock：数字强制使用tabular-nums.

团队作业：上线新版团队作业，保留旧版链接。旧版作业待转换or也可以手动搬运。

### 6 月

全局页面：更改了英文字体

题目编辑：允许在使用subtask的时候选择子任务“分数取最小值，时间取最大值”的选项。

题单：可使用关键词搜索公开题单。

社区管理：被管理手动棕名时，在陶片放逐会有提示。对于非本人实名手机注册的用户不再封号，而是用二次验证的方式进行确认。

社区动态：报名邀请赛不再会显示在个人动态中

讨论：超过20分钟的回复不允许自己删除

### 5 月

团队：  

- 新的团队页面
- 现在只有团队主可以修改成员的权限，如果团队主为「洛谷」请至[团队历史遗留问题解决帖](https://www.luogu.com.cn/discuss/show?postid=227126l)反馈解决。  
- 原「团队作业」将转换成团队私有题单的形式。（待转换，保留链接跳转回老页面）  
- 团队管理员可设置团队黑名单（禁止申请加入）。  

题解区：题解区改版，优化页面结构，可切换排序方式、优化 markdown、code 及 latex 渲染速度。

代码显示：调整新前端下的代码显示样式。

### 4 月

提交答案：重新上线提交答案；其他的题目也可以上传代码源文件。

交互题：允许创建和提交交互题，可以进行IO交互或者完成函数。

编辑题目：界面改版，可以上传附加文件，并在题目详情中可以下载附加文件。

我的题库：在个人中心新增“题库”tab，替代旧版页面。

云剪贴板：加入折叠功能。

openid：支持第三方绑定及登录。

### 3月

题单：发布题单功能，替代试炼场。