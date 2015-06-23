# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.
require 'rubygems'
require File.expand_path('../config/application', __FILE__)
gem 'ci_reporter'
require 'ci/reporter/rake/test_unit'
Rails.application.load_tasks
