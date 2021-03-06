source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.7'
gem 'i18n', '~> 0.6'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'

gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

gem 'aasm'

gem 'lodash-rails'
gem 'local_time'
gem 'redis', '~> 3.0'

gem 'devise'
gem 'devise_invitable'
gem 'rolify'
gem 'cancancan', '~> 1.15'

gem 'paper_trail'

gem 'bootstrap-sass', '~> 3.3.6'

gem 'friendly_id', '~> 5.1.0'

gem 'slim-rails'

gem 'sidekiq'
gem 'sinatra', github: 'sinatra/sinatra', require: nil
gem 'sidekiq-statistic'

gem 'gravatar_image_tag'
gem 'country_select'
gem 'kaminari'

gem 'money-rails'

gem 'ransack'

gem 'slack-notifier'

gem 'premailer-rails'
gem 'griddler'
gem 'griddler-mailgun'

gem 'rollbar'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  gem 'rspec-rails', '~> 3.5'
  gem 'spring-commands-rspec'
  gem 'capybara'
  gem 'rails-controller-testing'
  gem 'faker'
  gem 'database_cleaner'
  gem 'poltergeist'
  gem 'shoulda-matchers', '~> 3.0'
  gem 'vcr'
  gem 'webmock'
end

gem 'simplecov', :require => false, :group => :test
gem 'factory_bot_rails', '~> 4.0'

group :development do
  gem 'foreman'
  gem "letter_opener"
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'rack-cors', :require => 'rack/cors'