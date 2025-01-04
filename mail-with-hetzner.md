Follow this guide: https://www.youtube.com/watch?v=mmnnV-hARj4

Make sure to set the A-record for the subdomain to the server ip address

sudo apt-get update
sudo apt install mailutils

sudo nano /etc/postfix/main.cf
(make sure myhostname and mydestination are correct)

sudo systemctl restart postfix

