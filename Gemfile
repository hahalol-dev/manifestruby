# source :gemcutter
Encoding.default_external = Encoding::UTF_8
source 'https://rubygems.org'

ruby "2.6.9"

# gems not bundled in ruby by default
gem "rake", "13.0.6"
gem "net-telnet", "~> 0.1.1"

gem "rails", "6.1.7.8"
gem 'rack-cors', '~> 1.0.4'

# gem 'next_rails'
gem 'karafka', '2.2.10'

gem 'rugged', "0.27.4", require: false
gem 'hashdiff', "0.3.7", require: false

gem "freemail", "0.2.0", require: false
gem 'rbtrace', require: false

gem "json", "2.3.0"
gem 'jbuilder', "2.9.1"

gem 'yajl-ruby', '1.4.1', require: 'yajl'
gem 'blueprinter', '0.19.0'
gem 'docx', '~> 0.7.0'
gem 'turbo-sprockets-rails4'

#SSL Service Gem
gem 'fcm', git: 'git@github.com:freshdesk/cert_management.git', tag: 'v0.91.0', glob: 'clients/fcm_ruby/src/fcm.gemspec'

# gem 'strong_parameters', "0.2.3" # Used for API params validation

# rails update - deprecated behaviors moved to gems
gem "protected_attributes_continued"
# ActiveModel::Serializers::Xml has been extracted from Rails to the activemodel-serializers-xml gem
gem "activemodel-serializers-xml"

gem "mini_magick", "4.12.0"

gem 'actionpack-action_caching'
gem 'rails-deprecated_sanitizer'
gem 'actionpack-xml_parser'

gem "mysql2", "0.5.2"

#For instrumenting cache-performance
gem "time_bandits", git: "git@github.com:freshdesk/fd_time_bandits", tag: 'v1.6'

gem "white_list", git: "https://github.com/neubloc/white_list"

gem "will_paginate", "3.1.7"

gem "acts_as_list", "0.9.5"
gem 'typhoeus', '0.7.3'
gem 'prototype-rails', git: 'https://github.com/voxmedia/prototype-rails.git'

gem "dynamic_form", git: 'https://github.com/GoodMeasuresLLC/dynamic_form.git'
gem "prototype_legacy_helper", '0.0.0', git: "https://github.com/rails/prototype_legacy_helper"
gem 'rack-ssl', require: 'rack/ssl', git: 'https://github.com/freshdesk/rack-ssl', branch: 'ssl'
gem 'rack-uri_sanitizer'

gem "sneaky-save", git: "https://github.com/realdlee/sneaky-save", branch: 'master'

gem 'memoize_until', '1.2.1'

gem 'record_not_unique', git: 'git@github.com:freshdesk/record_not_unique.git', tag: 'v1.1.0'

gem "migration_templates", git: 'git@github.com:freshdesk/migration_templates.git', tag: 'v1.1.0'

gem 'fresh_request', git: 'git@github.com:freshdesk/fresh_request.git', :branch => 'release'
gem 'moneta', '1.1.0'
gem 'circuitbox', '2.0.0.pre2'
gem 'iconv', "1.0.8"

gem "redis_display_id", git: 'git@github.com:freshdesk/redis_display_id.git', tag: 'v1.0.3'

gem "mail", "2.8.1"
gem "i18n", "1.14.1"
gem "i18n-js", "3.2.3"
gem "RedCloth", "4.3.2"
gem "authlogic", "~> 6.3.0"
gem "request_store", "~> 1.0"
gem "httparty", "0.10.0"
gem "omniauth", "1.9.1"
gem "omniauth-oauth", "1.0.1"
gem "tzinfo", '~> 2.0'
gem 'rails_autolink', '1.1.6'

gem 'retriable', '3.0.1'

gem "omniauth-oauth2", "1.2.0"
gem "omniauth-openid", "1.0.1"
# TODO-RAILS3 need check are we still using this
gem "omniauth-google", "1.0.2"
gem "omniauth-google-oauth2", "0.1.13"
gem "omniauth-quickbooks", "0.0.2"
gem "yam", git: "https://github.com/pizza/yam", branch: "master"

gem "omniauth-mailchimp", "1.0.3"
gem "omniauth-constantcontact2", "1.0.4"

gem "google-api-client", "~> 0.7.0"
gem 'googleauth', '~> 0.4.0'
gem 'omniauth-oauth2-manifold', git: 'git@github.com:freshdesk/omniauth-oauth2-manifold.git', tag: 'v1.1.1'
gem "ipaddress", "0.8.0"

gem 'sidekiq', "5.2.8"
gem 'lego-gem', git: 'git@github.com:freshdesk/custom-objects-gem.git', branch: 'logger_for_keep_alive'
# This needs bundler 1.7.2 or 1.10.6 as other version has problem in resolving.
# Get the gem_contribsys key from FWSS and run below command to pull sidekiq pro gem
# bundle config gems.contribsys.com <value from FWSS>
source 'https://gems.contribsys.com/' do
  gem "sidekiq-pro", "4.0.5"
end

gem 'shoryuken', '6.1.1'
gem "soap4r-ruby1.9", "~> 2.0.5"
gem "jira4r", "0.3.0"
gem "ruby-openid", git: "https://github.com/freshdesk/ruby-openid", require: "openid"
gem "ruby-openid-apps-discovery", "1.2.0"

gem "ruby-saml", "1.7.0"

gem "rubyzip", "2.0.0"
gem "zip-zip"

gem "http_accept_language", "~> 2.0.1"

gem "faraday" , "0.9"
gem 'faraday_middleware', '~> 0.10.0'
gem "sanitize", '~> 6.1.0'
gem "spreadsheet", "0.6.8"

gem "sax-machine", "~> 0.1.0"

gem "redis","3.3.5"
gem "redis-namespace", "1.5.2"

# resque gems - to be cleaned up when deprecating old reports
gem "resque","~> 1.25.0"
gem 'resque-scheduler', "2.3.0"

gem "resque-status", "0.4.1"
gem "log_filter", path: "#{File.expand_path(__FILE__)}/../vendor/gems/log_filter"
# resque gems

gem 'encryptor', '1.1.3'
gem "dalli", '~> 3.2'
gem 'ice_cube', '~> 0.16'
# gem "deadlock_retry", git: "https://github.com/freshdesk/deadlock_retry"
gem "lhm", git: "https://github.com/freshdesk/large-hadron-migrator", tag: 'v1.1.0.5', require: false
gem "rinku", git: "https://github.com/freshdesk/rinku"

gem "namae", '0.8.4'
gem 'ancestry', '4.3.3'
gem "useragent", "~> 0.4.16"

gem 'active_record_shards', git: "git@github.com:freshdesk/active_record_shards", branch: "rails6"
gem "rack-throttle", "~> 0.3.0"
gem "static_model", "~> 1.0.4"

gem 'wkhtmltopdf-binary', git: "https://github.com/freshdesk/wkhtmltopdf_binary_gem", branch: "ruby_2.3"
gem "wicked_pdf", "1.1.0"
gem "pg", "0.21.0"

gem "paperclip", "~> 6.1.0"

gem "aws-sdk-core", "3.121.3"
gem "aws-sdk-s3", "1.57.0"
gem "aws-sdk-sqs", "1.26.0"
gem "aws-sdk-opsworks", "1.24.0", require: false
gem "aws-sdk-cloudwatch", "1.38.0", require: false
gem "aws-sdk-ec2", "1.165.0", require: false
gem "aws-sdk-rds", "1.85.0", require: false
gem "aws-sdk-sns", "1.24.0"
gem "aws-sdk-lambda", "1.42.0", require: false
gem "aws-sdk-codecommit", "1.33.0"
gem "aws-sdk-cloudfront", "1.29.0"
gem "aws-sdk-route53", "1.35.0"


gem "xml-simple", "1.1.4", require: 'xmlsimple'

gem "premailer", "~> 1.8.0"

gem "redis-queue", "0.0.4"

gem "add_pod_support", path: "#{File.expand_path(__FILE__)}/../vendor/gems/add_pod_support-0.0.1"
gem "custom_fields", path: "#{File.expand_path(__FILE__)}/../vendor/gems/custom_fields-0.1"
gem 'formserv-gem', git: 'git@github.com:freshdesk/formserv-gem.git', branch: 'rails6'

gem "rule_engine", git: 'git@github.com:freshdesk/rule_engine.git', tag: 'v0.2.15'
gem "workflow", git: 'git@github.com:freshdesk/workflow.git', tag: 'v0.4.16'
gem "state_machine", git: 'git@github.com:freshdesk/state_machine.git', tag: 'v0.3.0'

#Using the branch here instead of tag because few of the changes are done by Freshdesk is not implemented in platforms.
gem 'freshid', git: 'git@github.com:freshdesk/freshid-ruby-client.git', tag: 'v5.0.0.1'
gem "freshid-sdk", :git => 'git@github.com:freshdesk/platforms-sdk-ruby.git', tag: '1.5.0.3', glob: 'gems/freshid-sdk/freshid-sdk.gemspec'

gem 'approvals_sdk', git: 'git@github.com:pizzainc/fs_approvals_sdk.git', tag: 'v1.3'
gem "jwt", "1.5.4"
gem "json-jwt", "1.13.0", require: false
gem "recaptcha", require: "recaptcha/rails"
gem "marginalia", "1.7.1"

gem 'feature_management', path: "#{File.expand_path(__FILE__)}/../vendor/gems/feature_management"
gem "freshdesk_authority", path: "#{File.expand_path(__FILE__)}/../vendor/gems/freshdesk_authority-0.1"
gem "active_presenter", git: "https://github.com/jorgevaldivia/active_presenter"
gem "acts_as_voteable", path: "#{File.expand_path(__FILE__)}/../vendor/gems/acts_as_voteable"
gem "has_description_body", path: "#{File.expand_path(__FILE__)}/../vendor/gems/has_description_body"
gem "xss", path: "#{File.expand_path(__FILE__)}/../vendor/gems/xss"
gem "features", path: "#{File.expand_path(__FILE__)}/../vendor/gems/zendesk-features-1.0.2"
gem "dev_notification", path: "#{File.expand_path(__FILE__)}/../vendor/gems/dev_notification"
gem "sharding", path: "#{File.expand_path(__FILE__)}/../vendor/gems/sharding"
gem "business_time", path: "#{File.expand_path(__FILE__)}/../vendor/gems/business_time"
gem "ssl_requirement", path: "#{File.expand_path(__FILE__)}/../vendor/gems/ssl_requirement"
gem "helpdesk_attachable", path: "#{File.expand_path(__FILE__)}/../vendor/gems/helpdesk_attachable"
gem "has_flexiblefields", path: "#{File.expand_path(__FILE__)}/../vendor/gems/has_flexiblefields"
gem "liquid", path: "#{File.expand_path(__FILE__)}/../vendor/gems/liquid"
gem "seed-fu", path: "#{File.expand_path(__FILE__)}/../vendor/gems/seed-fu"
gem "highcharts-rails", path: "#{File.expand_path(__FILE__)}/../vendor/gems/highcharts-rails"
gem "will_paginate-liquidized", path: "#{File.expand_path(__FILE__)}/../vendor/gems/will_paginate-liquidized"
gem "will_filter", path: "#{File.expand_path(__FILE__)}/../vendor/gems/will_filter"
gem "rack-openid", path: "#{File.expand_path(__FILE__)}/../vendor/gems/rack-openid"
gem "open_id_authentication", path: "#{File.expand_path(__FILE__)}/../vendor/gems/open_id_authentication"
gem "docusign_rest", path: "#{File.expand_path(__FILE__)}/../vendor/gems/docusign_rest"
gem 'freshcaller', git: 'git@github.com:freshdesk/freshcaller-ruby-sdk.git', tag: '1.3.1'
gem "emailserv_request", :git => "git@github.com:freshdesk/emailserv_request.git", tag: 'v1.3'
# tag will be changed to version after testing. Currently it is added as master
gem "search_client", git: "git@github.com:freshdesk/search_client.git", tag: 'test_02'
gem "erm", git: "git@github.com:freshdesk/flag_mgmt.git", tag: 'v0.0.4'
gem 'money'
gem 'eu_central_bank'
gem "jsonpath", git: 'git@github.com:joshbuddy/jsonpath.git', tag: 'v1.1.5'
gem 'icalendar', '2.4.1'

gem 'rails_cookie_overflow', '1.0.1'

group :development, :test do
  gem 'better_errors', '~> 2.8'
  gem 'binding_of_caller'
  gem 'byebug'
  gem 'pry'
  gem 'brakeman', require: false
  gem 'bullet', '~> 6.1.0'
  gem 'rubocop', '~> 1.23', require: false
  # gem 'factory_bot_rails', '6.1.0'
  gem 'puma'
  gem 'bootsnap', require: false
  # to benchmark active record queries in console
  # Enabled by default, use ExecutionTime.disable! to disbale it.
  # https://github.com/igorkasyanchuk/execution_time
  gem 'execution_time'
end

group :development, :test, :staging do
  gem 'factory_bot_rails', '6.1.0', require: false
  gem 'faker', '~> 1.8.6'
end

group :test do
  #gem 'spring-commands-rspec', '1.0.4'
  gem "rspec", "3.10.0"
  gem 'rails-controller-testing'

  gem 'shoulda-matchers', '~> 5.0'
  gem 'test-prof', '~> 1.3'
  gem 'rubocop-rspec', '~> 2.6', require: false
  gem 'rubocop-rails', '~> 2.12', require: false
  gem 'rubocop-performance', '~> 1.12.0', require: false
  gem "rspec-rails", "5.1.1"
  gem 'rspec-collection_matchers', '1.0.0'
  gem "rr", "~> 1.1.0"
  gem 'simplecov', '~> 0.21.2'
  gem 'simplecov-csv', '~> 0.1.3'
  gem 'simplecov-json', '~> 0.2.3'
  gem 'simplecov-rcov', '~> 0.2.3'
  gem 'simplecov-html', '~> 0.12.3'
  gem "fuubar"
  gem "json-compare", "0.1.8"
  gem "rspec_junit_formatter" # Used by API
  gem "rubocop-checkstyle_formatter" # Used by API
  gem 'json_expressions' # Used by API
  gem "timecop" # Used by API
  gem "json-schema" # Used by AuditLog
  gem 'webmock', '3.5.1' # used to mock http requests
  # gem 'codecov', '0.1.14', :require => false # TODO: Enable after Continuous Deployment, with latest stable version
  gem 'grpc_mock', '0.4.6'
  gem 'rspec-sidekiq'
  gem 'karafka-testing', '2.2.0'

  # Commenting deprecation toolkit which is not needed now
  # gem 'deprecation_toolkit', '~>1.5.1'
  # Commenting deprecation toolkit which is not needed now
end

gem "ejs", "1.1.1"

# SASS and Compass gems
gem "sass-rails", "5.0.8"
gem "compass-rails", "~> 4.0.0"

gem "sprockets", "3.7.2"

gem "compass-blueprint", "1.0.0"

gem "uglifier", "3.2.0"
gem "asset_sync", "2.14.1"
gem "fog-aws", "3.3.0"

# Portal grid system is done using susy grids
gem "susy", "2.1.3"

# To optimize sprite generation
gem "chunky_png", "1.3.6" # locking this because of breaking API in 1.3.7
gem "oily_png", "1.1.1"

# Building custom font icons inside the application
gem "fontcustom", git: "git@github.com:psyipm/fontcustom.git", branch: "upgrade-dependencies-for-rails-6-1"

gem "handlebars_assets", "0.23.9"

# Marketplace
gem 'nokogiri', '1.13.9'
gem 'axlsx', require: false
gem 'activerecord-import', '1.0.7'
gem 'freshquery', git: "git@github.com:freshdesk/search-fql-sdk-ruby.git", tag: 'v0.4.4'

#barby gem for BARcode generation
gem 'barby', '0.6.5'
#rqrcode gem and its dependency gems for QR Code generation
gem 'rqrcode', '1.2.0'
gem 'rqrcode_core', '0.2.0'

# Shrine and its dependency Gems
gem 'shrine', '2.12', require: false
gem 'uppy-s3_multipart', '0.1.0', require: false

#Ember Rails
gem "ember-cli-rails", "0.10.0"
gem 'pagy', '1.2.1', require: false

#heap Analytics
gem 'heap', '~> 1.0'

#Fluffy
gem "fluffy", git: 'git@github.com:freshdesk/api-gateway.git', tag: 'v1.2.0', glob: 'clients/fluffy_ruby/src/fluffy.gemspec'

#Semian
gem 'semian', require: %w(semian semian/mysql2), git: "git@github.com:freshdesk/semian.git", branch: "fs_master", group: [:development, :production, :staging]

# Prometheus
gem 'prometheus_exporter', git: 'git@github.com:freshdesk/prometheus_exporter.git', tag: 'v1.1.14', require: false

# to convert empty string to NULL for string attributes to avoid mixup of NULL and empty string data in DB
gem "nilify_blanks", '~> 1.3'

gem 'telephone_number'

#on-call
gem 'oncall', git: 'git@github.com:freshdesk/itom_oncall.git', tag: 'v1.0.9', glob: 'clients/oncall/oncall.gemspec'

#Tracing
group :production, :staging, :test, :development do
  gem 'opentelemetry-common', git:'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-semantic_conventions', git:'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-instrumentation-base', git:'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'

  gem 'opentelemetry-api', git:'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-sdk', git:'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-exporter-otlp', git:'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-instrumentation-rails', git:'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-instrumentation-action_pack', git:'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-instrumentation-rack', git:'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-instrumentation-mysql2', git:'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-instrumentation-dalli', git:'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-instrumentation-redis', git:'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-instrumentation-ethon', git:'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-instrumentation-net_http', git:'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-instrumentation-sidekiq', git:'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-instrumentation-meta_errors', git: 'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-instrumentation-faraday', git: 'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-instrumentation-active_support', git: 'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-instrumentation-action_view', git: 'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'opentelemetry-instrumentation-shoryuken', git: 'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
  gem 'sherlock-agent', git:'git@github.com:freshdesk/opentelemetry-ruby.git', branch: 'v1.0.2', glob: '/**/*.gemspec'
end

path 'components' do
  gem 'solution'
  gem 'pom'
  gem 'ams'
  gem 'dashboard'
  gem 'problem'
  gem 'change'
  gem 'release'
  gem 'itil'
  gem 'asset'
  gem 'contract'
  gem 'software'
  gem 'cmdb'
  gem 'workload'
  gem 'ticket'
  gem 'billing'
  gem 'ocs'
  gem 'service_catalog'
  gem 'communication'
  gem 'status_page'
  gem 'offboarding'
  gem 'task'
  gem 'workato'
  gem 'document_generator'
  gem 'instance_management'
  gem 'sla'
  gem 'onboarding'
  gem 'workflow_service'
  gem 'devops_platform'
  gem 'support'
  gem 'service_bot'
  gem 'csat'
end
# custom_engines ends here

# inline svg helper
gem 'inline_svg', '1.7.2'

gem 'slack_block_kit_builder', git: 'git@github.com:freshdesk/slack_block_kit_builder.git', tag: 'v1.1.0'

gem 'cloud_wrapper', git:'git@github.com:pizzainc/cloud_wrapper.git', tag: '2.0.2'

gem 'infra_alert_processor', git:'git@github.com:freshdesk/infra_alert_processor.git', tag: '1.0.3'

gem 'redcarpet', tag: '3.6', require: false
