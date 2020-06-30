For Tomcat servlet container:
    
1) New: JAVA Project
2) New: 
   webapp: main directory
   classes: class file directory or build output folder
   lib: jars for webapp, different from "Add Libraries"(this is just for compliler, e.g. JRE)
   WEB-INF: security resource directory
   web.xml: webapp deployment description
(https://stackoverflow.com/questions/19786142/what-is-web-inf-used-for-in-a-java-ee-web-application)
3) Config Build Path...-->change source build out folder: classes
4) change <context/> in server.xml
   <Context docBase="D:\workspace\eclipse\simple-web-app\webapp" path="/web" reloadable="true"/>  
5) enter http://localhost:8080/web

Done!

New 
