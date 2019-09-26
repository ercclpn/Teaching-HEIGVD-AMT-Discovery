FROM tomee:8-jre-7.1.0-plume

MAINTAINER Olivier Liechti <olivier.liechti@heig-vd.ch>

ADD config /usr/local/tomee/conf/
ADD manager /usr/local/tomee/webapps/manager/

COPY app-dist/LandingPageApp-1.0-SNAPSHOT.war app-dist/LandingPageMVCApp-1.0-SNAPSHOT.war /usr/local/tomee/webapps/
