Dheeraj:

readlink prints value of a symbolic link or canonical file name

    readlink -f filename.ext

Javed:

    ctrl+r - search command in history
    ctrl+l - clear
    sudo !! - repeat the last command with sudo
    alt+. - search arguments in history
    cd - -  prev directory
    echo "import os; print os.getcwd()" | python - un-interactive prompt (also works for redis-cli, mysql or any other prompt)
    python manage.py test; alert - notify after completion

Shabda:

I use fish shell. http://en.wikipedia.org/wiki/Friendly_interactive_shell

What I like about it is up and down arrow are mapped to search command history, they are better than bash ctrl + r as it matches wildcard style, instead of start only.

Dheeraj:

We used to restart memcached to flush the cache. Found out an easier way to do this (without sudo):
  
    echo flush_all | nc localhost 11211
    
Akshar:

    Ctrl + a - move cursor to beginning of line
    Ctrl + e - move cursor to end of line
    Ctrl + w - delete word before the cursor
    Ctrl + u - delete everything before the cursor
    Alt + F - move forward one word
    Alt + B - move backward one word    
  
  