# Kali Linux Foundation Building Skills

# Problem 1 - Create secret.txt. Set permissions so only YOU can read it (no write, no execute) [Permission Lockdown]
Step by Step Problem Solving -
1. touch [filename] - Creates a new empty file
2. chmod 400 [filename] - "chmod" command is for changing security permissions and "400" is a specific code that only owners can read it, no one else

# Problem 2 - Create permanent alias in .zshrc: 'update' runs sudo apt update && upgrade [The Fast Lane]
Step by Step Problem Solving - 
1. nano ~/.zshrc - "nano" is a text editor command for the computer system terminal.
2. alias update='sudo apt update && sudo apt upgrade -y'
3. source ~/.zshrc - "source" is a command for refresh/reload
   
