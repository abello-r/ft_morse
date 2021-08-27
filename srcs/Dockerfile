FROM	alpine:3.14.1

RUN		apk update && \
		apk add vim

COPY	morse_code/ /home/morse_code/
COPY	tools/ /home/tools/

WORKDIR	/home


