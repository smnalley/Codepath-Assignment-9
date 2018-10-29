# Codepath-Assignment-9
Assignment 9: Honeypot, for Codepath course at MSU

Which Honeypot was deployed? Dionaea over HTTP

Any issues you encountered? 
- The github repository link given for mhn was out of date. I had to use a different one at https://github.com/RedolentSun/mhn.
- The admin console does not work for the mhn VM unless you specify Port 80 as an access point on the firewall. 
This is not listed as one of the ports you need to have open in the lab instructions.
- creating and downloading the json file through ssh on terminal does not work for everyone, 
and neither does ssh through the Google Cloud web app.
- Google Cloud will not instantiate a project if the Google Cloud account is created with an msstate.edu GMail account.

Summary of data collected:
Attacks in the last 24 hours: 6,241
Top 5 attacker IPs:
1) United States 130.18.104.168 (997 attacks)
2) United States 209.141.35.236 (202 attacks)
3) Hong Kong 103.72.165.5 (201 attacks)
4) United Kingdom  185.58.224.223 (190 attacks)
5) United Kingdom  46.101.9.8 (159 attacks)
TOP 5 Attacked ports:
1)8088 (2,184 times)
2)5060 (260 times)
3)23 (239 times)
4)80 (229 times)
5)445 (165 times)
TOP 5 Honey Pots:
dionaea (6,241 attacks)
TOP 5 Sensors:
mhn-honeypot-1 (6,241 attacks)
TOP 5 Attacks Signatures: (blank)

Any unresolved questions raised by data collected?
- Why are specific ports more popular than others for attacks? Is this a function of the honeypot implementation,
or a function of the attackers' tools?
- What proportion of these hacks are actually malicious? How many might arise from white-hat pentesters?
Point being, if so much hacking goes on at such a large scale and these honeypots show us the hacker's IP address, 
why aren't more of them criminally investigated?
- What tools are these hackers using to quickly find this honeypot and try to hack it?
