# disk_monitoring_tool

A disk monitoring tool that can monitor disk usage and also report on any faulty disk

## Installation

Download the github code and run the check_disk code.
Make sure 'sendmail' and 'smarttools' are installed. 

## Usage

Usage: ./check_disk -w -c -ne -i
Example : ./check_disk -w 80% -c 90% -ne xyz@abs.com -i 5
