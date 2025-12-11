
#### 1. Install OpenFortiVPN

Open your terminal and run:

```bash
sudo pacman -S openfortivpn
```

#### 2. Connect to the Network

Connect to the IIT Kanpur using below command.
Bash

```bash
sudo openfortivpn gateway.iitk.ac.in:443 -u YOUR_USERNAME
```

**Notes on Passwords:**

1. First, it asks for your **Laptop (Sudo) password** to run the VPN software.
2. Next, it asks for your **IITK CC password** (the one used for webmail/helloIITK).

#### 3. Disconnect
To stop the VPN, go to the terminal window where it is running and press:
**Ctrl + C**

*Note: This cleanly closes the tunnel and restores your normal internet connection.*
