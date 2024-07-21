FROM python:3.13.0b3-slim

RUN pip install --upgrade pip

RUN git clone https://github.com/SecureAuthCorp/impacket.git
RUN cd impacket && python setup.py install
ENTRYPOINT ["/bin/bash"]