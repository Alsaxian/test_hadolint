FROM python:3.8-alpine
# WORKDIR /dockerfile_python/
COPY requirements.txt /tmp/
RUN apk update && apk add make automake gcc g++ subversion python3-dev && pip install -r /tmp/requirements.txt
ENTRYPOINT ["python3", "/script.py"]