FROM debian:12-slim

RUN apt-get update && apt-get install -y \
    ant \
    default-jdk \
    libcommons-lang3-java \
    libjss-java \
    libslf4j-java \
    libtomcat10-java \
    git \
    curl \
    unzip \
    procps \
    libxext6 \
    libxrender1 \
    libxtst6 \
    libxi6 \
    libfreetype6


#RUN apt-get update && apt-get install -y \
#    openssh-server

#RUN mkdir /var/run/sshd

#RUN echo 'root:docker' | chpasswd

#RUN sed -i 's/#PermitRootLogin prohibit-password/PermitRootLogin yes/' /etc/ssh/sshd_config

#EXPOSE 22

# Start SSH server
#CMD ["/usr/sbin/sshd", "-D"]

