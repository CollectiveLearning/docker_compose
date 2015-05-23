FROM ruby:latest
RUN apt-get update  && apt-get install -y libpq-dev nodejs-dev
RUN mkdir /myapp
WORKDIR /myapp
ADD . /myapp
ADD Gemfile /myapp/Gemfile
RUN bundle install


