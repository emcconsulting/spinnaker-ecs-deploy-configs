FROM openjdk:8u111-jre-alpine


COPY ./igor/igor-web/build/install/igor /opt/igor
COPY ./igor.yml /opt/spinnaker/config/igor.yml

RUN apk --nocache add --update bash

CMD ["/opt/igor/bin/igor"]
