# frozen_string_literal: true

source "https://rubygems.org"

ruby RUBY_VERSION

gem "decidim", "0.29.1"
# gem "decidim-conferences", "0.29.1"
# gem "decidim-design", "0.29.1"
# gem "decidim-initiatives", "0.29.1"
# gem "decidim-templates", "0.29.1"

gem "bootsnap", "~> 1.3"

gem "puma", ">= 6.3.1"

gem "wicked_pdf", "~> 2.1"

gem "truncate_html"


gem "decidim-iframe", git: "https://github.com/Road-STEAMer/decidim-module-iframe.git"

gem "decidim-whiteboard", git: "https://github.com/Road-STEAMer/decidim-module-whiteboard.git"

gem "decidim-idra", git: "https://github.com/Road-STEAMer/decidim-module-idra.git" 

gem "decidim-access_requests", git: "https://github.com/Road-STEAMer/decidim-module-access_requests.git", branch: "v0.29.1"

#gem "decidim-decidim_awesome"

group :development, :test do
  gem "byebug", "~> 11.0", platform: :mri

  gem "brakeman", "~> 6.1"
  gem "decidim-dev", "0.29.1"
  gem "net-imap", "~> 0.2.3"
  gem "net-pop", "~> 0.1.1"
  gem "net-smtp", "~> 0.3.1"
end

group :development do
  gem "letter_opener_web", "~> 2.0"
  gem "listen", "~> 3.1"
  gem "web-console", "~> 4.2"
end

group :production do
end
