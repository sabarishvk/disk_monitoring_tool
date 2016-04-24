# disk_monitoring_tool

A disk monitoring tool that can monitor disk usage and also report on any faulty disk

## Installation
- Make sure 'smartmontools' is installed for checking disk health.
apt-get install smartmontools

- Make sure sendmail is installed and configured for sending out notiication mails

	For Debian / Ubuntu systems: Run these commands
	apt-get install mutt
	apt-get install swaks
	apt-get install mailx
	apt-get install sharutils
        
	For Red Hat based systems like CentOS or Fedora: Run these commands
	yum install mutt
	yum install swaks
	yum install mailx
	yum install sharutils

## Usage

Usage: ./check_disk -w -c -ne -i
Example : ./check_disk -w 80% -c 90% -ne xyz@abs.com -i 5
