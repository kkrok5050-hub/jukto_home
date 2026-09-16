source "https://rubygems.org"

# GitHub Pages와 완전히 동일한 환경(지원 플러그인 버전 포함)으로 로컬 빌드/미리보기
gem "github-pages", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
  gem "jekyll-feed"
end

# Windows/JRuby 환경 관련 필수 젬 (없어도 GitHub Pages 배포엔 영향 없음)
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
