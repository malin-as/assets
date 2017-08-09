source 'https://rubygems.org'
gemspec

unless ENV['TRAVIS']
  gem 'byebug', require: false, platforms: :mri
  gem 'yard',   require: false
end

gem 'hanami-utils',   '1.1.0.beta1', git: 'https://github.com/hanami/utils.git',   branch: 'develop'
gem 'hanami-helpers', '1.1.0.beta1', git: 'https://github.com/hanami/helpers.git', branch: 'develop'
gem 'hanami-view',    '1.1.0.beta1', git: 'https://github.com/hanami/view.git',    branch: 'develop'

gem 'hanami-emberjs',        path: 'spec/support/fixtures/hanami-emberjs',        require: false
gem 'hanami-compass',        path: 'spec/support/fixtures/hanami-compass',        require: false
gem 'hanami-foo-compressor', path: 'spec/support/fixtures/hanami-foo-compressor', require: false

gem 'rubocop', '0.48.0', require: false
gem 'coveralls',         require: false
