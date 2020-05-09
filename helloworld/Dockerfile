FROM openjdk:8u181-jre-slim

ENV J_OPTS ""

COPY Dockercmd.sh /bin/
RUN ["chmod", "+x", "/bin/Dockercmd.sh"]

COPY target /bin/target/

CMD [ "/bin/bash", "-c", "/bin/Dockercmd.sh" ]
