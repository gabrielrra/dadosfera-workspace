FROM dadosfera/base-kernel-py:1.0.2

USER root

COPY setup_script.sh /tmp/setup_script.sh
RUN chmod +x /tmp/setup_script.sh
RUN /tmp/setup_script.sh
COPY setup_script.sh /tmp/setup_script.sh

USER $NB_USER

CMD [ "tail", "-f", "/dev/null"	 ]
