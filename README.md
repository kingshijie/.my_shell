My Mac Scripts
==============

This project has some useful scripts I am recently using, includes useful alias, some shells.

To use it, download the project, 
$ mv /directory/to/unziped/project ~/.my_shell

If you are using clean system (without .profile)
$ ln -s ~/.my_shell/.profile ~/.profile
$ source ~/.profile

But if you already have ~/.profile, add one line at the end of your ~/.profile
  source ~/.my_shell/.profile

That's it.
