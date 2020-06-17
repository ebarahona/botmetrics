source 'https://rubygems.org'
ruby '2.3.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '5.0.0'
# Use postgresql as the database for Active Record
gem 'pg',    '~> 0.18.4'

# Use jquery as the JavaScript library
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks',    '~> 5.0.0.beta'
gem 'excon',         '~> 0.49.0'
gem 'with_advisory_lock',       '~> 3.0.0'
gem 'local_time', '~> 1.0.3'
gem 'haml',                     '~> 4.0.6'
gem 'sass-rails', '~> 5.0.6'
gem 'bootstrap-sass',           '~> 3.3.7'
gem 'font-awesome-sass',        '~> 4.6.2'
gem 'autoprefixer-rails',       '~> 6.5.0'
gem 'jquery-rails', '~> 4.4.0'
gem 'coffee-rails', '~> 4.2.1'
gem 'jquery-ui-rails', '~> 5.0.5'
gem 'simple_form', '~> 3.2.1'
gem 'cocoon',                   '~> 1.2.9'
gem 'modernizr-rails',          '~> 2.7.1'
gem 'kramdown',                 '~> 1.11.1'

# Dashboard stuff
gem 'groupdate',                '~> 2.5.3'
gem 'chartkick',                github: 'botmetrics/chartkick', ref: '92cc9566c0b4fe2c2db36da20b4d4f2599f23e3d'

# Auth
gem 'devise', '~> 4.0.0'
gem 'jwt',                      '~> 1.5.4'
gem 'devise_invitable', '~> 1.6.1'

# Pagination
gem 'will_paginate',            '~> 3.1.0'
gem 'will_paginate-bootstrap',  '~> 1.0.1'

# Redis
gem 'relax-rb',                 '~> 0.5.0', require: 'relax'
gem 'sidekiq', '~> 4.1.4'
gem 'sinatra', '~> 2.0.0'
gem 'redis-namespace',          '~> 1.5.2'
gem 'pusher',                   '~> 0.15.1'

gem 'passenger', '~> 5.0.30'

gem 'json-stream',              '~> 0.2.1', require: 'json/stream'

# Cron
gem 'clockwork'

gem 'font_assets', '~> 0.1.14'

gem 'rollbar',                  '~> 2.13.2'

gem 'validate_url',             github: 'perfectline/validates_url', ref: '0844e25', require: 'validate_url'

group :development do
  gem 'foreman',                  '~> 0.82.0'
  gem 'quiet_assets', '~> 1.1.0'
  gem 'git',                      '~> 1.3.0'
  gem 'parity',                   '~> 0.9.3'
  gem 'letter_opener'
  gem 'derailed', '~> 0.1.0'
end

group :development, :test do
  gem 'dotenv',                   '~> 2.1.1'
  gem 'rspec-rails', '~> 3.5.0'
  gem 'rspec-its',                '~> 1.2.0'
  gem 'byebug',                   '~> 2.0.0'
  gem 'timecop',                  git: 'https://github.com/steakknife/timecop', ref: '8371a3abe23d93bbf2a68499fdf73a11587d042d'
  gem 'factory_girl_rails', '~> 4.5.0'
  gem 'faker',                    '~> 1.6.6'
  gem 'pry-rails'
end

group :test do
  gem 'database_cleaner',         '~> 1.3.0'
  gem 'shoulda-matchers',         '~> 3.1.1', require: false
  gem 'webmock',                  '~> 1.22.3'
end

group :production do
  gem 'rails_12factor',           '~> 0.0.3'
  gem 'newrelic_rpm',             '~> 3.9.9'
  gem 'bugsnag',                  '~> 2.8.13'
  gem 'lograge', '~> 0.3.6'
end

group :assets do
  gem 'uglifier',                 '~> 2.7.1'
end
