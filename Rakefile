require 'rubygems'
require 'rake'
require "rspec/core/rake_task"

task :default => [:core]

RSpec::Core::RakeTask.new(:core) do |spec|
    spec.pattern = 'spec/**/*_spec.rb'
      spec.rspec_opts = ['--backtrace']
end
