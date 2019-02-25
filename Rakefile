desc "Build the site with the production configuration."
task :build do
     system ("bundle exec jekyll build")
end

namespace :assets do
    desc "Rake task that Heroku runs to build static assets by default. "
    task :precompile => :build
end