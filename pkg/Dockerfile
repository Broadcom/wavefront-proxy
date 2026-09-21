# Create a docker VM for building the wavefront proxy agent .deb and .rpm
# packages.
FROM ruby:3.0

RUN gem install fpm
RUN apt-get update
RUN apt-get install -y rpm
