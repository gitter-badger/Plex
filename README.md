## Plex [![Build Status](https://travis-ci.org/isainode/Plex.svg?branch=master)](https://travis-ci.org/isainode/Plex)

[![Join the chat at https://gitter.im/isainode/Plex](https://badges.gitter.im/isainode/Plex.svg)](https://gitter.im/isainode/Plex?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Plex is a set of services for IRC networks designed for large IRC networks 
with high scalability requirements.  It is relatively mature software, with 
some code and design derived from another package called Shrike, and is a fork 
of a dying services package named Atheme.

Plex's behavior is tunable using modules and a highly detailed 
configuration file. Almost all behavior can be changed at deployment time just 
by editing the configuration.

If you are running this code from Git, you should read `GIT-Access` for 
instructions on how to fully check out the Plex tree, as it is spread 
across a few repositories.

## Building

Whatever you do, make sure you do *not* install Plex into the same location 
as the source. Plex will default to installing in `$HOME/Plex`, so make 
sure you plan accordingly for this.

    $ git submodule update --init
    $ ./configure
    $ make
    $ make install

If you're still lost, read [INSTALL](INSTALL) or [GIT-Access](GIT-Access) for 
hints.

## Contact Us

__Be sure to read [the FAQ](doc/FAQ.md) as well.__

 * [GitHub: isainode/Plex](https://github.com/Plex/Plex)
 * [IRC: irc.isainode.net, #Plex](ircs://irc.isainode.net:6697/Plex) ([webchat](https://kiwiirc.com/client/irc.isainode.net:+6697/Plex))
