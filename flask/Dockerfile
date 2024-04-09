FROM python:3-alpine3.10
WORKDIR /python-docker
COPY . .
RUN pip3 install --upgrade pip -r requirements.txt
EXPOSE 3000
CMD python3 main.py
