FROM python:3.12-slim

RUN mkdir src
WORKDIR /src

RUN pip3 install notebook

CMD ["jupyter", "notebook", "--ip=0.0.0.0", "-p=8888", "--no-browser", "--allow-root"]