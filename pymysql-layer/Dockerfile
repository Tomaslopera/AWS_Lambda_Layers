FROM public.ecr.aws/lambda/python:3.11

RUN mkdir -p /opt/python/lib/python3.11/site-packages

RUN pip install pymysql -t /opt/python/lib/python3.11/site-packages

WORKDIR /opt

RUN zip -r /layer.zip .
