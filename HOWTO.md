* view sprint saml quickstart guide: http://docs.spring.io/spring-security-saml/docs/current/reference/html/chapter-quick-start.html
* git clone https://github.com/bboortz/spring-security-saml.git
* cd sprint-security-saml
* cd sample
* edit src/main/webapp/WEB-INF/securityContext.xml 
** change the value of the key "entityId"
* mvn package
* mvn tomcat7:run
* access with a browser: http://localhost:8080/spring-security-saml2-sample/

*View Also*
* http://docs.spring.io/spring-security-saml/docs/current/reference/html/index.html
* https://github.com/vdenotaris/spring-boot-security-saml-sample
* http://www.testshib.org/
* http://www.ssocircle.com/
* https://saml-federation.appspot.com/saml/discovery?returnIDParam=idp&entityID=saml-federation.appspot.com
