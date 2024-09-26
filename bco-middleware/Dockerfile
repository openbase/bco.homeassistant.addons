FROM eclipse-mosquitto:latest

RUN echo -e "allow_anonymous true\nlistener 13780" > /mosquitto/config/mosquitto.conf

EXPOSE 13780

CMD ["mosquitto", "-c", "/mosquitto/config/mosquitto.conf"]