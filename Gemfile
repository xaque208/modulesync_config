#  Copyright 2016 Vox Pupuli
#
#  Licensed under the Apache License, Version 2.0 (the "License");
#  you may not use this file except in compliance with the License.
#  You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
#  Unless required by applicable law or agreed to in writing, software
#  distributed under the License is distributed on an "AS IS" BASIS,
#  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
#  See the License for the specific language governing permissions and
#  limitations under the License.

source "https://rubygems.org"

group :development do
  gem 'travis'
  gem 'travis-lint'
  gem 'pry'
end

group :release do
  gem 'github_changelog_generator',  :require => false, :git => 'https://github.com/github-changelog-generator/github-changelog-generator'
end

gem 'puppet_forge', '>= 2.2.9'
gem 'modulesync', '>= 1.0.0'
gem "octokit", "~> 4.0"
# vim: syntax=ruby
