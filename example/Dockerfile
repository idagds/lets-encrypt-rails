FROM ruby:2.3.1

WORKDIR /app/src

COPY Gemfile Gemfile.lock /app/src/
RUN bundle install

COPY . /usr/src/app
CMD rails s
