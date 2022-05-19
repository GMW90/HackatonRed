FROM quay.io/jkube/jkube-java:0.0.13
ENV JAVA_OPTIONS=-Dquarkus.http.host=0.0.0.0 JAVA_APP_DIR=/deployments
LABEL org.label-schema.description="" org.label-schema.version=1.0.0-SNAPSHOT org.label-schema.schema-version=1.0 org.label-schema.build-date=2022-05-18T16:59:33.825637200 org.label-schema.name=antennas-front
EXPOSE 8080 8778 9779
COPY /lib/deployments /deployments/
COPY /fast-jar/deployments /deployments/
WORKDIR /deployments
