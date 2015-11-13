source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.4'

gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
# gem 'coffee-rails', '~> 4.1.0'

# Use jquery as the JavaScript library
gem 'jquery-rails'

gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'bootstrap-sass', '~> 3.0.3.0'

# Images
gem 'carrierwave', github: 'carrierwaveuploader/carrierwave'
gem 'fog'
gem 'mini_magick'
#Necessary for AWS
gem 'cliver', :git => 'git://github.com/yaauie/cliver', :ref => '5617ce'

# Auth

gem 'devise'
gem 'omniauth'
gem 'omniauth-facebook'

# Misc
# gem "wysiwyg-rails", "2.0.0.pre.rc.3"
gem 'bootsy'
gem 'geocoder'
# gem "simple_calendar", "~> 1.1.0"
gem "simple_calendar", "~> 2.0"
gem "font-awesome-rails"
gem "rest-client"

# gem 'jquery-tablesorter'

gem 'farm_slugs', :git => 'https://github.com/jessethebuilder/farm_slugs'

gem 'twitter_express', :git => 'https://github.com/jessethebuilder/TwitterExpress'
# gem 'twitter_express', :path => 'C:\Users\Bucky\Desktop\jesseweb\twitterexpress\twitterexpress'

# gem 'farm_shed', '0.0.2', :path => 'C:\Users\Bucky\Desktop\jesseweb\farm_shed'
gem 'farm_shed', '0.0.2', :git => 'https://github.com/jessethebuilder/farm_shed'

# gem 'sdad', '0.0.1', :path => 'c:\Users\Bucky\Desktop\jesseweb\sdad'
gem 'sdad', '0.0.1', :git => 'https://github.com/jessethebuilder/sdad'

gem 'meta_farm', '0.0.1', :git => 'https://github.com/jessethebuilder/meta_farm'
# gem 'meta_farm', '0.0.1', :path => 'c:/users/bucky/desktop/jesseweb/meta_farm'

gem 'farm_gals', '0.0.1', :git => 'https://github.com/jessethebuilder/farm_gals'
# gem 'farm_gals', '0.0.1', :path => 'c:\Users\Bucky\Desktop\jesseweb\farm_gals'




# eCommerce
# gem 'shoppe', '~> 1.0'


group :test, :development do
  gem 'faker'
  gem 'rspec-rails'
  gem 'wdm'
  gem 'database_cleaner', '~> 1.0.0rc'
  gem 'timecop'
end

group :test do
  gem 'factory_girl_rails'
  gem 'capybara'
  gem 'guard-rspec'
  gem 'selenium-webdriver'
  gem 'shoulda'
  gem 'launchy', '~> 2.4.0'
  gem 'poltergeist' 
  #gem 'webrat'
end

group :production do
  gem 'rails_12factor'
  gem 'faker'
end
