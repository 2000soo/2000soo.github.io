# frozen_string_literal: true

source "https://rubygems.org"

# 기본 Jekyll 의존성 추가
gem "jekyll", "~> 4.3.4"
gem "jekyll-seo-tag"
gem "jekyll-feed"
gem "jekyll-sitemap"
gem "jekyll-paginate"
gem "jekyll-archives"
gem "jekyll-theme-chirpy"

gem "html-proofer", "~> 5.0", group: :test

# Windows 플랫폼에 필요한 추가 설정
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
