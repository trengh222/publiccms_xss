# publiccms_xss
publiccms后台增添数据存在xss
首先登陆后台：
![image](https://github.com/user-attachments/assets/1d87a1e3-12c9-4129-b38e-0d4a3b7d4d24)
之后点击“分类管理”功能：
![image](https://github.com/user-attachments/assets/16a4b8dd-a969-4927-a2a9-681a08db1864)

之后在添加分类的标签和编码中输入代码：“
<script>alert('XSS')</script>”并保存:
![image](https://github.com/user-attachments/assets/27113adc-0243-4051-9282-a367f7070d45)
退出后刷新界面，点击修改分类即可触发xss:
![image](https://github.com/user-attachments/assets/4fda9377-3929-4f23-ad39-979585c17960)





