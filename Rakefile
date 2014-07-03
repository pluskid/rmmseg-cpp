# -*- Ruby -*-
require 'rake/extensiontask'
load 'tasks/setup.rb'
Rake::ExtensionTask.new('rmmseg')
ensure_in_path 'lib'
require 'rmmseg'

task :default => 'spec:run'

PROJ.name = 'rmmseg-cpp'
PROJ.version = '10.2.9.2'
PROJ.authors = 'pluskid,seoaqua'
PROJ.email = 'pluskid@gmail.com,seoaqua@qq.com'
PROJ.url = 'https://github.com/seoaqua/rmmseg-cpp'
PROJ.rubyforge.name = 'rmmseg-cpp'

PROJ.spec.opts << '--color'

# EOF
