begin
  require 'config/requirements'
  require 'config/hoe' # setup Hoe + all gem configuration
end

$:.unshift("#{File.dirname(__FILE__)}/lib")
Dir['tasks/**/*.rake'].each { |rake| load rake }