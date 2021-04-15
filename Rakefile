require 'rake-jekyll'

require 'rspec/core/rake_task'
task :default => :spec
RSpec::Core::RakeTask.new

# This task builds the Jekyll site and deploys it to a remote Git repository.
# It's preconfigured to be used with GitHub and Travis CI.
# See http://github.com/jirutka/rake-jekyll for more options.
Rake::Jekyll::GitDeployTask.new(:deploy) do |t|
    t.committer = 'Jekyll Publisher <jekyll@example.com>'
end
