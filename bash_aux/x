#!/bin/sh

echo "start debugging.."
p=$1

M=`ps uax | grep $p | awk 'NR==1{print $2}'` 
echo "target PID is :  $M"
echo "[*]Attaching now..."

gdb attach $M
