source "https://rubygems.org"

# Specify your gem"s dependencies in kitchen-ec2.gemspec
gemspec
gem "test-kitchen"
gem "winrm-transport"
gem "winrm-fs"
gem "activesupport", "~> 4.0"
gem "faraday-http-cache", "~> 1.3"

group :test do
  gem "rake", "< 12"
  gem "pry"
end

group :development do
  gem "github_changelog_generator"
end
