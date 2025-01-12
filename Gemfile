source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem "jekyll", "~> 4.3.0"
gem "webrick", "~> 1.8.1"
gem "nokogiri", "~> 1.18.1"

# Use a specific version of ffi that works with Ruby 3.0
gem "ffi", "~> 1.15.5"

group :jekyll_plugins do
  gem "jekyll-last-modified-at", git: "https://github.com/maximevaillancourt/jekyll-last-modified-at", branch: "add-support-for-files-in-git-submodules"
end
