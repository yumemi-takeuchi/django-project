FROM python:3.6

ADD requirements.txt /tmp/

RUN pip install --upgrade pip
RUN pip install -r /tmp/requirements.txt

# create application directory
RUN mkdir /app
WORKDIR /app
