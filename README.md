<h1>Performing ARP Poisoning</h1>


<h2>Description</h2>
In this lab, I learned to perform ARP poisoning. ARP (Address Resolution Protocol) is a stateless protocol used for resolving IP addresses to machine MAC addresses. In ARP spoofing, ARP packets can be forged to send data to the attacker’s machine. ARP spoofing is also known as ARP poisoning.
<br />



<h2>Environments Used </h2>

- <b>Windows 10 Pro</b> 

<h2>Utilities and Language </h2>

- <b>Hyper-V Manager</b>

<h2>Program walk-through:</h2>

<p align="center">
Click on the Hyper-V manager icon and double click the kali to start it then click start <br>
<img src="https://i.postimg.cc/635G50df/Screen-Shot-2023-03-06-at-4-22-32-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
<img src="https://i.postimg.cc/k4pDMdM7/Screen-Shot-2023-03-06-at-4-24-16-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
  
  
  
  
<br />
Enter credentials to access Kali machine <br>
<img src="https://i.postimg.cc/MT7xN2cs/Screen-Shot-2023-03-06-at-4-29-13-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />



<br />
Minimiaze the Kali machine and then boot up the windows 10 machine<br>
<img src="https://i.postimg.cc/HW6FxkCw/Screen-Shot-2023-03-06-at-4-32-18-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />



<br />
Return to the Kali machine and navigate to the 09-Sniffing & Spoofing ettercap-graphical <br>
<img src="https://i.postimg.cc/qR6VHfNf/Screen-Shot-2023-03-06-at-4-52-12-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />

  
  
  
<br />
Verify the primary interface and click the check icon<br>
Click the Ettercap menu and click hosts then click host list <br>
Click the Ettercap menu again then click hosts and then scan for hosts <br>
Click target ip address and add to target 1 <br>
Click second target ip address and add to target 2 <br>
<img src="https://i.postimg.cc/nzbTrNdf/Screen-Shot-2023-03-06-at-4-57-54-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
 
 
<br />
Click the MITM menu now and click arp poisoning and verify that the sniff remote connections checkbox is checked and then click ok  <br>
<img src="https://i.postimg.cc/wMxXszLZ/Screen-Shot-2023-03-06-at-5-01-06-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br /> 

<img src="https://i.postimg.cc/x8WdVyf5/Screen-Shot-2023-03-06-at-5-04-51-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br /> 
 
 
 
 

  
<br />
 Return to the Windows 10 machine and navigate to firefox and enter a url and login <br>
<img src="https://i.postimg.cc/90Vhd8Qv/Screen-Shot-2023-03-06-at-5-09-15-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />   
  
  
  
  
  
  
  
<br />
 You will observe the login credentials and URL in the ettercap toolbar  <br>
<img src="https://i.postimg.cc/1z97rkG0/Screen-Shot-2023-03-06-at-5-20-12-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />   













