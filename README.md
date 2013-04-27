knife-ssh
=========

Chef knife ssh cli improvements

Subject to big changes soon.

## Install

Save ssh.rb into your .chef/plugins/knife

## Configure

In your .chef/knife.rb, add:

    # Colors you want to use for different hosts
    knife[:colors] = [:black, :red, :green, :yellow, :blue, :magenta, :cyan, :white]
    
    # Display the content in color as well
    knife[:color_content] = true

## Dependency

Paint

    gem install paint