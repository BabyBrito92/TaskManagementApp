source "https://rubygems.org"

# Rails framework - the core of the app.
gem "rails", "~> 8.0.0"

# Handles CSS/JS assets. Simplifies things.
gem "propshaft"

# PostgreSQL adapter - connects Rails to my Postgres database.
gem "pg", "~> 1.1"

# Puma server - runs the app. It’s fast and production-ready.
gem "puma", ">= 5.0"

# importmap for JavaScript without Webpack.
gem "importmap-rails"

# turbo-rails for Hotwire. Makes the app fast and modern without too much JS.
gem "turbo-rails"

# stimulus for Hotwire. Adds small JS components for interactive UI.
gem "stimulus-rails"

# Helps create JSON responses (useful for APIs).
gem "jbuilder"

# bcrypt for hashing passwords (needed for auth, like login/signup).
gem "bcrypt", "~> 3.1.7"

# Loads timezone data on Windows (if I ever run it there).
gem "tzinfo-data", platforms: %i[ windows jruby ]

# Speeds up Rails app startup by caching stuff.
gem "bootsnap", require: false

# Devise - makes handling users (signups, logins, etc.) way easier.
gem "devise"

# Adds JWT support to Devise - this is for API-style token authentication.
gem "devise-jwt"

# dotenv - lets me keep secret keys (like JWT secret) in an environment file.
gem "dotenv-rails"

group :development, :test do
  # Helps me debug errors when things go wrong.
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
end
