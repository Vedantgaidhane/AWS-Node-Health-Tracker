#!/bin/bash

##########################################
#Author      - Vedant
#Date        - 11/02/2024
#Description - Script will output the node health
#Version     - v1
##########################################

set -x

echo "Disk space"
df -h

echo "Memory space"
free

echo "Number of CPU's"
nproc

echo "print ID number"
ps -ef |grep amazon|awk -F" " '{print $2}'
