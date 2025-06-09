---
layout: page
title: Resetting your staging server credentials
---

## Resetting your staging server credentials
Once provided with your login credentials to the MDPN staging server, you will need to change your password.  Using a terminal/shell program (Command Prompt in Windows, Terminal in Mac, Shell in Linux), you will need to SSH into the server using the credentials provided:
1. **ssh USERNAME@staging.mipres.org**
![mdpn-ssh-1](../images/mdpn-ssh-1.png)

2. You may then see a prompt beginning with the following: *The authenticity of host 'staging.mipres.org (67.227.240.205)' can't be established.*
![mdpn-ssh-2](../images/mdpn-ssh-2.png)

3. Type **yes** and hit Enter.
![mdpn-ssh-3](../images/mdpn-ssh-3.png)

4. Type the password provided.
![mdpn-ssh-4](../images/mdpn-ssh-4.png)

The system should then walk you through changing your password.  Once that is done, you can use your new password to deposit your content via the DART application.