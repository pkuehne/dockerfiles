FROM ubuntu:18.04

# Run with 
# docker run --rm -it -v /path/to/jrnl/data:/root/ jrnl
RUN apt update -qq && apt install -y -qq --no-install-recommends \
        python3 \
        python3-venv \
        python3-pip

RUN pip3 install setuptools 
RUN pip3 install jrnl 

ENTRYPOINT ["jrnl"]
