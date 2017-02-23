# **Customizing Tomcat server.xml and switching http -&gt; https**

**manifest.yml :**

add "JBC\_CONFIG\_TOMCAT" enviroment variable to your manifest.yml file (Example yml is in the repository).


Note that the compressed file tomcat_configuration_1.0.0.tar.gz has server.xml under directory :  /conf. The server.xml from here replaces default server.xml during staging.

**Edits to web.xml may be required :**

Please see : https:\/\/developer.ibm.com\/answers\/questions\/245322\/how-to-redirect-http-to-https-on-ibm-bluemix-using.html
