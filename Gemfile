source "https://rubygems.org"

# 不要固定 ruby 版本，交给 Vercel 使用它的 3.3
gem "jekyll", "~> 4.3.3"
gem "minima", "~> 2.5"

gem "webrick"
gem "logger", "~> 1.5"   # 关键：在 Ruby 3.3 上避免 Jekyll/Logger 报错

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
