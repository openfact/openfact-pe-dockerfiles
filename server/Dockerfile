FROM openfact/openfact:latest

ENV OPENFACT_VERSION 1.0.RC3

RUN rm /opt/jboss/wildfly/standalone/deployments/*
RUN cd $HOME && curl -L -O https://github.com/openfact/openfact-pe/releases/download/$OPENFACT_VERSION/openfact.war && mv $HOME/openfact.war $HOME/wildfly/standalone/deployments