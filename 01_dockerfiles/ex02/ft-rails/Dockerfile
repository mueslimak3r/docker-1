FROM ruby

RUN apt-get update -y && apt-get upgrade -y
RUN apt-get install -y nodejs
RUN gem install rails

ONBUILD COPY app/ /opt/app
ONBUILD WORKDIR /opt/app/
ONBUILD RUN bundle install && \
    bundle exec rake db:migrate && \
    bundle exec rake db:seed