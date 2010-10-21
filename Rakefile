require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "quilted-harvested"
    gem.version = "0.3.3"
    gem.summary = %Q{A Ruby Wrapper for the Harvest API http://www.getharvest.com/}
    gem.description = %Q{Harvested wraps the Harvest API concisely without the use of Rails dependencies. More information about the Harvest API can be found on their website (http://www.getharvest.com/api). For support hit up the Mailing List (http://groups.google.com/group/harvested)}
    gem.email = "michelle@quilted.coop"
    gem.homepage = "http://github.com/quilted/harvested"
    gem.authors = ["Zach Moazeni, Michelle Moon Lee (updated)"]
    gem.add_development_dependency "rspec", ">= 1.2.9"
    gem.add_development_dependency "cucumber", ">= 0"
    gem.add_development_dependency "ruby-debug", ">= 0"
    gem.add_development_dependency "fakeweb", ">= 0"
    gem.add_dependency "httparty", ">= 0"
    gem.add_dependency "happymapper", ">= 0"
    gem.add_dependency "builder", ">= 0"
  end
  Jeweler::GemcutterTasks.new
rescue LoadError => e
  p e
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end
