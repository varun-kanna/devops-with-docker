FROM ubuntu:22.04

RUN apt update && apt install -y curl

COPY script.sh .

ENTRYPOINT ["./script.sh"]

CMD ["helsinki.fi"]