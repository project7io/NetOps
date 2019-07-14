### scripts
Linux scripts and notes

Link to a Linux script to update https://github.com/project7io/scripts/blob/master/update.sh 



### Get internal IP Parrot OS
ip a | grep 'e g' | cut -d ' ' -f 6 > internal_ip.txt 


### Get internal IP Raspbian OS
w | grep 'pts' | cut -d ' ' -f 12 >> internal_ip.txt 
