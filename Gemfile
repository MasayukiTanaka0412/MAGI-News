source "https://rubygems.org"

gem "jekyll", "~> 4.3"
gem "minima", "~> 2.5"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag", "~> 2.8"
end

# Windows および JRuby では tzinfo-data が必要
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows でディレクトリ監視のパフォーマンス向上
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# JRuby で http_parser.rb のロック
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]