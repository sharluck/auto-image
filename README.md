
# shinchan: share your os setup with others
# auto-image
you must configure the scripting path in /root/.bashrc to run the script files
must install the shellinabox by updating theyum repo to the "epel-release" then only we will get the shellinabox application 


set up the path in " vim /root/.bashrc " : 
  # .bashrc
  # User specific aliases and functions
  alias rm='rm -i'
  alias cp='cp -i'
  alias mv='mv -i'
  PATH=/root/shinchan/scripting:$PATH
  # Source global definitions   
  if [ -f /etc/bashrc ]; then
        . /etc/bashrc
  fi

  PATH="/root/shinchan/scripting:$PATH"



