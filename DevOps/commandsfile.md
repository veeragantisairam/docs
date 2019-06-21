# basic commands

-  create **AWS** account and launch **EC2** server.
-  create  new **key pair** and download **pem** file
-  download **putty** and install,which for connect to server.
-  open putty gen for convert pem file to ppk file (putty server accept only ppk files)
-  connet to putty server from EC2 instance through  public ip(13.30.8.90).
-  putty command ask user, bydefault **(ec2-user)**.
-  and then switch to root user "**sudo su**".
-  once switch to root user we will access all linux permissions.
-  inorder to install jenkins, jenkins required **java** softwere. to install java "**yum install java-1.8.0**". java will be installed.
-  There is two methods to install jenkins 1). yum method  2). rpm method.
    1) **yum method**
    
    step a)  -go to genkins website  "**https://pkg.jenkins.io/redhat-stable/**"
    
    step b) - in putty command line download jinkins package 
        **sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo** 
    
    step c) - and then install jenkins **sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key**
    
    step d) start genkins **service jenkins status**, **service jenkins start**,**service jenkins stop**.
    
    step e) access jenkins in browser (**13.30.8.90:8080**).
    
    step f) verify jenkins authentication code for first time open. (**cat somefilename**).
    
    step g)  after verification success download some dependencies as shown in website, and  create jenkins username and password .
    
    step h)  complete
    
    2) **rpm method **
 
    step a) -go to genkins website  "**https://pkg.jenkins.io/redhat-stable/**" and copy link of required jenkins package 
    
    step b) paste that link in putty command line with (**wget https://pkg.jenkins.io/redhat-stable/jenkins-2.176.1-1.1.noarch.rpm**)
    
    
    
    
    
    
```js
let hello = 'hi';
```

```css
p {
color: blue;
}
```

```html
<p></p>
```
