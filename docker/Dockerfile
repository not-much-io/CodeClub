FROM python
COPY ./tester.py /src/tester.py
COPY ./solution.py /src/solution.py
COPY ./requirements.txt /src/requirements.txt
WORKDIR /src
RUN ["pip", "install", "-r", "requirements.txt"]
CMD ["python", "tester.py"]
