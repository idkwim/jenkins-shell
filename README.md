# Hacking Jenkins using Shodan API

## Requirements:
0. Works on any platform
1. PHP
2. Shodan API
3. PHP Curl

## Usage

I have created 2 scripts for hacking jenkins in much easier way.

### Hacking jenkins involves 2 steps:
1. Find the vulnerable jenkin URLs
  a. Execute **shodan.php** to get the list of all URLs and on which user the jenkins is running
2. Executing shell commands without writing your own exploits
  a. Execute **jenkins-cli.php** to run shell commands on the jenkins server

## Screenshots

### Script 1

![Script 1](https://image.prntscr.com/image/pa_Z62uWQh_5W-k5BV0enQ.png)

### Script 2

![Script 2](https://image.prntscr.com/image/x7FnAGuGQfSSy7Kgp87W1g.png)
