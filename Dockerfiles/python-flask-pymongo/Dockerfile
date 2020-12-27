FROM frolvlad/alpine-python3

RUN pip install --upgrade pip \
	&& pip install flask \
	&& pip install pymongo


ENV GROUP_ID=1000 \
    USER_ID=1000

ENTRYPOINT ["/usr/bin/python" , "/app/app.py"]