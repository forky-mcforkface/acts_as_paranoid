source "http://rubygems.org"

gem "activerecord", "~>8.0"

# Development dependencies
gem "rake"
gem "activesupport", "~>8.0"

platforms :ruby do
  gem "sqlite3"
end

platforms :jruby do
  gem "activerecord-jdbcsqlite3-adapter"
end

group :test do
  gem "minitest"
  gem "autotest-growl"
end
