FROM ubuntu:20.04

# 1. JAVA 18 - Opt to Image
COPY scripts/install_java.sh install_java.sh
RUN chmod +x install_java.sh && sync && ./install_java.sh && rm install_java.sh
ENV JAVA_HOME=/opt/jdk-18
ENV PATH="/${PATH}:/${JAVA_HOME}/bin"

CMD ["bash"]
