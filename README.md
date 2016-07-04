# wafid
 Wafid allows one to identify and fingerprint Web Application Firewall (WAF) products protecting a website.
#How does it work?
 Wafid sends a normal HTTP request and analyses the response; this identifies a number of WAF solutions.If that is not successful, it  sends a number of (potentially malicious) HTTP requests and uses simple logic to deduce which WAF it is If that is also not successful, it analyses the responses previously returned and uses another simple algorithm to guess if a WAF or security solution is actively responding to our attacks
 
 For further details, check out the source code on the main site, github.com/Cryin/wafid.
#What does it detect?
 It detects a number of WAFs. 360、Safedog、Anquanbao、Baidu Yunjiasu、Knownsec、BIG-IP、Barracuda、BinarySEC、BlockDos、Cisco ACE、CloudFlare、WebSphere、jiasule、Palo Alto and so on...
 
 Also you can add waf id with finger.xml!
#How do I use it?

 Usage: python wafid.py -u URL
 
#Questions?
 contact me:Cryin@insight-labs.org
 
 
