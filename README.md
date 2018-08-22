# nmap-html

## Prerequisites

### Linux 

* `xdg-open`
    - On Debian/Ubuntu: `apt-get install xdg-utils`
    - On Fedora `dnf install xdg-utils`

### Mac
* It works! :smile: 

## Usage
```
$ ./nmap-html {target specification} [output file name]

TARGET SPECIFICATION:
    Can pass hostnames, IP addresses, networks, etc.
OUTPUT (optional):
    Filename to the xml and html file generated. Default is 'report'.
```