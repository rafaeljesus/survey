Survey Example app
==============================

[![CircleCI](https://circleci.com/gh/rafaeljesus/survey.svg?style=svg)](https://circleci.com/gh/rafaeljesus/survey)
[![Code Climate](https://codeclimate.com/github/rafaeljesus/survey/badges/gpa.svg)](https://codeclimate.com/github/rafaeljesus/survey)


It's a Rails 3.2 app.

The application allows users to sign up and create surveys. Other users can then
sign in and answer the questions on the survey. The basic requirements are
similar to Wufoo.

Running the app
---------------

Make sure you're running Ruby 2.0 (there's a .ruby-version) and then:

    bundle
    bundle exec rake db:create db:migrate
    bundle exec rails server

Open on http://localhost:3000
