source 'https://rubygems.org'

gem 'bourbon'
gem 'guard'
gem 'guard-sass'
gem 'bourbon'

# Notifiers
case RUBY_PLATFORM
when /linux/i
  gem 'libnotify'
when /darwin/i
  gem 'rb-fsevent', require: false
  gem 'growl'
  gem 'terminal-notifier-guard'
when /mswin(?!ce)|mingw|cygwin|bccwin/i
  gem 'rb-notifu'
  gem 'win32console'
  gem 'wdm'
end
