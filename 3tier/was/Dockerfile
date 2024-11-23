FROM tomcat:9.0
WORKDIR /usr/local/tomcat/lib
ADD mysql-connector-java-8.0.26.jar mysql-connector-java-8.0.26.jar
# 라이브러리가 모여있는 lib 디렉토리에 호스트의 JDBC를 넣어줌

WORKDIR /usr/local/tomcat/webapps/ROOT
ADD db.jsp db.jsp
# /usr/local/tomcat/webapps/ROOT : jsp 파일들의 웹루트디렉토리

