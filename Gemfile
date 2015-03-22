
source (ENV['RUBYGEMS_MIRROR'] or 'https://rubygems.org')
ruby '1.9.3'
# the node/service architecture is built with sinatra
gem 'sinatra', '1.4.4'

# ...and hosted by Thin.
gem 'thin', '1.6.1'

# used to generate UUIDs for service names
gem 'uuidtools', '2.1.4'
gem 'ruby-hmac', '0.4.0'

# an ORM for saving services to a database
gem 'datamapper', '1.2.0'
gem 'dm-sqlite-adapter', '1.2.0'
gem 'do_sqlite3', '0.10.13'

# The NATS message bus
gem 'nats', '0.5.0.beta12'

# Used to work with elasticsearch
gem 'elasticsearch', '0.4.1'


# cloudfoundry-specific gems for logging and for providing
# us with some basic foundation for our service.
gem 'steno-codec-text'  ,      '0.1', :path => "../filesystem/vendor/bundle/ruby/1.9.1/gems/steno-codec-text-0.1"
gem 'vcap_common'       ,    '3.0.0', :path => '../mysql/vendor/cache/common', :require => ['vcap/common', 'vcap/component']
gem 'vcap_services_base', '0.2.6', :path => "../base"
gem 'vcap_logging', '>=0.1.3', :require => ['vcap/logging']
# stackato's vcap_common relies on eventmachine for event-based triggers
gem 'eventmachine', '1.0.3'
gem 'em-http-request', '1.1.1'
