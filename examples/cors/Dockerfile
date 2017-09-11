FROM registry.access.redhat.com/3scale-amp20/apicast-gateway:1.0

RUN mkdir /opt/app-root/src/mssl
COPY cert.pem /opt/app-root/app/mssl/
COPY key_94744bc5-e945-457f-ad19-c98d1fe24c6f.pem /opt/app-root/app/mssl/

COPY mssl.conf /opt/app-root/app/apicast.d/location.d/

