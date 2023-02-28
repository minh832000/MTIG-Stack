FROM eclipse-mosquitto:latest

COPY ./config /mosquitto/config

# hash password
RUN mosquitto_passwd -U /mosquitto/config/password.txt

EXPOSE 1883
