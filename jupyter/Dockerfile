FROM python:3.12-slim

RUN mkdir src
WORKDIR /src
COPY requirements.txt /src

RUN pip3 install notebook
RUN pip3 install -r requirements.txt

CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--port=8888", "--no-browser", "--allow-root"]