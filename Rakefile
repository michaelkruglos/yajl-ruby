# encoding: UTF-8
begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "yajl-ruby"
    gem.summary = "Ruby C bindings to the excellent Yajl JSON stream-based parser library."
    gem.email = "seniorlopez@gmail.com"
    gem.homepage = "http://github.com/brianmario/yajl-ruby"
    gem.authors = ["Brian Lopez"]
    gem.require_paths = ["ext", "lib"]
    gem.extra_rdoc_files = `git ls-files *.rdoc`.split("\n")
    gem.files = `git ls-files`.split("\n")
    gem.extensions = ["ext/extconf.rb"]
    gem.files.include %w(lib/jeweler/templates/.document lib/jeweler/templates/.gitignore)
    # gem.rubyforge_project = "yajl-ruby"
  end
rescue LoadError
  puts "Jeweler, or one of its dependencies, is not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"
end