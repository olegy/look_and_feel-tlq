# Look and feel chef recipe

Recipe used for configuring basic look and feel of a fresh Ubuntu
server. In particular:

- Install vim
- Install htop (nicer to look at but more resource intensive alternative
to top)
- Install unzip
- Add an ASCI art banner on login to production environments
- Add `subl` command for editing remote files in Sublime Text
    To make it work:
      - Install the `rsub` package in Sublime Text using the Package Manager
      - add `-R 52698:localhost:52698` to your `ssh` command
