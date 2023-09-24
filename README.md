## Technical team public ssh keys
post your public (not private!) ssh keys here so they can be pulled by ansible for logging into internal systems \
post in format of 'username-a.pub' so ansible can automatically read it using the existing vars \
if you dont have one to hand run the below command, this will generate a 4096 key \
ssh-keygen -t rsa -b 4096 -C username-a \
~/.ssh/id_rsa.pub = public key to be uploaded here \
~/.ssh/id_rsa = private key to be saved somewhere safe - you use the private key in putty to connect to servers with username-a@ipaddress \
within putty look under conections > ssh > auth > private key file for authentication