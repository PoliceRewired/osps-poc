FROM osixia/openldap
LABEL maintainer="team@policerewired.org"
ENV LDAP_ORGANIZATION="osps" LDAP_DOMAIN="osps.local"
COPY bootstrap.ldif /container/service/slapd/assets/config/bootstrap/ldif/50-bootstrap.ldif
RUN cat /container/service/slapd/assets/config/bootstrap/ldif/50-bootstrap.ldif
