# Secure your communication online (Chrome, Firefox, etc)
### User TOR, Always

## Setup your system for secure end-to-end communication and browsing
 
1) Download TOR: [Tor Project](https://www.torproject.org/download/) Recommend: Browser Bundle
2) Download ProtonVPN (Swish company) https://protonvpn.com/download
3) Install ProtonVPN (This could require restart of your machine)
4) Install TOR Browser Bundle
5) Start ProtonVPN, Choose Iceland or Finland, if to slow, use The Netherlands

## Get TOR up and running first
1) Start TOR Browser
2) Go to: [Onion address](https://protonmailrmez3lotccipshtkleegetolb73fuirgj7r4o4vfu7ozyd.onion/) [Validate here](https://protonmail.com/tor)<br/
3) Create a Protonmail account (Allows Encrypted Email). https://protonmail.com/ 
You can for example send pictures and videos to news outlets!
You will sometimes need an email account for other services to!

## Create SSH Cryptographic KeyPair
1) Download PuttyGen (for Windows and Mac)
2) Create SSH keypair (4096 BITS)  => PuttyGen example and explained: ![Screenshot](https://i.ibb.co/nfXryBZ/Screenshot-1.png)
3) Send your Public Key using your -ANONYMOUS ACCOUNT- and by using TOR to: [balam.ajaw2020@protonmail.com](balam.ajaw2020@protonmail.com) (yes anonymous account ;)
4) Your public key should looks like this: 
```
ssh-rsa AAAAB3NzaC1yc2EAAAABJQAAAQEApMgkygW00P3k7ztTUAKy1qMHFJBx9GA5P6Luk0Js+RzhdPFNWzJUovYxq6AdV51d95UeywNjC98jL3VKOIN5b6JqCsDJCufpIy1KRx66+FuZyoRovLgxK7iKphqoubPQ2pA61Xq5fFqRd7FJhvEdl9UomZ+K68y6Izbj66hr+8fSOwtHcNcrMalTbDT+8Wop2hTHFDU5CyGEVOSnL4QsurxNZoUhRulbF3aJQyL3GWTYno4hGmNZMr08jVurh6z/05jKh+VAzN5L1gTYH1f+mPTseIMku6RbppeXgzj6N4LOJesXhpzhoMZFIu02SUexEtxt8EMK0iL2VMb7aIMeow== rsa-key-20220227
```
## *** !!! DON NOT SEND YOUR PIVATE KEY!!! *** ##

# This SSH Public Key will provide you Socks5 proxy access through Iceland #

## SSH Keys and Mega (cloud storage). [Screenshots](https://ibb.co/album/n8crnF)

1) Add a password for your SSH key ![Add password](https://i.ibb.co/W56DxJg/Export-Open-SSH-key-add-password.png)
2) Export your OpenSSH private key ![Export OpenSSH key](https://i.ibb.co/zJwMFgN/SSH-private-key.png)
3) Give your filename the identification of 'private' to prevent mistakes. ![Filename](https://i.ibb.co/4Z0p9Vj/Export-Open-SSH-key-save.png)
3b) Export your Putty Private Key ![Export PPK file](https://i.ibb.co/tBGCt5m/Putty-export-key.png)
4) Create account on MEGA: [Mega Storage](https://mega.nz/start)
5) Save your Private Key(s) securely on Mega.

## Setup Chrome to always use TOR as proxy [Chrome setup screenshots](https://ibb.co/album/X7wSGr)

<b>Windows example:</b>

Chrome steps: 
  1) Goto settings ![Step 1](https://i.ibb.co/StTgjmD/Chrome-step-1.png)
  2) Open the advanced section ![Step 2](https://i.ibb.co/gWHKHcd/Chrome-step-2.png)
  3) Goto system ![Step 3](https://i.ibb.co/jZxc9ng/Chrome-step-4.png)
  4) Open your computer proxy settings ![Step 4](https://i.ibb.co/LYs5X30/Chrome-step-5.png)
  5) Add the following details ![Step 4](https://i.ibb.co/M1V38ph/Chrome-step-6.png)
  5) Click on 'SAVE'

Through system steps: 
  1) Search for Proxy, and open Proxy settings ![Step 1](https://i.ibb.co/C6FZymt/Windows-Proxy-settings.png)
  5) Add the following details ![Step 4](https://i.ibb.co/M1V38ph/Chrome-step-6.png)
  5) Click on 'SAVE'

Linux example: will follow

## Setup Mozilla Firefox always using TOR as proxy:
<b>Windows example:</b>

Steps:
  1) Goto settings ![Open settings](https://i.ibb.co/TMwB63b/FF-step-1.png)
  2) Scroll down to the bottom and open 'settings' under 'Network settings' ![Open Network Settings](https://i.ibb.co/PN7yD1V/FF-step-3.png)
  3) Fill in the form EXACTLY as on the the screenshot! ![Fill in proxy settings](https://i.ibb.co/qCbf3hz/FF-step-4.png)
  4) Click on 'OK'
**** REPEAT FOR Chrome Incognito!! ****

Linux example: Will follow

## ************** Always use TOR Browser!!! Unless you can't for some reason!!  *********** ##

# Let's add stealth layer!

### *** Close all application, except Proton VPN. (chrome, firefox, TOR all!) *** ###

You should now have received an e-mail from: [balam.ajaw2020@protonmail.com](balam.ajaw2020@protonmail.com) (Aka Andreas Johansson .... yeah fake name). 
This is an e-mail confirmation that your SSH key is added as allowed proxy user! Now we use either SSH (linux/unix or Putty) to setup an SSH tunnel through Iceland

<b>Windows example</b>

## Setup SSH Sock5 tunnel

Steps:
1) Startup Putty and add this info ![Start putty](https://i.ibb.co/DKyF7Sf/Putty-add-host-info.png)
2) Click on 'SAVE' to save this info
3) Now click on 'Connection' on the left side ![Click on connection](https://i.ibb.co/xjFsXKm/Putty-open-SSH-tunnel-info.png) 
4) Open the 'SSH' section by clicking on the + sign
5) Open the 'Auth' section by clicking on the + sign
6) Now click on 'Auth' to open the section ![Open Auth section](https://i.ibb.co/L5hsbbK/Putty-open-Auth-section.png)
7) Click on the 'browse' button and select your 'Putty private key' that you created earlier in the section "SSH Keys and Mega (cloud storage)" ![Select key](https://i.ibb.co/xmYvNnX/Putty-Select-putty-private-key.png)
8) Click on 'open'
8) Click on 'Tunnels', in the left side of the panel ![Add tunnel](https://i.ibb.co/fFQ2JsF/Putty-add-socks5-tunnel.png)
9) Make sure you fill in all the info correctly !! 
10) Click on the 'Add' button. You should now see this: ![Add tunnel](https://i.ibb.co/x20z9rz/Putty-verify-tunnel-info.png) 
11) Click on 'Session' in the top of the left panel. 
12) Then click on 'Save' button, on the right side of the panel ![Save key to session](https://i.ibb.co/N6nJqRm/Putty-Store-key-to-session.png)
13) Click on the 'Open' button
14) You should now see something similar to this. ![Socks5 Proxy open](https://i.ibb.co/YcPHjJS/Putty-tunnel-connected.png)

## Now we connect the TOR network over Socks5 proxy through Iceland. Follow instructions below:

Steps:
1) Open the Tor Browser (Do not connect!) ![Open network settings](https://i.ibb.co/M8dYb4H/Tor-Main-Network-Settings.png)
2) Setup Tor to use our Socks5 Proxy in Iceland ![Setup network](https://i.ibb.co/6Z527XF/Tor-Network-setup.png)
3) Scroll back to the top, and click 'Connect'
4) You should now see the Tor Browser page.


# *** Leave it running, because your system, browser or firefox needs TOR to connect to the internet *** 



