FROM python

RUN pip install flask Authlib PyJWT flask-cors
COPY server.py /opt
WORKDIR /opt
CMD ["python", "server.py"]