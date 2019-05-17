# CSRF_DoubleSubmitCookiePattern
Cross-site Request Forgery protection in web applications(Used Double Submit Cookie Pattern)

In this project used Double Submit Cookie Pattern to avoid Cross-site Request Forgery protection in a web application. The application consists of a simple login page with hard-coded credentials. Upon login, generate session identifier and set a cookie in the browser. At the same time, generate the CSRF token for the session and set a cookie in the browser. The CSRF token value is not stored in the server side. When the form is submitted to the action, the CSRF token cookie will be submitted and in the form body, the CSRF token value will be submitted. The web page that accepts the form submission, obtain the CSRF token received in the cookie and in the message body. If Validation Success, show success message. If not show error message.

## Download and Installation

###### Clone the project to the local Machine

```
git clone https://github.com/AnuradhaSD/CSRF_DoubleSubmitCookiePattern.git

```
### Run application

- Application Implemented Using Eclipse IDE
- Appache TomCat Should be Configured(Used Tomcat V7.0)

###### Login Form URL

```
localhost:8080/CSRF/login.jsp

```
###### Credentials

```
UserName :asd
Password :123
```
Upon Sceessful login directs to Form

###### Form URL
```
localhost:8080/CSRF/form.jsp
```
### Blog URL : [Double Submit Cookie Pattern](https://sachinthaweesinghe.blogspot.com/b/post-preview?token=APq4FmBMiienKy4XUqK7IHjcgSMyuvOI1IWbrjMs-r32mzuUmi_LLVSKocgEkAl2RFmpqN_zP-bwB5OlvVCdXomlPHNTntufSARfahqACsONVoZDHWklDjpiByxMVL15yA0lzEg3MQJu&postId=6727372578414464531&type=POST)
