#!/usr/bin/ruby -wKU

task :default => :run

task :run, [:name] do |t,args|
  ruby '-Ilib', 'lib/hello.rb', args[:name]
end
