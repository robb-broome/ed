# -*- encoding: utf-8 -*-
$:.push File.expand_path("../lib", __FILE__)
require "ed/version"

Gem::Specification.new do |s|
  s.name        = "ed"
  s.version     = Ed::VERSION
  s.authors     = ["Robb Broome"]
  s.email       = ["robb@teamvoice.com"]
  s.homepage    = ""
  s.summary     = %q{Effective dated database records}
  s.description = %q{add preserves_history_for [:array, :of, :attribute, :names] and ed will prevent history from changing}

  s.rubyforge_project = "ed"

  s.files         = `git ls-files`.split("\n")
  s.test_files    = `git ls-files -- {test,spec,features}/*`.split("\n")
  s.executables   = `git ls-files -- bin/*`.split("\n").map{ |f| File.basename(f) }
  s.require_paths = ["lib"]
end
