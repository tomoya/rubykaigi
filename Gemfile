# -*- coding: utf-8 -*-
source :rubygems
source 'http://gems.github.com'

gem 'rails', '3.0.6', :require => nil
gem 'rake', '~> 0.8.7'
gem 'jquery-rails', '>= 0.2.6'
gem 'mysql'
gem 'configatron'
gem "ambethia-smtp-tls", :require => "smtp-tls"
gem "fastercsv"
gem "hoptoad_notifier"
gem 'i18n_generators'
gem 'haml'
gem 'sass'
gem 'fastercsv'
gem 'whenever', '0.6.7', :require => false
gem 'delayed_job'
gem 'rack-google-analytics', '0.6.1'
gem 'will_paginate'
gem 'redis-objects', :require => 'redis/objects'
gem 'SystemTimer'
gem 'twitter', '0.9.8'

gem 'rails_warden'
gem 'warden_oauth'
gem 'warden-openid'

gem 'ri_cal', :git => "git://github.com/ctide/ri_cal.git"

group :development do
  gem 'capistrano', :require => nil
  gem 'capistrano-ext', :require => nil
  gem 'capistrano-notification', :require => nil
  gem 'gettext', '<2' # required by i18n_generators
  gem 'thin', :require => nil
end

group :test, :cucumber do
  gem 'rspec', '2.5.0'
  gem 'rspec-rails', '2.5.0', :group => :development
  gem 'rr'
  gem 'machinist', :require => 'machinist/active_record'
  gem 'faker'
  gem 'email_spec', '0.6.3'
  gem 'autotest-rails'
#  gem 'autotest-growl'
  gem 'daemons'
  gem 'spork', :group => :development
  gem 'cucumber-rails', '~>0.3.2'
  gem 'webrat'
  gem 'moro-miso'
  gem 'database_cleaner'
  gem 'nokogiri'
  gem 'steak', :group => :development
  gem 'capybara', :group => :development
end
