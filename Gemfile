source "https://rubygems.org"

# 使用 GitHub Pages 来提供所有必要的 gem
gem "github-pages", group: :jekyll_plugins

# 插件
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows-specific gems (如果你在 Windows 上开发)
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance boosters for Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# JRuby-specific gems (如果你在 JRuby 上开发)
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
