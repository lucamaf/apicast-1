FROM quay.io/3scale/apicast:master

RUN mkdir /opt/app-root/src/mssl
COPY cert.pem /opt/app-root/src/mssl/
COPY key_94744bc5-e945-457f-ad19-c98d1fe24c6f.pem /opt/app-root/src/mssl/

COPY mssl.conf /opt/app-root/src/apicast.d/location.d/

