source 'https://rubygems.org'

gem 'oj', '~> 3.0'
gem 'rake'
gem 'request_store'
gem 'parallel'
gem 'json-ld'
gem 'jwt'

# NCBO
gem 'goo', github: 'agroportal/goo', branch: 'chore/ruby-3.4.12'
gem 'ncbo_annotator', github: 'agroportal/ncbo_annotator', branch: 'master'
gem 'ontologies_linked_data', github: 'agroportal/ontologies_linked_data', branch: 'chore/ruby-3.4.12'

# agroportal ontologies_linked_data requires net/ftp, a bundled gem since Ruby 3.1
gem 'net-ftp'

group :development do
  gem 'ontoportal_testkit', github: 'agroportal/ontoportal_testkit', branch: 'chore/ruby-3.4.12-bookworm'
  gem 'minitest'
  gem 'pry'
  gem 'simplecov'
  gem 'simplecov-cobertura' # for codecov.io
end
