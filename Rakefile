# frozen_string_literal: true

require "bundler/gem_tasks"
require "rake/extensiontask"

task build: :compile

Rake::ExtensionTask.new("hello_rust") do |ext|
  ext.lib_dir = "lib/hello_rust"
end

task default: :compile
