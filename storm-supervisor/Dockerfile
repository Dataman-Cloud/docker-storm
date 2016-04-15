FROM index.shurenyun.com/storm-0.10:base
MAINTAINER FANG ZHIHAO "zhfang@dataman-inc.com"

EXPOSE 6700 6701 6702 6703 8000

RUN /usr/bin/config-supervisord.sh supervisor
RUN /usr/bin/config-supervisord.sh logviewer
CMD /usr/bin/start-supervisord.sh
