FROM ubuntu

WORKDIR /mundir
RUN touch moi.txt
COPY local.txt .
RUN apt-get update && apt-get install -y wget
RUN wget http://example.com/index.html
CMD ["/bin/bash"]
