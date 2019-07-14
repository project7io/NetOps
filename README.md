#### Bash Commands ####
[Bash command for IP Addresses](#IP-addresses "Bash commands for IP addresses")

Link to a Linux script to update https://github.com/project7io/scripts/blob/master/update.sh 




### IP Addresses ###
#### Get internal IP Parrot OS and push to text file. ####
ip a | grep 'e g' | cut -d ' ' -f 6 > internal_ip.txt 

#### Get internal IP Raspbian OS and push to text file. ####
w | grep 'pts' | cut -d ' ' -f 12 >> internal_ip.txt 
