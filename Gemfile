source 'http://rubygems.org'

gem 'rails', '3.1.3'
gem 'gravatar_image_tag'
gem 'jquery-rails'

group :development do
gem 'rspec-rails', '2.0.1'
gem 'annotate', :git => 'git://github.com/jeremyolliver/annotate_models.git',
    :branch => 'rake_compatibility'

end

group :test do
  # Pretty printed test output
gem 'rspec', '2.0.1'
gem 'webrat', '0.7.1'
gem 'spork', '0.8.4'
gem 'factory_girl_rails'
end

group :production do
  gem 'pg'
end

group :development, :test do
  gem 'sqlite3'
end

