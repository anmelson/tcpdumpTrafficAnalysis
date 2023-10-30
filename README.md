<h1>Analyzing Traffic with Linux tcpdump</h1>

<h2>Description</h2>
This was a simple project with the purpose of learning the different arguments available for tcpdump and utilize them, as well as to write a simple script to capture packets and write them to a pcap file for analysis with Wireshark or with tcpdump itself.
<br />

<h2>Languages and Utilities Used</h2>

- <b>tcpdump</b> 
- <b>Wireshark</b>

<h2>Arguments Used </h2>

- <b>-c, -w, -#, -XX, -tttt, -G, -C, -D, -i, host, port</b>

<h2>Program walk-through:</h2>

<p align="center">
Using tcpdump to capture 10 packets: <br/>
<img src="https://imgur.com/YdkKBlX.png" height="80%" width="80%" alt="tcpdump usage"/>
<br />
<br />
Using tcpdump to check network interfaces and capture packets from a specific interface:  <br/>
<img src="https://i.imgur.com/D1592yg.png" height="80%" width="80%" alt="tcpdump usage"/>
<br />
<br />
Using tcpdump to capture 10 packets from a specific host: <br/>
<img src="https://i.imgur.com/Hu3aMJz.png" height="80%" width="80%" alt="tcpdump usage"/>
<br />
<br />
Creating a simple script to capture packets from a host and write them to a pcap file:  <br/>
<img src="https://i.imgur.com/fEzpbD6.png" height="80%" width="80%" alt="tcpdump usage"/>
<br />
<br />
Analyzing the traffic in Wireshark:  <br/>
<img src="https://i.imgur.com/GFguxUl.png" height="80%" width="80%" alt="Wireshark usage"/>
<br />
<br />
Creating a script to use an expression to capture GET traffic:  <br/>
<img src="https://i.imgur.com/OHRiby4.png" height="80%" width="80%" alt="tcpdump usage"/>
<br />
<br />
Creating a script to listen for incoming SSH traffic:  <br/>
<img src="https://i.imgur.com/6yw8k2g.png" height="80%" width="80%" alt="tcpdump usage"/>
</p>
