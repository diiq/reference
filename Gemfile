source 'https://rubygems.org'
 ruby "2.3.1"

# Rails
gem "rails"
gem "pg"
gem "rack-cors"
gem "jbuilder"

gem "devise", "~> 4.1.1"
gem "devise_token_auth", github: "lynndylanhurley/devise_token_auth"
gem "omniauth"

# Workers
gem "resque"
gem "aws-sdk"
gem "paperclip", git: "https://github.com/thoughtbot/paperclip"

group :production do
  gem 'rails_12factor'
end 

group :test, :development do
  gem 'dotenv-rails'
end

group :test do
  gem "rspec-rails"
  gem "spring-commands-rspec"
  gem "factory_girl"
  gem "timecop"
end

group :development do
  gem "pry"
  gem "spring"
  gem 'guard-rspec'
end

group :darwin do 
  gem 'rb-fsevent'
end
