# publiccms_xss version:V4.0.202406
Public CMS backend data addition is vulnerable to XSS. First, log in to the backend：

![image](https://github.com/user-attachments/assets/1d87a1e3-12c9-4129-b38e-0d4a3b7d4d24)
After that, click on the "Category Management" feature：
![image](https://github.com/user-attachments/assets/16a4b8dd-a969-4927-a2a9-681a08db1864)
Afterward, in the label and code input fields for adding a category, enter the code: `<script>alert('XSS')</script>` and then save it:
![image](https://github.com/user-attachments/assets/27113adc-0243-4051-9282-a367f7070d45)
After logging out, refresh the interface and click on "Edit Category" to trigger the XSS:
![image](https://github.com/user-attachments/assets/4fda9377-3929-4f23-ad39-979585c17960)





