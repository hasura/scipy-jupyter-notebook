FROM jupyter/scipy-notebook

USER root

ADD init.sh /usr/local/bin
RUN chmod 755 /usr/local/bin/init.sh

CMD ["init.sh"]