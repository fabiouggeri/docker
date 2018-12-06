FROM debian 
RUN apt-get update
RUN apt-get install apache2 vim htop -y
COPY index.html /var/www/html/index.html
CMD /bin/bash
