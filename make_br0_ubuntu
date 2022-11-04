#Open the Terminal app! 
#Get info about the current connection:
nmcli con show
#Add a new bridge:
nmcli con add type bridge ifname br0
#Create a slave interface:
nmcli con add type bridge-slave ifname enp8s0 master bridge-br0
#Turn on br0:
nmcli con up bridge-br0
#Turn off enp8s0
nmcli con down "Wired connection 1"

