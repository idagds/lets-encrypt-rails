FROM ruby:2.3.1

WORKDIR /app/src
EXPOSE 3000

COPY Gemfile Gemfile.lock /app/src/
RUN bundle install --frozen --no-cache

COPY . /app/src
CMD ["bundle", "exec", "rails", "s", "-b", "0.0.0.0"]
