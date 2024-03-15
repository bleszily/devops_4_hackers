FROM python:3.13.0a4-slim

RUN pip install --upgrade pip

RUN git clone https://github.com/SecureAuthCorp/impacket.git
RUN cd impacket && python setup.py install
ENTRYPOINT ["/bin/bash"]