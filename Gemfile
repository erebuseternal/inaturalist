# frozen_string_literal: true

source "https://rubygems.org"

ruby "~> 2.6.0"

gem "rails", "6.1.4"

gem "actionpack-action_caching"
gem "actionpack-page_caching"
gem "activerecord-postgis-adapter" #, ">= 5", "< 6"
gem "activerecord-session_store"
gem "acts-as-taggable-on"
gem "acts_as_votable"
gem "ancestry"
gem "angular-rails-templates"
gem "aws-sdk-cloudfront"
gem "aws-sdk-s3"
gem "aws-sdk-waf"
gem "biodiversity"
gem "capistrano"
gem "capistrano-passenger"
gem "capistrano-rails"
gem "capistrano-rvm"
gem "chroma"
gem "chronic"
gem "cocoon" # JY: Added to support nested attributes for assessment_sections on assessments
gem "coffee-rails"
gem "dalli"
gem "dbf" # Needed for georuby shapefile support
gem "delayed_job"
gem "delayed_job_active_record"
gem "devise"
gem "devise-encryptable"
gem "devise-i18n"
gem "devise_suspendable"
gem "diffy"
gem "dm_preferences", git: "https://github.com/nickcoyne/preferences.git"
gem "doorkeeper"
gem "dynamic_form"
gem "elasticsearch"
gem "elasticsearch-api"
gem "elasticsearch-model"
gem "elasticsearch-rails"
gem "exifr", require: ["exifr", "exifr/jpeg", "exifr/tiff"]
gem "exiftool_vendored" # Vendored version includes exiftool and exiftool gem
gem "fastimage"
gem "flickraw-cached"
gem "friendly_id"
gem "gdata", git: "https://github.com/pleary/gdata.git"
gem "georuby"
gem "haml"
gem "htmlentities"
gem "i18n-inflector-rails"
gem "i18n-js", git: "https://github.com/fnando/i18n-js.git"
gem "icalendar", require: ["icalendar", "icalendar/tzinfo"]
gem "irwi", git: "https://github.com/Programatica/irwi.git"
gem "json"
gem "koala"
gem "nokogiri"
gem "non-stupid-digest-assets"
gem "objectify-xml", git: "https://github.com/inaturalist/objectify_xml.git"
gem "omniauth"
gem "omniauth-apple"
gem "omniauth-facebook"
gem "omniauth-flickr", git: "https://github.com/IDolgirev/omniauth-flickr.git",
ref: "bcd202b0825659cbd984e611f6151f67c4aae591"
gem "omniauth-google-oauth2"
gem "omniauth-oauth2"
gem "omniauth-openid", git: "https://github.com/inaturalist/omniauth-openid"
gem "omniauth-orcid"
gem "omniauth-rails_csrf_protection"
gem "omniauth-soundcloud", git: "https://github.com/ratafire/omniauth-soundcloud.git"
gem "omniauth-twitter"
gem "optimist"
gem "paperclip"
gem "parallel"
gem "patron"
gem "pg"
gem "rack-cors"
gem "rack-mobile-detect"
gem "rack-tracker"
gem "rails-controller-testing"
gem "rails-html-sanitizer"
gem "rails-i18n"
gem "rails-observers"
gem "rakismet"
gem "rdoc", "< 6.4.0"
gem "redcarpet"
gem "rest-client", require: "rest_client"
gem "rgeo"
gem "rgeo-geojson"
gem "rgeo-proj4", "~> 2.0.1"
gem "rgeo-shapefile"
gem "riparian", git: "https://github.com/inaturalist/riparian.git", ref: "rails6"
gem "rubyzip", "~> 2.3.0"
gem "sass-rails"
gem "savon" # allow to consume soap services with WSDL
gem "soundcloud"
gem "sprockets"
gem "terrapin"
gem "uglifier"
gem "utf8-cleaner"
gem "watu_table_builder", require: "table_builder"
gem "whenever", require: false
gem "will_paginate"
gem "xmp", git: "https://github.com/inaturalist/xmp.git"
gem "ya2yaml"
gem "yajl-ruby", require: "yajl"
gem "yui-compressor"

group :production do
  gem "newrelic_rpm"
end

group :test, :development, :prod_dev do
  gem "database_cleaner"

  # this fork fixes the `warning: constant ::Fixnum is deprecated` warnings
  # See https://github.com/notahat/machinist/pull/133
  gem "machinist", git: "https://github.com/narze/machinist", ref: "eaf5a447ff0d59a1fb2c49b91c6e1b2d95d8e4ee"

  gem "better_errors"
  gem "binding_of_caller"
  gem "byebug"
  gem "capybara"
  gem "lefthook", require: false
  gem "puma"
  gem "rubocop-rails", require: false
  gem "rubocop-rspec", require: false
  gem "thin"
end

group :test do
  gem "factory_bot_rails", require: false
  gem "faker"
  gem "rspec"
  gem "rspec-html-matchers"
  gem "rspec-rails"
  gem "shoulda-matchers"
  gem "simplecov", require: false
  gem "webmock"
end
