path = "#{File.dirname(__FILE__)}"

require 'yaml'
require path + '/scripts/styletheory.rb'

Vagrant.configure(2) do |config|
    StyleTheory.configure(config, YAML::load(File.read(path + '/styletheory.yaml')))
end
