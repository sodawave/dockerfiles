#########################################
# MQTT broker: Mosquitto
#########################################

FROM alpine:latest

MAINTAINER Sodawave <https://github.com/sodawave>

# Install packages
RUN apk add --update mosquitto mosquitto-clients

# Expose MQTT port
EXPOSE 1883

ENTRYPOINT ["mosquitto"]