#
# OpenJDK Java 7 JDK Dockerfile
#

# Pull base image.
FROM vertigomedia/ubuntu-deps
MAINTAINER Dan Fowler <dan@logickc.com>

# Install Java.
RUN \
  apt-get update && \
  apt-get install -y openjdk-7-jdk && \
  rm -rf /var/lib/apt/lists/*

# Define working directory.
WORKDIR /data

# Define commonly used JAVA_HOME variable
ENV JAVA_HOME /usr/lib/jvm/java-7-openjdk-amd64

# Define default command.
CMD ["bash"]
