# ppa-Testing
Respository to Test DreamVu's Debian Packages. After testing the debian packages are deployed in https://github.com/DreamVu/ppa. 

## To Add the ppa run the command:
  `sudo wget -qO - https://dreamvu.github.io/ppa-Testing/KEY.gpg | sudo apt-key add - && sudo wget -qO /etc/apt/sources.list.d/dreamvu.list   https://dreamvu.github.io/ppa-Testing/dreamvu.list && sudo apt update`
