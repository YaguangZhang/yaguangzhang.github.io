source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

gem "github-pages", group: :jekyll_plugins

# If you want to use Jekyll native, uncomment the line below.
# To upgrade, run `bundle update`.

# gem "jekyll"

# Modified on 20250324 by Yaguang:
# ------
gem "eventmachine", platforms: [:ruby]
require 'em/pure_ruby' if not defined?(EventMachine)

# Windows-specific gems
gem "wdm" if Gem.win_platform?
# gem "tzinfo-data" #, platforms: [:mingw, :mswin, :x64_mingw] if Gem.win_platform?
gem "tzinfo-data" if Gem.win_platform?

# ------

# Added on 20211201 by Yaguang:
gem "webrick"

# If you have any plugins, put them here!
group :jekyll_plugins do
  # gem "jekyll-archives"
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "hawkins"
  gem "activesupport", ">= 4.1.11"
end