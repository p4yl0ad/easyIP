# easyIP
EasyIP is a tool i wrote in bash to easily select an interfaces ip address and append it to your bash prompt in order to make remembering local IP addressess easier in labs.


chmod +x easyIP.sh && bash easyIP.sh

follow the prompts and make sure to open a new terminal once youre done.
To change your ip to another , simply run the script again and select the apropriate interface.


#TODO
add function that uses regex and tail to remove the appended $PS1 EXPORT or utilize the ability of having $PS1 $PS2 etc
