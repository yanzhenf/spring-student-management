# spring-student-management
本系统使用Springboot开发的一个学生竞赛管理平台
由学生和和教师两个身份
系统功能分析
大学生竞赛管理系统设计了注册学生会员，评委和管理人员三个功能模块，其功能如下：
1、注册、登陆
 该系统根据操作权限的不同分为管理员，学生用户，评委三个操作模块，新用户在登陆前要进行用户注册，注册完成后方可进行登陆。
用户注册时需填入手机号，姓名，密码，其中手机号作为用户登录时的账号。

管理员
1.管理员进入系统对前端注册的学生用户信息进行管理。管理员有权对会员信息进行修改与删除操作。点击编辑会进入会员信息详情界面。管理员有权重置用户密码。
2.管理员登录系统后可发布比赛公告信息。公告发布后可进行查看修改与编辑。
3.管理员登录系统后可对系统竞赛信息进行管理与维护。管理员有权对竞赛信息进行修改与删除操作。管理员决定该竞赛开始、结束时间，状态为已开始时，前端用户才可选择进行答题。
4. 管理员可以在线添加试题内容，新增试题类型，问题标题，答案选项以及答案信息，新增试题后可进行修改与删除。
5.管理员可在线新增评委信息，每一次竞赛评委人数不得少于三人。管理员可查看报名学生信息，包括分数，排名以及答题时间等。
学生用户
1.大学生用户输入账号密码登录系统后，可查看竞赛信息，输入标题，创建人等信息对比赛公告信息进行搜索查询。
2.学生用户登录系统后，进入竞赛管理界面查看竞赛信息，可根据类型与状态进行竞赛的查询。大学生可根据竞赛信息进行报名。
3.大学生用户可以通过系统进行用户问卷答题。根据系统显示的问卷题目选择是否答题。系统会显示该答卷是否已经答题，以及用户所得分数和排名情况。为未答题状态的问卷学生用户可以选择开始答题。
评委
1.管理员奖评委添加到竞赛信息立候，评委用户输入账号密码登录系统可查看竞赛信息。
2.点击参赛选手即可查看选手答题信息并及时做出评分。
3.个人信息的维护与修改
