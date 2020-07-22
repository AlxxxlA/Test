FROM python:2.7

RUN apt update -y && apt install -y python-flask python-requests

EXPOSE 8000
EXPOSE 22
EXPOSE 21

WORKDIR /app
COPY ./api.py /app/api.py

ENTRYPOINT ["/usr/bin/python"]
CMD ["api.py"]