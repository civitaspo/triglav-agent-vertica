require "bundler/gem_tasks"
require "rspec/core/rake_task"

require 'rake/testtask'
desc 'Run test_unit based test'
Rake::TestTask.new(:test) do |t|
  t.libs << "test"
  t.test_files = Dir["test/**/test_*.rb"].sort
  t.verbose = false
  t.warning = false
end
