FROM sonvn/jenkins
RUN ls -lt /usr/lib/jvm/
RUN export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64
RUN mkdir /opt/java
COPY ./Helloworld.java /opt/java
RUN javac /opt/java/Helloworld.java
