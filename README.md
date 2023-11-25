# grade_manage
### 项目说明

本项目为软工小组作业之教务系统设计的前后端源码，设计的产品是一款成绩管理系统，用户可以通过页面端访问并正常使用。通过本系统使学校拥有便捷的管理学生成绩方式，如随时查询与修改课程和成绩，增加与删除老师、学生账号等功能，提高教务工作效率、减少重复劳动，并提供准确、可靠的数据支持。

### 涉及技术

前端技术栈：vue2,vue-router,axios,vuex,elementui,echarts,webpack
技术栈：springboot，mybatis，mysql，fastjson，pagehelper；

### 产品的功能
本系统的用户主要包括三类：学生、教师、管理员。在登录界面选择不同角色，输入正确账号密码后即可登录。
学生拥有查询自己成绩、选课、删除选课与查询课表的功能。
教师拥有开设或取消课程、查询课程，新增与修改成绩、查询成绩的功能。
管理员拥有修改学生与教师账号的权限，并可随时修改学生与教师的请求，并查询总体的选课与成绩情况。

### 前端部署
npm i下载依赖
npm run serve运行
npm run build打包

### 学生端
![image](https://github.com/jobgege/academic-system/assets/121150459/b53ebc0d-ce85-4ce5-bcc7-a1b3e17aed64)

### 老师端
![image](https://github.com/jobgege/academic-system/assets/121150459/b871e069-ecb9-4732-bfb2-27d370d7a093)

### 管理员端
![image](https://github.com/jobgege/academic-system/assets/121150459/96b90de8-d111-41c3-81a3-fb567e647367)
