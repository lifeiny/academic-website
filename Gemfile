source "https://rubygems.org"

# 固定 Ruby 版本，Vercel 会据此安装
ruby "3.2.2"

# 固定 Jekyll 到 4.3.3（或以上小版本），避免 logger 在 Ruby 3.3 的兼容性坑
gem "jekyll", "~> 4.3.3"

# 主题（保持你现有的）
gem "minima", "~> 2.5"

# Jekyll 常用依赖（本地与云端都稳）
gem "webrick"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
