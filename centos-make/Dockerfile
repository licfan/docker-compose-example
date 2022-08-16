FROM centos-cmake:latest
# your command
RUN wget https://download-ib01.fedoraproject.org/pub/epel/7/x86_64/Packages/r/rapidjson-devel-1.1.0-2.el7.noarch.rpm && \
    rpm -Uvh rapidjson-devel*rpm && \
    yum install -y centos-release-scl devtoolset-7 && \
    source /opt/rh/devtoolset-7/enable
CMD [ "/bin/sh", "-c", "while sleep 864000; do :; done" ]