FROM registry.access.redhat.com/rhpam-7/rhpam70-kieserver-openshift:1.2

ADD ./contrib/standalone-openshift.xml /opt/eap/standalone/configuration/standalone-openshift.xml
USER root
RUN chown jboss:root /opt/eap/standalone/configuration/standalone-openshift.xml && chmod 664 /opt/eap/standalone/configuration/standalone-openshift.xml
USER jboss
