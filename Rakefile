#!/usr/bin/env rake
require "bundler/gem_tasks"

require 'rspec/core'
require "rspec/core/rake_task"

Bundler::GemHelper.install_tasks

RSpec::Core::RakeTask.new do |t|
  t.pattern = "./spec/**/*_spec.rb"
end

task default: :spec
