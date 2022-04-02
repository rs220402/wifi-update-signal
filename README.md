# wifi-update-signal
when the IP address of the device changes, it should send a message with the new address with the messenger signal
## background
I operate a raspberry pi zero in a guest wifi. IP address is assigned by DHCP, DNS is not available. Guests can contact each other by IP address. 

In order to reach the servers on the raspberry by IP address, I want it to send a message to the messenger Signal, whenever its address changes. 

I have chosen Signal for two reasons: 
1. It supports group chats. That way, I can add my teammates to a group chat and they will receive the address updates, too
2. there is already a python implementation for signal-cli available
3. 
