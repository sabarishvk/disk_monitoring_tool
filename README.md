# disk_monitoring_tool

A disk monitoring tool that can monitor disk usage and also report on faulty disk. 

## Installation
- Make sure 'smartmontools' is installed for checking disk health. <br />
	For Debian / Ubuntu systems: Run these commands <br />
	apt-get install smartmontools <br />

	For Red Hat based systems like CentOS or Fedora: Run these commands <br />
	yum install smartmontools <br />

- Make sure sendmail is installed and configured for sending out notiication mails 

	For Debian / Ubuntu systems: Run these commands <br />
	apt-get install mutt <br />
	apt-get install swaks <br />
	apt-get install mailx <br />
	apt-get install sharutils <br />
        
	For Red Hat based systems like CentOS or Fedora: Run these commands <br />
	yum install mutt <br />
	yum install swaks <br />
	yum install mailx <br />
	yum install sharutils <br />

## Usage

Usage: ./check_disk -w -c -ne -i <br />
Example : ./check_disk -w 80% -c 90% -ne xyz@abs.com -i 5
