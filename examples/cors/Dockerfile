FROM quay.io/3scale/apicast:master

RUN mkdir /opt/app-root/src/mssl
COPY ./examples/cors/cert.pem /opt/app-root/src/mssl/
COPY ./examples/cors/key_94744bc5-e945-457f-ad19-c98d1fe24c6f.pem /opt/app-root/src/mssl/

COPY ./examples/cors/mssl.conf /opt/app-root/src/apicast.d/location.d/

