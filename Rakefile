require 'rake/testtask'

Rake::TestTask.new do |t|
  t.libs.push 'test'
  t.pattern = 'test/**/test_*.rb'
  t.verbose = true
end

task :default => :test
