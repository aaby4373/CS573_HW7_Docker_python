FROM ubuntu:latest
RUN apt-get update && apt-get install -y python3 python3-pip

COPY ./src ./ 

RUN pip3 install jupyter
RUN pip3 install pandas
RUN python3 hw7_docker.ipynb
ENTRYPOINT ["jupyter", "notebook","--ip=*", "--allow-root"]
