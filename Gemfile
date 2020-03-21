source 'https://rubygems.org'

gem 'rails', '5.2.4.2'

# Use postgresql as the database for Active Record
gem 'pg'
gem 'pg_search'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0.6'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Explicitly include Nokogiri to control version
gem 'nokogiri', '>= 1.8.1'

# Use jquery as the JavaScript library
gem 'jquery-rails', '>= 4.1.1'
gem 'jquery-ui-rails', '>= 5.0.5'

# Inline js validations
gem 'client_side_validations', '>= 11.1.0'
gem 'client_side_validations-simple_form', '>= 6.6.0'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '~> 2.5.3'
gem 'jquery-turbolinks', '~> 2.1.0'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'

# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 1.0.0', group: :doc

# Summernote is the wysiwyg editor
gem 'jquery-minicolors-rails', '>= 2.2.3.0'
gem 'summernote-rails', '>= 0.8.3.0'
gem 'codemirror-rails', '>= 5.16.0'

# Ranked model gives the ability to rank articles and categories
gem 'ranked-model'

# Google Analytics Measurement Protocol
gem 'staccato'

gem "rails-settings-cached", "~> 0.5", ">= 0.5.6"
gem 'sucker_punch', '~> 2.0'

# Charting
gem "groupdate"
gem "chartkick"

# Auth Gems
gem 'devise', '>= 4.4.2'
gem 'devise-i18n'
gem 'devise-bootstrap-views'
gem 'omniauth'
gem 'omniauth-github'
gem 'omniauth-twitter', '>= 1.3.0'
gem 'omniauth-google-oauth2'
gem 'omniauth-facebook'

# i18n gems
gem 'rails-i18n', '~> 5.0.0'
gem 'i18n-country-translations', '>= 1.2.3'
gem 'route_translator', '>= 5.6.0'
gem 'http_accept_language'

# API gems
gem 'grape'
gem 'grape-swagger'
gem 'grape-entity'
gem 'grape-swagger-rails', '>= 0.3.0'
gem 'grape-swagger-entity'
gem 'grape-attack'
gem 'grape-kaminari', '>= 0.1.9'
gem 'rack-cors', :require => 'rack/cors'

gem 'permalink_fu'
gem 'paper_trail'

gem 'acts-as-taggable-on', '~>3.5'

gem 'kaminari', '>= 0.16.3'
gem 'kaminari-i18n', '>= 0.4.0'

gem 'globalize-versioning'
gem 'globalize-accessors'

gem 'gravtastic'

# File handling
gem 'cloudinary', '1.1.2'
gem 'attachinary', '>= 1.3.1'

gem 'carrierwave', '~> 1.0.0'
gem "jquery-fileupload-rails", ">= 0.4.7"
gem 'mini_magick'

# Bootstrap/UI Gems
gem 'font-awesome-sass'
gem 'bootstrap-sass'
gem 'bootstrap_form'
gem 'simple_form', '>= 4.0.0'
gem 'twitter-bootstrap-rails', '>= 3.2.2'
gem 'twitter-bootstrap-rails-confirm'
gem 'rdiscount'
gem 'selectize-rails'
gem "bootstrap-switch-rails"
gem 'bootstrap-datepicker-rails', '>= 1.6.4.1'
gem 'bootstrap-select-rails'

gem 'config', '~> 1.1.0', git: 'https://github.com/railsconfig/config.git'

# Email/Mail Handling
gem 'daemons'
gem 'mailman'#, require: false
gem 'mail_extract'

gem 'griddler', '>= 1.3.1'
gem 'griddler-mandrill', '>= 1.1.3'
gem 'griddler-sendgrid', '>= 0.0.1'
gem 'griddler-mailgun', '>= 1.0.2'
gem 'griddler-postmark', '>= 1.0.0'
gem 'griddler-mailin', '>= 0.0.1'
gem 'griddler-sparkpost', '>= 0.0.1'

gem 'rails-timeago', '>= 2.13.0'

gem 'devise_invitable', '~> 1.6', '>= 1.6.0'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Faker is used for the populate script to create demo data
gem 'faker'

gem 'timecop' #used to populate

gem 'themes_on_rails', '>= 0.4.0'
gem "recaptcha", "2.0.0"

gem 'best_in_place', '~> 3.0.3'

# Add onboarding component
gem 'helpy_onboarding', path: 'vendor/helpy_onboarding'

group :development, :test do
  # Audit Gemfile for security vulnerabilities
  gem 'bundler-audit', require: false
  gem 'byebug'
  gem 'pry'
  gem 'pry-byebug'
  gem 'spring', '~> 1.4.0'
  gem 'annotate'
  gem 'brakeman', require: false
  gem 'rubocop'
  gem 'scss-lint'
  gem 'awesome_print'
end

gem 'bulk_insert'
gem 'roo'

group :development do
  gem "better_errors"

  # Check Eager Loading / N+1 query problems
  gem 'bullet'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.3', '>= 2.3.0'
end

group :test do
  gem 'minitest'
  gem 'minitest-reporters'
  gem 'shoulda'
  gem 'factory_girl_rails', '>= 4.7.0'
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'launchy'
  gem "codeclimate-test-reporter", ">= 0.5.0", require: nil
  gem 'simplecov', '>= 0.12.0', :require => false

  # remove this for Rails 5 because the function is already included
  gem 'test_after_commit'
end

group :production do
  # Uncomment this gem for Heroku:
  # gem 'rails_12factor'
  gem 'unicorn'
end

ruby '>= 2.2', '< 3.0'
