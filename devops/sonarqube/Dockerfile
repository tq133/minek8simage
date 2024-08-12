FROM sonarqube:9.9.6-community 
LABEL MAINTAINER=master@tq133.top BUILDTYPE=Aliyun 
RUN sudo sysctl -w vm.max_map_count=524288
RUN sudo sysctl -w fs.file-max=131072
RUN sudo ulimit -n 131072
RUN sudo ulimit -u 8192

