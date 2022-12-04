#!/bin/bash
for url in $(cat sub-domains.txt);
do host $url.$1 |grep “has address”
done
