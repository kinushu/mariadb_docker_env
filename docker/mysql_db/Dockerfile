FROM mariadb:10.5

RUN apt-get update &&\
    apt-get install -y ruby &&\
    apt-get autoremove -y &&\
    apt-get clean &&\
    apt-get autoclean &&\
    rm -rf /var/lib/apt/lists/*

COPY init_proc/* /docker-entrypoint-initdb.d/