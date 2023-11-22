FROM python:slim-bookworm

RUN pip install --upgrade pip

RUN git clone https://github.com/SecureAuthCorp/impacket.git
RUN cd impacket && python setup.py install
ENTRYPOINT ["/bin/bash"]