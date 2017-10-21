source "https://rubygems.org"
ruby File.read(File.expand_path("../.ruby-version", __FILE__)).chomp

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "rake"
gem "ruboty-cron"
gem "ruboty-echo"
gem "ruboty-redis"
gem "ruboty-slack"
gem "ruboty-ruby", ">= 0.0.2"
gem "ruboty-call", github: "a2ikm/ruboty-call", branch: "record_option"
gem "ruboty-contacts", github: "a2ikm/ruboty-contacts"
