FROM websphere-liberty

COPY target/ProductSearchService-0.1.war /opt/ibm/wlp/usr/servers/defaultServer/apps/ProductSearchService.war
COPY server.xml /opt/ibm/wlp/usr/servers/defaultServer/

RUN  installUtility install --acceptLicense defaultServer

EXPOSE 9080
EXPOSE 9443

