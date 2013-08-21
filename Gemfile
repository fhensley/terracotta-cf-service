source :rubygems

gem 'eventmachine'
gem "em-http-request"
gem "ruby-hmac"
gem "uuidtools"
gem "datamapper", ">= 0.10.2"
gem "dm-sqlite-adapter"
gem "sinatra"
gem "thin"
gem "rest-client"

gem 'vcap_common', :require => ['vcap/common', 'vcap/component'], :git => 'git://github.com/cloudfoundry/vcap-common.git', :ref => '3a0127e77d'
gem 'vcap_logging', :require => ['vcap/logging'], :git => 'git://github.com/cloudfoundry/common.git', :ref => 'b96ec1192'
gem 'vcap_services_base', :git => 'git://github.com/cloudfoundry/vcap-services-base.git', :ref => '9ef28d4bae'
gem 'warden-client', :require => ['warden/client'], :git => 'git://github.com/cloudfoundry/warden.git', :ref => 'fe6cb51'
gem 'warden-protocol', :require => ['warden/protocol'], :git => 'git://github.com/cloudfoundry/warden.git', :ref => 'fe6cb51'

group :test do
  gem "rake"
  gem "rspec"
  gem "simplecov"
  gem "simplecov-rcov"
  gem "ci_reporter"
end
