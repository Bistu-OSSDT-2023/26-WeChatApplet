## 项目介绍 

 本项目为约课小程序，使用微信小程序开发平台进行开发，可以为各类培训机构提供学生家长选课、预约时间的登记，可以查看自己的课时消耗情况。学生端可以选择老师和预约时间，预约成功后课时将减少，若取消预约，将恢复课时数。老师端可以设定预约时间段及人数。后台端可以设置老师及课程的基本信息，还可给学生设置课时数。



## 后台管理系统
- 后台超级管理员默认账号:admin，密码123456，请登录后台后及时修改密码和创建普通管理员。

## LICENSE
选择GPL license


## 小组成员

曲浩铭 
张耀扬 
郑子祥 
刘晓   
## 环境部署

在微信小程序导入源码后，需要开通云开发。

打开云开发控制平台，创建一个新的云开发环境。

打开cloudfunctions/mcloud/congif/config.js文件，将CLOUD_ID改为云环境ID。

点击couldfunctions目录，右键选择当前环境，点击mcloud，选择上传并部署：云端安装依赖。

打开云开发控制平台，点击云函数，点击版本与配置，选择当前云函数，点击配置，将超时时间改为60，环境变量改为Key：TZ，Value：Asia/Shanghai。

打开mijiprogram/setting/setting.js文件，将CLOUD_ID改为云环境ID。








