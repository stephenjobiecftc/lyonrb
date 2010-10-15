source 'http://rubygems.org'

gem 'rails', '3.0.1'

group :production do
  gem 'pg', '0.9.0'
end
group :development do
  gem 'sqlite3-ruby', :require => 'sqlite3'
end

gem 'warden'
gem 'devise', "1.1.2"

gem 'haml'
gem 'rdiscount'
gem 'nokogiri'
gem 'icalendar'

# Camille est pas fan de Rack::Offline (comme je balance! :p)
#gem 'rack-offline', :git => "http://github.com/wycats/rack-offline.git"


gem 'launchy'    # So you can do Then show me the page

group :test do
	gem "rspec", '2.0.0'
	gem "rspec-rails", '2.0.0'
	
	gem 'spork'
	gem 'capybara'
	gem 'cucumber'
	gem 'cucumber-rails'
	
	gem 'database_cleaner'
	gem 'factory_girl', :git => "http://github.com/thoughtbot/factory_girl.git"
	gem 'fakeweb'
	gem 'timecop', :git => 'http://github.com/jtrupiano/timecop.git'
end
