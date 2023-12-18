#!/bin/bash
echo "enter user name"
read -s  username  
echo "user name enter is:$username"
echo "enter password"
read -s password
echo "password enter is:$password"

num1=$2
num2=$3
sum=$((num1+num2))
echo "sum is:$sum"
