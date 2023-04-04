source 'https://rubygems.org'

ruby '2.2.5'

gem 'rails', '~> 6.1.7', '>= 6.1.7.3'
gem 'sass-rails', '~> 6.0', '>= 6.0.0'
gem 'uglifier', '~> 2.7.2'
gem 'turbolinks', '~> 5.0.0'
gem 'yajl-ruby', '~> 1.4.2'
gem 'pg',                           '~> 0.18.2'
gem 'sidekiq', '~> 6.2.1'
gem 'sidekiq-throttler', '~> 0.5.1'
gem 'octokit', '~> 4.6.0'
gem 'octicons-rails', '~> 2.1.1'
gem 'actionpack-action_caching', '~> 1.2.1'
gem 'redis',                        '~> 3.2.0'
gem 'puma', '~> 4.3.12'
gem 'httparty', '~> 0.21.0'
gem 'kaminari', '~> 1.2.1'
gem 'dalli', '~> 3.2.3'
gem 'omniauth-github', '~> 2.0.0'
gem 'rorvswild',                    '~> 1.0.0'
gem 'active_model_serializers', '~> 0.9.3'
gem 'swagger-docs', '~> 0.2.9'
gem 'newrelic_rpm',                 '~> 3.9.9.275'
gem 'lograge', '~> 0.3.4'

group :development do
  gem 'quiet_assets', '~> 1.1.0'
  gem 'web-console', '~> 2.2', '>= 2.2.1'
  gem 'spring',                     '~> 1.2.0'
  gem 'capistrano-rails', '~> 1.1.5'
  gem 'capistrano-bundler', '~> 1.1.4'
  gem 'sitemap_generator',          '~> 5.0.5'
  gem 'dotenv-rails', '~> 2.7.6'
  gem 'spring-commands-rspec',      '~> 1.0.4'
end

group :test do
  gem 'rspec-rails', '~> 3.5', '>= 3.5.0'
  gem 'factory_girl_rails', '~> 4.5.0'
  gem 'mocha',                      '~> 1.1.0'
  gem 'fakeredis',                  '~> 0.5.0'
  gem 'webmock', '~> 1.20.4'
  gem 'vcr',                        '~> 2.9.3'
end

group :development, :test do
  gem 'pry-byebug',                  '~> 3.1'
end

group :production do
  gem "sentry-raven",               :git => "https://github.com/getsentry/raven-ruby.git"
end
