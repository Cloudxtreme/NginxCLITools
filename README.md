NginxCLITools
=============

A bunch of CLI-Tools to control nginx

Installation
============

1. Find out whats your nginx-path
2. Edit scripts to fit your path
3. Copy all the scripts to /usr/bin: `sudo cp nginx-* /usr/bin/`

Tools
=====

## nginx-enable
`nginx-enable <sitename>`  
enable site `<sitename>`

## nginx-disable
`nginx-disable <sitename>`  
disable site `<sitename>`

## nginx-reload
reload nginx config

## nginx-list-available
list available sites

## nginx-list-enabled
list enabled sites
