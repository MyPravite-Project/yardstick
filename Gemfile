source :rubygems

gem 'yard', '~> 0.7.0'

group :development do
  gem 'jeweler', '~> 1.6.0'
  gem 'rake',    '~> 0.8.7'
  gem 'rspec',   '~> 1.3.2'
end

group :jruby do
  platform :jruby do
    gem 'jruby-openssl', '~> 0.7.4'
  end
end

platforms :mri_18 do
  group :quality do
    gem 'flay',      '~> 1.4.2'
    gem 'flog',      '~> 2.5.1'
    gem 'heckle',    '~> 1.4.3'
    gem 'json',      '~> 1.5.1'
    gem 'metric_fu', '~> 2.1.1'
    gem 'mspec',     '~> 1.5.17'
    gem 'rcov',      '~> 0.9.9'
    gem 'reek',      '~> 1.2.8', :git => 'git://github.com/dkubb/reek.git'
    gem 'roodi',     '~> 2.1.0'
    gem 'ruby2ruby', '=  1.2.2'
  end
end