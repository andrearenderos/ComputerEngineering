# ComputerEngineering
Carnegie Mellon 



Sed - Function is the answer in text/ how to delete lines, find/replace with famcy pattern matching. 
> sed -option 'instructions' filename

using awk command

Print one file: 
awk '{i=0; while(i<=NF) { print i ":"$i; i++;}}' employees.txt

Combining patterns 
awk '$3 > 10 && $4 < 20 {print $1, $2}' employees.txt


Create an awk script 
awk '{action}'

awk '{print "How to use the awk command"}'
