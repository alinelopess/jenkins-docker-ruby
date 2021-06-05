# jenkins-docker-ruby
Code for the QAaninja academy "Continuous testing with jenkins and ruby" course

## How to run the project

ruby (version 2.5 or higher),
chromedriver/geckodriver,
docker

### Install Bundler

gem install bundler

### Install Ruby dependencies (project)

bundle install

### Run it locally (my machine)

bundle exec cucumber

### Run it on the CI server (generating JSON reports)

bundle exec cucumber -p ci
