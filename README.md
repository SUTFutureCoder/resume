# 联系方式
* 手机：15101669791（北京） / 13940022196（沈阳）
* Email：<FutureCoder@aliyun.com>
* QQ：506200331

---

#个人信息
* 林星辰 / 男 / 1994
* 本科 / 沈阳工业大学计算机科学与技术系 / 2012-2016
* Github：<https://github.com/SUTFutureCoder>

* 期望职位：PHP研发工程师

---

#技能清单
* Web开发：PHP
* Web框架：CodeIgniter
* Cache：Redis / memcache
* 单元测试：PHPUnit
* 前端：HTML / CSS / JS（jquery）
* 前端框架：Bootstrap / HTML5
* 数据库相关：MySQL / MongoDB / PDO / ElasticSearch
* 版本管理：Git
* 其他：WebSocket / Ajax / SPL / cURL / Python / LocalStorage / PHPDOC / OOP / 敏捷项目开发 / 设计模式 / 正则表达式 / 性能优化及安全常识 / 内部标准编程风格
* 以Linux作为日常操作系统 
* 业余管理两台阿里云和一台校园服务器OP

---

#工作经历
###百度实习（2015年7月至今）
####[csiem云分析项目](http://gitlab.baidu.com/yejin01/csiem)
我在此项目负责PHP中间件API以及其对应的[后台管理系统](http://gitlab.baidu.com/linxingchen/csiem_admin)的开发。  
1. 无需培训即可根据需求迅速地高质量完成任务，并自学PHPDOC、PHPUnit、Redis、ElasticSearch、敏捷项目开发等知识。
2. 在这个项目中，我最自豪的技术细节是高效地由数据库生成调度队列并从中获取本时刻需要执行的任务，通过使用SPL、Redis同步策略、动态挖坑填数据、手工组装JSON等技术实现，相比于传统遍历获取任务方法提升效率80%以上，支持了万级数据量的24小时任意时段任意间隔的定时任务即时获取。  

---

#主要项目
* 2015.04 - 2015.05 [沈阳工业大学德智体积分评测系统](https://github.com/SUTFutureCoder/sut_score)
> **S** 对于2014级以后入学的学生实行进行全面的评测积分制度，需要一个自动化抓取并计算，分类存储奖惩记录。  
> **T** 归纳整理2014级版学生需知奖惩分级积分制度，实现批量绩点换算算法，学习curl系列抓取函数。  
> **A** 通过分离验证码header得以获取用户cookies用于抓取数据。开发离线模式和授权模块，允许在任何时间被授权者可以随时维护自己或全体的积分项目并以Excel文件输出。  
> **R** 成功完成一个允许教工和学生干部轻松计算、维护学生积分的平台。目前已在沈阳工业大学投入实际使用。  


* 2015.02 - 2015.04 [WSPDM2 基于PHP Websocket的数据库管理器](https://github.com/SUTFutureCoder/intelligence_server)
> **S** 同类的数据库管理器体积庞大，DBA无法同步即时协作，无法连接外网数据库，SQL语句构建速度较慢。  
> **T** 学习SPL、PDO、memcache等技术，预想用户操作需求，研究ANSI SQL标准以构建通用语句。  
> **A** WebSocket引擎允许DBA之间进行同步协作，防止脏数据产生。图形化界面封装了大量的复杂操作并且提供语句极速构建功能。使用PDO理论支持多达13种关系型数据库本地或远程连接并附带MongoDB非关系型数据库，动态构建通用(no)SQL语句。使用SPL高效率创建备份和回滚数据，[ECharts](https://github.com/ecomfe/echarts)构建图表以便分析。  
> **R** 成功完成一个具有高实时性、通用性、轻量级、跨平台、人性化界面设计等特性的数据库管理器，并且加深了对数据库语句的使用熟练度。并获得**第八届中国大学生计算机设计大赛 全国总决赛一等奖**。  

* 2014.03 [三位一体信息化社团建设套件第二版](https://github.com/SUTFutureCoder/nws_v2)（**开发进行中**） 
> **S** 社团管理困难，通知短信开支庞大，部员参与度不足，社团文化无法传承。  
> **T** 总结在社团中的工作经验，收集部员和同事在管理或参与社团活动过程中的一些不满或意见，并将这些信息转换成各种功能。 尝试使用Ajax技术和WebSocket引擎，掌握数据库结构优化技巧。  
> **A** 使用CI框架进行控制台、PhoneGap进行移动端以及MediaWiki进行社团百科开发，共包含三十余种社团常用功能。  
> **R** 该套件顺利开发完毕并获得**第七届中国大学生计算机设计大赛 全国总决赛一等奖**，在所属社团作为试点进行测试。  

* 2015.01 [沈阳工业大学排课系统1.5](https://github.com/SUTFutureCoder/paike1.5)
> **S** 每学期进行实验室排课安排需要学院集中开会研讨，传统记录和安排方式效率低、灵活性差。  
> **T** 跟踪传统排课流程，收集负责教师需求，并首次尝试使用设计模式。允许各个教师在实验室空闲时间自行安排课程并导出Excel文档以便打印。  
> **A** 根据现实情况添加排课、教师、课程、班级管理等功能并使用PHP EXCEL类支持一键导出指定/所有实验室或教师课程安排及对应课程表。  
> **R** 已成功完成本学院实验室2014及2015年度全校排课任务。 节约每教师每学期4小时及实验中心人力一人。 

* 2014.09 [WebSocket-Engine](https://github.com/SUTFutureCoder/WebSocket-Engine)
> **S** 大部分Web程序使用轮询方法以达到实时性，延迟和服务器开销较大。  
> **T** WebSocket底层引擎转发API请求，意在此后的工程中取代Ajax以实现更高的实时性、协作性及解决PhoneGap跨域问题。  
> **A** 对WebSocket框架**[Workerman](https://github.com/walkor/workerman)**进行二次开发，使用cURL模拟POST数据至指定API。并添加“群组”功能，使多个应用能够运行在同一引擎。  
> **R** WebSocket-Engine引擎应用到接下来的实时性应用开发中。  

* 2013.08 - 2014.11 [SUTOJ 沈阳工业大学在线评测系统 13.10/14.04/14.10](https://github.com/SUTFutureCoder/sutoj)
> **S** 华中科技大学ACM开源项目**[HUSTOJ](https://code.google.com/p/hustoj/)**无法满足本校特色赛制设计，后台操作复杂。  
> **T** 收集比赛组织者及志愿者团队需求，设计“一键”系列便利功能。  
> **A** 全新设计界面，加强后台管理员功能：作弊代码平铺对比、打印随机密码条、一键配置校赛等，并将其改造为具有本校特色赛制的OJ。  
> **R** 已依靠此系统成功举办三届沈阳工业大学ACM程序设计大赛。  


* 2009.10 - 2013.05 高性能图形化网页系统第一/二/三/四版  
> 高中时期前端作品，获得省市级一二等奖荣誉五次，对互联网和编程的无限热爱从这里开始。 

---

# 曾获荣誉
###专业技能
* 2015.08 [第八届中国大学生计算机设计大赛 全国总决赛一等奖](https://raw.githubusercontent.com/SUTFutureCoder/resume/master/8th_gold_medal.jpg)
* 2014.07 [第七届中国大学生计算机设计大赛 全国总决赛一等奖](http://jwzx.sut.edu.cn/jwc/content.jsp?id=44&xlh=681)
* 2015.06 第八届中国大学生计算机设计大赛 辽宁赛区 一等奖
* 2014.05 第七届中国大学生计算机设计大赛 辽宁赛区 二等奖
* 2014.06 [ACM/ICPC 东北赛区 二等奖](https://github.com/SUTFutureCoder/resume/blob/master/ACM_second.jpg)  
* 2014.05 [ACM/ICPC 辽宁赛区 三等奖](https://github.com/SUTFutureCoder/resume/blob/master/ACM_third.jpg)  
* 2014.10 第七届全国大学生网络商务创新应用大赛 辽宁赛区 二等奖
* 2013.11 [第六届全国大学生网络商务创新应用大赛 全国总决赛 三等奖](https://github.com/SUTFutureCoder/resume/blob/master/E-commerce_third.jpg)  
* 2013.10 [第六届全国大学生网络商务创新应用大赛 东北赛区 综合一等奖](https://github.com/SUTFutureCoder/resume/blob/master/E-commerce_ace.jpg)  
* 2014.07 [辽宁省大学生创业就业大赛公益创业赛 二等奖](https://github.com/SUTFutureCoder/resume/blob/master/entrepreneurship.jpg)  
* 高中时期 省/市级电脑制作活动 网页组 一/二等奖 共五次

###综合素质
* 2014.12 [中国仪器仪表学会二等奖学金](http://www.cis.org.cn/NewsDeltailed.aspx?id=554&PID=9)  （全国共19人）  
* 2014.12 [辽宁省政府奖学金](https://github.com/SUTFutureCoder/resume/blob/master/Provincial_Government_Scholarship.jpg)  
* 2014.12 [一等校突出贡献奖](https://github.com/SUTFutureCoder/resume/blob/master/Contribution.jpg)   
* 2014.11 [校一等奖学金](https://github.com/SUTFutureCoder/resume/blob/master/first_scholarship.jpg)  
* 2013.11 [校二等奖学金](https://github.com/SUTFutureCoder/resume/blob/master/second_scholarship.jpg)  
* 2014.12 [校友工作学生志愿者协会 贡献奖](https://github.com/SUTFutureCoder/resume/blob/master/volunteer.jpg)  
* 2014.11 校“优秀团干部”称号  
* 2014.11 [院“十佳学习标兵”称号](https://github.com/SUTFutureCoder/resume/blob/master/learning_model.jpg)  
* 2013.11 [院“十佳科技创新标兵”称号](https://github.com/SUTFutureCoder/resume/blob/master/technology_pacesetter.jpg)
* [2014](https://github.com/SUTFutureCoder/resume/blob/master/miyoshi_student.jpg)、[2013](https://github.com/SUTFutureCoder/resume/blob/master/miyoshi_student2.jpg)  两年“三好学生”称号

[**共获得各类荣誉35项**](https://github.com/SUTFutureCoder/resume/blob/master/college_awards.jpg)

---

#致谢
感谢您阅读我的简历，期待能有机会和您共事。
