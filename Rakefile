require 'rubygems'
require 'rake'

namespace :install do

  desc "install custom themes and bundle tweaks for e-text editor"
  task :e do
    abort 'This is for Windows, yo!' unless RUBY_PLATFORM.downcase.include?('mswin')
    
    appdata = ENV['APPDATA']
    FileUtils.cp_r '.e/.', File.join(File.expand_path(appdata), 'e')
  end
end
