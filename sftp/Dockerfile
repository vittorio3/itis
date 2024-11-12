FROM debian:bookworm

RUN apt-get update && \
    apt-get upgrade -y && \
    apt-get -y install openssh-server && \
    mkdir -p /var/run/sshd

RUN useradd -m alunno && \
    echo "alunno:password" | chpasswd

WORKDIR /home/alunno/

RUN ssh-keygen -t rsa -q -f "$HOME/.ssh/id_rsa" -N ""

EXPOSE 22

CMD ["/bin/sh", "-c", "/usr/sbin/sshd -D -e && sleep infinity"]
