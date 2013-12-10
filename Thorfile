# encoding: utf-8

require 'bundler'
require 'thor'

class Templeton < Thor

  desc "setup", "Install templeton dependancies on your system"
  def setup
    %w{ yo bower grunt generator-angular }.each do |pkg|
      `npm install -g #{pkg}`
    end
  end

end
