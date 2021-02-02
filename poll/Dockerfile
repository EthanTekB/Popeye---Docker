FROM python:slim
WORKDIR /poll
COPY . /poll
RUN pip3 install -r requirements.txt
EXPOSE 80
ENV NOM ethan
CMD ["flask", "run", "--host=0.0.0.0", "--port=80"]