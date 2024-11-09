FROM ubuntu:20.04 AS base
RUN apt update
CMD [ "sh", "-c", "echo My name is $my_name" ]

FROM base AS dev
ENV my_name=TEST

FROM base AS pro
ENV my_name=Bob
