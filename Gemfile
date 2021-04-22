# frozen_string_literal: true

source "https://rubygems.org"
ruby "2.7.1"

# See: https://github.com/sass/sassc-rails/issues/114
gem "sassc-rails"

# Use jquery as the JavaScript library
gem "jquery-rails"
# Use MongoDB as the database, and mongoid as our ORM for it. This version of
# mongoid supports MongoDb 3.6
gem "mongoid", "~> 7.1.5"
# Bundle edge Rails instead: gem "rails", github: "rails/rails"
gem "rails", ">= 6.0.3"
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem "turbolinks"
# Use Uglifier as compressor for JavaScript assets
gem "uglifier", ">= 1.3.0"

# bundle exec rake doc:rails generates the API under doc/api.
gem "sdoc", "~> 1.1.0", group: :doc

# Use CanCanCan for user roles and permissions
# Version 2.0 doesn't support Mongoid, so we're locked to an earlier one
gem "cancancan", "~> 1.10"

# Use Devise for user authentication
gem "devise", ">= 4.4.3"
gem "devise_invitable", "~> 1.7.0"

# GOV.UK styling
gem "govuk_elements_rails", "~> 3.1"
gem "govuk_template", "~> 0.23"

# Use High Voltage for static pages
gem "high_voltage", "~> 3.0"

# Use Kaminari for pagination
gem "kaminari", "~> 1.1"
gem "kaminari-mongoid", "~> 1.0"

gem "secure_headers", "~> 5.0"

gem "wicked_pdf"

# Use the waste carriers engine for the user journey
gem "waste_carriers_engine",
    git: "https://github.com/DEFRA/waste-carriers-engine",
    branch: "feature/send-pending-payment-with-notify"

# Use the defra ruby mocks engine to add support for mocking external services
# in live environment. Essentially with this gem added and enabled the app
# also becomes a 'mock' for external services like companies house.
# This then allows us to performance test our services without fear of being
# reported for causing undue loads on the external services we use.
# With the environment properly configured, when any app in an environment needs
# to call Companies House, instead it will call this app which will mock the end
# point and return the response expected.
gem "defra_ruby_mocks"

# Allows us to automatically generate the change log from the tags, issues,
# labels and pull requests on GitHub. Added as a dependency so all dev's have
# access to it to generate a log, and so they are using the same version.
# New dev's should first create GitHub personal app token and add it to their
# ~/.bash_profile (or equivalent)
# https://github.com/skywinder/github-changelog-generator#github-token
# Then simply run `bundle exec rake changelog` to update CHANGELOG.md
# Should be in the :development group however when it is it breaks deployment
# to Heroku. Hence moved outside group till we can understand why.
gem "github_changelog_generator", require: false

# Defines a route for ELB healthchecks. The healthcheck is a piece of Rack
# middleware that does absolutely nothing, so it is faster than just using the
# default `/` route, or `/version` as was previously used.
# The app now returns a 200 from `/healthcheck`
# Test with `curl -I http://localhost:3002/healthcheck`
gem "aws-healthcheck"

group :production do
  # Web application server that replaces webrick. It handles HTTP requests,
  # manages processes and resources, and enables administration, monitoring
  # and problem diagnosis. It is used in production because it gives us an ability
  # to scale by creating additional processes, and will automatically restart any
  # that fail. We don't use it when running tests for speed's sake.
  gem "passenger", "~> 5.0", ">= 5.0.30", require: "phusion_passenger/rack_handler"
end

group :development, :test do
  # Call "byebug" anywhere in the code to stop execution and get a debugger console
  gem "byebug"
  # Apply our style guide to ensure consistency in how the code is written
  gem "defra_ruby_style"
  # Shim to load environment variables from a .env file into ENV in development
  # and test
  gem "dotenv-rails"
  # Project uses RSpec as its test framework
  gem "rspec-rails"
end

group :development do
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem "spring"
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem "web-console"
end

group :test do
  gem "database_cleaner-mongoid"
  gem "factory_bot_rails"
  gem "rails-controller-testing"

  # Generates a test coverage report on every `bundle exec rspec` call. We use
  # the output to feed SonarCloud's stats and analysis
  gem "simplecov", "~> 0.17.1", require: false
end
