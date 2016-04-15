FROM index.shurenyun.com/storm-0.10:base 
MAINTAINER FANG ZHIHAO "zhfang@dataman-inc.com"

RUN /usr/bin/config-supervisord.sh nimbus 
RUN /usr/bin/config-supervisord.sh drpc
RUN /usr/bin/config-supervisord.sh ui

EXPOSE 3772 3773 6627 8080 

CMD /usr/bin/start-supervisord.sh
