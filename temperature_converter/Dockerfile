FROM python:3
WORKDIR /application
COPY . .
RUN pip install flask
RUN pip install -r ./requirements.txt
ENV PORT 5000
CMD ["sh", "-c", "flask run -h 0.0.0.0 -p ${PORT}"]
