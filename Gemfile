# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
source 'http://rubygems.org'

gem "middleman", "~>3.3.3"

# Live-reloading plugin
gem "middleman-livereload", "~> 3.1.0"
gem "ffi", "~> 1.9.9"

# For faster file watcher updates on Windows:
gem "wdm", "~> 0.1.0", :platforms => [:mswin, :mingw]

# Windows does not come with time zone data
gem "tzinfo-data", platforms: [:mswin, :mingw]

require 'rbconfig'
if RbConfig::CONFIG['target_os'] =~ /(?i-mx:bsd|dragonfly)/
   gem 'rb-kqueue', '>= 0.2.4'
end
