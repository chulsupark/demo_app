source 'http://rubygems.org'

gem 'rails', '3.1.0'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

group :production do
# for heroku
#   $ sudo apt-get install libpq-dev
#   $ bundle install
# try Cedar stack!
#   $ git add .
#   $ git commit -a -m "..."
#   $ git push
#
#   $ heroku create --stack cedar
#   $ git push heroku master
#   $ heroku run db:migrate
#   $ heroku restart
#   $ heroku db:push
#
  gem "pg"
end

group :development, :test do
	gem 'sqlite3'

#PCS
# 3.1.0 problems on Ubuntu
	gem 'execjs'
	gem 'therubyracer'
#PCS_END
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

gem 'jquery-rails'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

group :test do
  # Pretty printed test output
  gem 'turn', :require => false
end
