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
