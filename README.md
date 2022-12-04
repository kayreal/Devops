# Devops
    <html>  
    <head>  
    <title> Login Form</title>  
    </head>  
    <body>  
    <h3> LOGIN </h3>  
    <formform ="Login_form" onsubmit="submit_form()">  
    <h4> USERNAME</h4>  
    <input type="text" placeholder="Enter your email id"/>  
    <h4> PASSWORD</h4>  
    <input type="password" placeholder="Enter your password"/></br></br>  
    <input type="submit" value="Login"/>  
    <input type="button" value="SignUp" onClick="create()"/>  
    </form>  
    <script type="text/javascript">  
    function submit_form(){  
    alert("Login successfully");  
    }  
    function create(){  
    window.location="signup.html";  
    }  
    </script>  
    </body>  
    </html>  #2. Start of tomcat configuration 
    
    
    

#Tomcat server configuration:
find / -name server.xml context.xml
vim /opt/tomcat9/conf/server.xml
vi /opt/tomcat9/webapps/manager/META-INF/context.xml
vi /opt/tomcat9/conf/tomcat-user.xml  # to add user

	<user username="landmark" password="admin" roles="manager-gui,admin-gui"/>
	

/opt/tomcat9/conf/context.xml

 vi /opt/tomcat9/webapps/manager/META-INF/context.xml
  
  vi /opt/tomcat9/conf/tomcat-user.xml  # to add user
  
	
	username YourName password=PassWord   roles=manager-gui
    
    
    
    
