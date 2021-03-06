# DC-Area Ruby Shell Server Cheftime Funtimes!

Followed [This chef-solo doc][1] to get the basics in place.

## Getting an account

1. Fork this repo
1. Add a databag for yourself to `data_bags/users/(you).json`
1. Add your user to the list of users in `nodes/ruby.loki.ws.json`
1. Commit your change, send a PR against this main repo
1. Hope!
1. If Josh accepts your PR, you'll be able to log in: `ssh (you)@ruby.loki.ws`
1. When you're in, you can run `tmux` to launch a session, then from
   in there you can run `irssi`.
    1. Documentation on using these commands is on the internet somewhere...

## Using tmux and irssi

These are with the default configs

1. ssh into the server: `ssh (you)@ruby.loki.ws`
1. start tmux: `tmux`
1. start irssi: `irssi`
1. connect to freenode: `/server irc.freenode.net`
1. set your nick: `/nick (you)`
1. join #arlingtonruby: `/join #arlingtonruby`
1. Say hi!: `hi!`

## Leaving and coming back

1. detatch your tmux session: `ctrl-b, d`
1. reattach your existing session: `tmux attach`

[1]: http://leopard.in.ua/2013/01/04/chef-solo-getting-started-part-1/
