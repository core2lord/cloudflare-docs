---

order: 3
---

# Windows(10) DNS Modification Instructions

## Block malware

### IPv4
* Click the Start button and immediately begin typing the following 'ncpa.cpl'
* Confirm the correct filename was found then hit Enter on your keyboard to open the Network Connections Control Panel Item
* Right-click on the network you are connected to and then select Properties.
      NOTE: It's common to have multiple connection types, be sure to select the correct adapter.
* In the properties window, find and select Internet Protocol Version [4], then click the Properties button below.
* Here we are only interested in the lower section, this should be empty unless it was altered previously.
* Make sure to change the radio button selection to 'Use the following DNS server addresses' if not already.
* Remove all IP address that may have been entered previously with the following IP addresses below:

    * **1.1.1.2**
    * **1.0.0.2**
* Double-check the information is entered correctly, Click OK.

# IPv6
* Click on the Start menu, then click on Control Panel.
* Click on Network and Internet.
* Click on Change Adapter Settings.
* Right click on the Wi-Fi network you are connected to.
* Click Properties.
* Select Internet Protocol Version 6.
* Click Properties.
* Click Use The Following DNS Server Addresses.
* Remove any IP addresses that may be already listed and in their place add the following IP addresses:
    * **2606:4700:4700::1112**
    * **2606:4700:4700::1002**
* Double-check the information is entered correctly, Click OK.

## Block malware and adult content

### IPv4
* Click the Start button and immediately begin typing the following 'ncpa.cpl'
* Confirm the correct filename was found then hit Enter on your keyboard to open the Network Connections Control Panel Item
* Right-click on the network you are connected to and then select Properties.
      NOTE: It's common to have multiple connection types, be sure to select the correct adapter.
* In the properties window, find and select Internet Protocol Version [4], then click the Properties button below.
* Here we are only interested in the lower section, this should be empty unless it was altered previously.
* Make sure to change the radio button selection to 'Use the following DNS server addresses' if not already.
* Remove all IP address that may have been entered previously with the following IP addresses below:

    * **1.1.1.3**
    * **1.0.0.3**
* Double-check the information is entered correctly, Click OK.

# IPv6
* Click the Start button and immediately begin typing the following 'ncpa.cpl'
* Confirm the correct filename was found then hit Enter on your keyboard to open the Network Connections Control Panel Item
* Right-click on the network you are connected to and then select Properties.
      NOTE: It's common to have multiple connection types, be sure to select the correct adapter.
* In the properties window, find and select Internet Protocol Version [6], then click the Properties button below.
* Here we are only interested in the lower section, this should be empty unless it was altered previously.
* Make sure to change the radio button selection to 'Use the following DNS server addresses' if not already.
* Remove all IP address that may have been entered previously with the following IP addresses below:

    * **2606:4700:4700::1113**
    * **2606:4700:4700::1003**
* Double-check the information is entered correctly, Click OK.
