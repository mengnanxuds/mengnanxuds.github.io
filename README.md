# mengnanxuds.github.io
Public page of curious Mengnan Xu
页面和后台架构设计:

前端页面:

index.html:主页面,包含个人简介、工作经历、项目经验和联系方式等内容。
projects.html(可选):如果项目经验内容较多,可以考虑将其独立成一个页面,以便更详细地展示每个项目。
assets/:

css/:存放CSS样式表文件。
js/:存放JavaScript文件。
images/:存放个人照片、公司logo、项目截图等图片资源。




后台设计:

数据库:

个人信息表:存储个人姓名、职位、简介等基本信息。
工作经历表:存储每段工作经历的公司名称、职位、时间、职责等信息。
项目经验表:存储每个项目的名称、描述、技术栈、截图等信息。
联系方式表:存储邮箱、社交媒体链接等联系信息。


后端API:

个人信息接口:获取个人基本信息。
工作经历接口:获取工作经历列表,支持分页和排序。
项目经验接口:获取项目经验列表,支持分页和排序。
联系方式接口:获取联系方式信息。


管理后台:

个人信息管理:编辑和更新个人基本信息。
工作经历管理:添加、编辑和删除工作经历条目。
项目经验管理:添加、编辑和删除项目经验条目。
联系方式管理:编辑和更新联系方式信息。
图片资源管理:上传、删除和管理个人照片、公司logo、项目截图等图片资源。




技术选型(仅供参考):

前端:

HTML5 + CSS3
JavaScript(ES6+)
前端框架:Vue.js/React.js/Angular.js等
UI库:Bootstrap/Material-UI/Ant Design等


后端:

编程语言:Python/Java/Node.js等
Web框架:Flask/Django/Spring Boot/Express.js等
数据库:MySQL/PostgreSQL/MongoDB等


部署:

服务器:Nginx/Apache
容器化:Docker
持续集成/持续部署:Jenkins/GitLab CI/GitHub Actions等