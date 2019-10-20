FROM tomcat
WORKDIR /usr/local/tomcat
ADD app1.war  webapps/app1.war
ADD app2.war  webapps/app2.war
ADD conf/manager-gui.xml webapps/manager/META-INF/context.xml
RUN apt-get update
RUN apt-get install vim -y
EXPOSE 8080
EXPOSE 8081
EXPOSE 8082