## About [DRAFT] 
 Simple gem management plugin for rubygems

## Usage

## installation
    
    $ git clone git://github.com/gmarik/gem-sync
    $ cd gem-sync/
    $ gem build gem-sync.gemspec
    $ sudo gem install gem-sync-0.0.2.gem

Configure .gems list, gem per line

    $ cat .gems
    rr -v 0.10.9
    gist
          
Now synchronize

    $ sudo gem sync

    Successfully installed rr-0.10.9
    1 gem installed
    Successfully installed gist-1.0.3
    1 gem installed

## References

 *  How to write rubygem plugin: <http://tagaholic.me/2009/04/23/how-to-write-a-rubygem-command-plugin.html>
 *  gem man plugin <http://github.com/defunkt/gem-man>

