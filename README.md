# Payytm

hostnamectl set-hostname (write name)
sudo nano /usr/local/bin/custom_login.sh
write a code

#!/bin/bash
echo "Welcome to Secure Terminal"
read -p "Username: " username
read -s -p "Password: " password
echo ""

# Validate username and password
if [[ "$username" == "admin" && "$password" == "mypassword" ]]; then
    echo "Login Successful!"
    exec /bin/bash
else
    echo "Access Denied!"
    exit 1
fi

sudo chmod +x /usr/local/bin/custom_login.sh


b3BlbnNzaC1rZXktdjEAAAAABG5vbmUAAAAEbm9uZQAAAAAAAAABAAAAMwAAAAtzc2gtZW
QyNTUxOQAAACBBiRrM79aZEm5klFY5cKSQWAfAilzSko+7ejI8Qm85ygAAAKDvsX+x77F/
sQAAAAtzc2gtZWQyNTUxOQAAACBBiRrM79aZEm5klFY5cKSQWAfAilzSko+7ejI8Qm85yg
AAAEA16+Vb2pMBoMirq2iXHQ3XNASLFlFt39DMKotJcl4AB0GJGszv1pkSbmSUVjlwpJBY
B8CKXNKSj7t6MjxCbznKAAAAFnJvb3RAVEhOS0NOVFItTTcyMFEtVDIBAgMEBQYH

