Port 25 must be accessible, new accounts may be blocked. The support can give you access.

Make sure to set the A-record for the subdomain to the server ip address

sudo apt-get update
sudo apt install mailutils

sudo nano /etc/postfix/main.cf
(make sure myhostname and mydestination are correct)

sudo systemctl restart postfix


Test:
echo "This is the body" | mail -s "This is the subject" -a "FROM:info@yourdomain.com" info@youremail.com
