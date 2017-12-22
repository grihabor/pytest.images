FROM python:alpine
MAINTAINER Borodin Gregory <grihabor@mail.ru>

RUN apk update \
 && apk add make

RUN pip3 install --no-cache-dir \
        pytest \
	pytest-cov \
	pyfakefs
