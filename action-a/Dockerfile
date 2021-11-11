FROM debian:9.5-slim

ADD entrypoint.sh action-a/entrypoint.sh
RUN chmod +x action-a/entrypoint.sh
ENTRYPOINT ["sh -c "echo Hello world my name is $INPUT_MY_NAME""]
