## How to Create Linux User With Non Interactive Shell
- First check if user exists on the server  by below command `sudo id USERNAME`
- If user is not found the then create a user with non-interactive shell by this command `sudo adduser USERNAME -s /sbin/nologin`
- Validate user is created successfully. `sudo id USERNAME`   `sudo  cat /etc/password | grep USERNAME`