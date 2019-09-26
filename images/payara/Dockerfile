FROM payara/server-full:5.183

MAINTAINER Olivier Liechti <olivier.liechti@heig-vd.ch>


ADD drivers/mysql-connector-java-5.1.39-bin.jar /glassfish4/glassfish/lib/

COPY app-dist/LandingPageApp-1.0-SNAPSHOT.war app-dist/LandingPageMVCApp-1.0-SNAPSHOT.war /opt/payara/glassfish/domains/domain1/autodeploy/

