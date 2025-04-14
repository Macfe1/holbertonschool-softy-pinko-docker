FROM ubuntu:24.04
WORKDIR /app
COPY  api.py /app/api.py
RUN apt-get update && apt-get upgrade -y
RUN apt-get install -y python3 python3-pip
RUN pip3 install flask --break-system-packages
CMD python3 api.py 