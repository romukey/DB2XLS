source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

group :production, :development do
  gem 'dotenv'
  gem 'mysql2'
  gem 'spreadsheet'
  gem 'activesupport'
end

group :development, :test do
  gem 'pry'
  gem 'test-unit'
end
