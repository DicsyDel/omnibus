source "https://rubygems.org"

gemspec

gem "chef-utils", path: "../chef/chef-utils"

group :docs do
  gem "yard"
  gem "redcarpet"
  gem "github-markup"
end

group :debug do
  gem "pry"
  gem "pry-byebug"
  gem "pry-stack_explorer"
end

if Gem::Version.new(RUBY_VERSION) < Gem::Version.new("2.5")
  gem "ohai", "<15"
end
