# Hacking Jenkins using Shodan API

## Requirements:
1. PHP
2. Shodan API
3. PHP Curl

## Jenkins hacking automation using shodan API

I have created 2 scripts for hacking jenkins in much easier way.

1st script is to get the list of jenkins servers from shodan and then check for vulnerable jenkins servers and find, on which user jenkins is running on. If it is root Cool , it's your day then! 30-40% jenkins servers run on roots, based on my analysis.

2nd script will give you a shell like environment, so you don't need write exploits for jenkins each time you want to execute a shell command.

## Screenshots

### Script 1

![Script 1](https://image.prntscr.com/image/pa_Z62uWQh_5W-k5BV0enQ.png)

### Script 2

![Script 2](https://image.prntscr.com/image/x7FnAGuGQfSSy7Kgp87W1g.png)

### Files:

Script1 : https://github.com/joesmithjaffa/jenkins...shodan.php

Script2 : https://github.com/joesmithjaffa/jenkins...ns-cli.php

Using these scripts, you can hack 1000s of jenkins servers without even need to write any exploits.
