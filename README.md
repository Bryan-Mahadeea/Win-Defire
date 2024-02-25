Windows Defender Firewall is a host-based software firewall that is included with the Windows operating system. We will learn to configure firewall rules using Windows Defender Firewall and Windows Defender Firewall with Advanced Security.

Objectives
Configure Firewall Rules Using Windows Defender Firewall

Configure Firewall Rules Using Windows Defender Firewall
1. Click the Windows Start button. and then select Windows Security.

![Alt text](https://github.com/Bryan-Mahadeea/Win-Defire/blob/main/1.png)

2. Click the Windows Start button. and then select Windows Security.

![Alt text](https://github.com/Bryan-Mahadeea/Win-Defire/blob/main/2.png)

3 Here you will see the firewall status for the following:
**Domain network:** Domain networks are workplace networks. A computer must be a part of the domain in order to communicate with other computers on that network.
**Private network:** Private networks are discoverable networks, meaning that only devices on that network can see or discover other devices on that same network. Home networks are a good example of a private network.
**Public network:** Public networks are non-discoverable networks. A non-discoverable network is a network where your device cannot be discovered by other devices on your network. A coffee shop or a library would be a good example of a public network. You do not want other individuals to be able to discover your device.

![Alt text](https://github.com/Bryan-Mahadeea/Win-Defire/blob/main/3.png)

4. Click Domain network.

![Alt text](https://github.com/Bryan-Mahadeea/Win-Defire/blob/main/4.png)

5. Verify that the Windows Defender Firewall is toggled to On. Note the checkbox under Incoming connections. This is a quick access location that blocks all incoming domain network traffic – even traffic that is normally permitted. Select the back arrow button to return to the Firewall and network protection window.

![Alt text](https://github.com/Bryan-Mahadeea/Win-Defire/blob/main/5.png)

6. Click Private network.

![Alt text](https://github.com/Bryan-Mahadeea/Win-Defire/blob/main/6.png)

7. Verify that the Windows Defender Firewall is toggled to On. Note the checkbox under Incoming connections. This is a quick access location that blocks all incoming private network traffic – even traffic that is normally permitted. Select the back arrow button to return to the Firewall and network protection window.

![Alt text](https://github.com/Bryan-Mahadeea/Win-Defire/blob/main/7.png)

8. Click Public network.

![Alt text](https://github.com/Bryan-Mahadeea/Win-Defire/blob/main/8.png)

9. Verify that the Windows Defender Firewall is toggled to On. Note the checkbox under Incoming connections. This is a quick access location that blocks all incoming public network traffic – even traffic that is normally permitted. Select the back arrow button to return to the Firewall and network protection window.

![Alt text](https://github.com/Bryan-Mahadeea/Win-Defire/blob/main/9.png)


10. Click Allow an app through firewall.

![Alt text](https://github.com/Bryan-Mahadeea/Win-Defire/blob/main/10.png)

11. Scroll to Mozilla Firefox. Note that the current configuration allows for Firefox to communicate on the Private network but denies it from communicating on the Public network.

![Alt text](https://github.com/Bryan-Mahadeea/Win-Defire/blob/main/11.png)

12. Click the Public box next to Firefox. A checkmark will appear. Click OK to return to the Firewall & network protection screen. Users will now be able to use Mozilla Firefox on the public network.

![Alt text](https://github.com/Bryan-Mahadeea/Win-Defire/blob/main/12.png)

