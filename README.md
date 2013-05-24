# Jenkins pyenv plugin

 pyenv build wrapper for Jenkins

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Building the plugin from source

Follow these steps if you are interested in hacking on the plugin.

Find a version of JRuby to install via `pyenv-install -l`

Install JRuby

    pyenv install jruby-1.6.7
    pyenv local jruby-1.6.7

Install the jpi gem

    gem install jpi
    pyenv rehash

Build the plugin

    jpi build
    

Look at [Getting Started with Ruby Plugins](https://github.com/jenkinsci/jenkins.rb/wiki/Getting-Started-With-Ruby-Plugins) to get up to speed on things.
