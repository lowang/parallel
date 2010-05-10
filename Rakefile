task :default => :spec
require 'spec/rake/spectask'
Spec::Rake::SpecTask.new {|t| t.spec_opts = ['--color']}

begin
  require 'jeweler'
  project_name = 'lowang-parallel'
  Jeweler::Tasks.new do |gem|
    gem.name = project_name
    gem.summary = "Run any kind of code in parallel processes"
    gem.email = "przemyslaw.wroblewski@gmail.com"
    gem.homepage = "http://github.com/lowang/#{project_name}"
    gem.authors = ["Michael Grosser", "Przemyslaw Wroblewski"]
  end

  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler, or one of its dependencies, is not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"
end