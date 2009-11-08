
begin
  require 'bones'
rescue LoadError
  abort '### please install the "bones" gem ###'
end

task :default => 'test'

Bones {
  name         'turn'
  summary      'Test::Unit Reporter (New) -- new output format for Test::Unit'
  authors      'Tim Pease'
  email        'tim.pease@gmail.com'
  url          'http://gemcutter.org/gems/turn'
  version      '0.6.0'
  ignore_file  '.gitignore'
  rdoc.exclude << '^lib/'

  use_gmail
  enable_sudo

  depend_on 'bones-git', :development => true
}

# EOF
