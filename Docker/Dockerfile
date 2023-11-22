FROM tomcat:9-jre8-alpine
WORKDIR /usr/local/tomcat
COPY ./Docker/server.xml ./conf
RUN rm -rf ./webapps/*
COPY ./edu-msa-user/target/edu-msa-user-1.0.0.war ./webapps/edu-msa-user-1.0.0.war

EXPOSE 28084

