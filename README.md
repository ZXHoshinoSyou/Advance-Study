### Advance-Study  
#### 红岩网校2020年web后端进阶学习  
#### workOne(第一次作业)  
封装一个JWT(Json Web Token)工具，然后使用gorm+gin写四个接口：登陆、注册、查询用户、修改信息。  
其中修改信息需要鉴权，鉴权使用JWT  
#### workTwo(第二次作业)  
假如最近在举行一场名为"寻找红岩真正的带师"的比赛,以学习委员为首的一大批同学参加了这次比赛  
如果你认为他/她才是你心目中真正的带师,就为它投上一票吧  
比赛最终会根据选手的票数多少来决定比赛的结果  
所以现在我们需要实现一个简易的投票系统来让比赛正常地进行下去  
你至少需要满足以下功能:  
- 注册/登录  
- 选手参赛/退赛  
- 用户投票  
- 比赛排行榜  
- 在固定时间更新票数,用户每日只有3张票  
- ......  
#### workThree(第三次作业)  
用websocket写一个聊天室，实现单聊、多聊、群聊  
部署到服务器上  
#### workFour(第四次作业)  
- lv1.抄一遍代码  
- lv2.抄一遍的基础上，自己看能不能再写一个  
- lv3.在当前功能的基础下，加上post解析，json解析  
- lv4.在当前功能下，加上中间件功能  
#### workFive(第五次作业)  
##### Level 1 爬取豆瓣电影250  
如题所示，你需要爬取电影中的信息有  
- 电影图片  
- 电影名字  
- 电影导演  
- 电影评价  
- 电影评语  
你需要将编写一个接口来将TOP250的信息以json的格式返回  
##### Level2 爬取课表  
- 爬取教务在线所有⼤⼀学⽣的课表并存储在数据库中  
- ⾃⾏设计表（课程表，学⽣表，选课关系表）  
- 成⼀个通过学号或者姓名查询课表的接⼝（返回格式参考如下）  
- 利⽤表优化，索引优化等  
##### Level3  百度一下  
平常在你”百度一下“的时候  
你会搜先输入搜索关键词  
然后获取到搜索结果  
现在你需要用代码实现上述的"百度"，即这样的接口  
- 输入关键词后返回搜索出来结果的网页截图  
##### Level4 爬取狂魔  
- 你可以爬取以下下面网站中的相关内容  
- 网易云  
- 哔哩哔哩  
- Acfun  
- ......  
爬取内容自定，需要以接口的形式返回相应的内容  
