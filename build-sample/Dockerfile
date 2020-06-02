# @James - where is "ubi8" coming from?
# FROM ubi8
FROM busybox
RUN yum install -y java-11-openjdk
COPY /bin/*.jar /app/bin/
CMD java -jar /app/bin/*.jar server
