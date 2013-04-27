source 'https://rubygems.org'

gem 'bourbon'
gem 'guard'
gem 'guard-sass'
gem 'bourbon'
gem 'pry'

gem 'rb-fsevent', require: false if RUBY_PLATFORM =~ /darwin/i # mac os x

# Notifiers
case RUBY_PLATFORM
when /linux/i
  gem 'libnotify'
when /darwin/i
  gem 'growl'
  gem 'terminal-notifier-guard'
when /mswin(?!ce)|mingw|cygwin|bccwin/i
  gem 'rb-notifu'
end
