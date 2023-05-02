FROM postgres:9.6
RUN echo 'es_ES ISO-8859-1' >> /etc/locale.gen 
RUN locale-gen
RUN localedef -i es_ES -c -f ISO-8859-1 -A /usr/share/locale/locale.alias es_ES.ISO-8859-1
ENV LANG es_ES.iso88591
