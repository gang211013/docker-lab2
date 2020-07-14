FROM ruby
MAINTAINER zhao yonggang zhaoyg@test.com

RUN gem install jekyll

VOLUME /data
VOLUME /usr/local/apache2/htdocs/
WORKDIR /data

CMD [ "jekyll", "build", "-d" ,"/usr/local/apache2/htdocs/" ]
