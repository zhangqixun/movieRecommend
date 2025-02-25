# 基于大数据平台的电影推荐系统

## 进度安排

### 11.2
完成网页架构的设计

### 11.9
完成和后端模拟数据交互

### 11.16
完成和真实数据交互与展示

## 项目部署

### 用户操作流程
#### 游客访问
用户在没有登录的时候，进入游客访问模式，可以在网页中看到热门推荐电影，如果要输入个人具体信息，需要先登录，此时要点击登录按钮进入注册登录界面

#### 用户注册
用户首先打开网页，进入主界面，点击注册和登录的选项卡，进行注册或登录；选择注册按钮，输入用户名和密码，点击注册，注册成功后返回登录页面；

#### 用户登录
选择登录按钮，输入用户名和密码，点击登录，如果登录用户名和密码正确就进入推荐电影的页面；
#### 查看与修改个人信息
进入推荐电影的页面，如果是第一次登录则推荐当前热门电影，用户可以选择点击个人信息查看个人信息，如果有需要修改的地方点击修改按钮进入个人信息修改页面进行修改，修改完成后返回推荐页面；

#### 推荐电影
在修改个人信息完成后，系统有了用户的各个重要的信息，这样系统就会根据用户的个人信息情况进行电影的推荐

#### 电影详细信息
用户点击电影图片进入电影详细介绍页面，可以对该电影的所有信息，包括主演，导演，评分，他人评论，地点，语言等进行查看；
#### 用户反馈
用户选择可以在该页面选择喜欢或者无感按钮进行反馈，当选择喜欢的时候，会返回后台用户喜欢的数据，并跳转到电影播放的页面；如果选择无感的时候，会返回后台用户不喜欢的数据，并跳转到推荐页面，让用户选择其他可能喜欢的电影。


### 前后端数据交互

登录注册过程中会有用户的账户名和密码还有userid进行前后端的交互；在查看与修改用户信息的过程中会有用户的userid，性别，所在地，生日等信息的交互；在推荐电影中会有movieid，电影图片，评分，电影名等信息的交互；在电影信息查看过程中会有movieid，电影图片，名称，导演，主演，主要内容，语言，评论的数据的交互；在用户点击反馈按钮会有userid、movieid、喜欢标志的交互
