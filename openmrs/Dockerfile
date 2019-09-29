FROM tomcat:8.0
LABEL author="mallikarjun"
ADD 2.1.2/openmrs.war /usr/local/tomcat/webapps/openmrs.war
EXPOSE 8080
CMD ["catalina.sh", "run"]

# docker build -t openmrs:2.1.2 .
# docker tag opemrs:2.1.2 mallikarjunangadi/openmrs:2.1.2
# docker login
# docker push <>
