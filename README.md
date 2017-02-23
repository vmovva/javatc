# Customizing Tomcat server.xml and switching http -> https

#manifest.yml : 

env:
  JBP_CONFIG_TOMCAT: "{ tomcat: { external_configuration_enabled: true }, external_configuration: { repository_root: \"https://raw.githubusercontent.com/vmovva/javatc/master\" } }"
