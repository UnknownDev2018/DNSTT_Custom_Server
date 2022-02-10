I made a small project based on DNSTT I did all my effort to do it as fast as possible I will give a short explanation of its functions and installation of the server also important things that I recommend at the time of jumping our firewall, this installer only works with the DNSTT application Custom just won't work elsewhere. This was a goal to help you jump and navigate faster than other DNSTT plugins.

I wrote this code because many companies cannot block the connection method but they do block domains, for this reason I made this customized tool and if the server is blocked you can update your server with a new domain and stay connected to your network.

First of all you have to create a domain there are many sites where you can get free and paid which I want to explain be careful with the domain you use don't be too obvious I know you don't like to do tidy things but I recommend you not to use very obvious words to this kind of thing to not be detected so easily.

Normally we usually use domains such as (dns.slow.jaquemate.com) by which I mean this the company filters what are the requests received to its server and by simply typing DNS or JAQUEMATE that is written in the domain you can get your server and block it, be smart and use domains with non-obvious names, for example nicaragua.jnadjjdsfodf.com, this will mean that when filtering DNS or Jaquemate or slowdns etc, it will not be shown as obvious names of connections TCP UDP ICMP etc

Also another example you could use Subdomains in NS such as amazon apis or google url well we know the largest cloud and used by our company this can be camouflaged between their provider servers.

Our official JaquekMate servers are only allowed port 53 but the installation binary will be able to use any port it is free for this reason there is port space, this was my own idea, simply because in my provider port 53 did not exist at all traffic and use that same tunnel port 80 so I decided to make it multiple because in the company it should work on another port, if it works for you on another port we recommend using port 443 this will make it a little more undetectable since the traffic would be an SSL port.

Our section by the DNSTT Custom APK client called segments this part is very simple this will depend on your ISP or DNS Solve how fast or unstable and maybe the area where you live is this value is totally personal this simply what it does is force the connection to send more requests to maintain a more stable and faster connection by sending NS packets faster example, if your DNS only allows sending 40kbps and part of the segment you put 4 this will send 4 times 40 to double it, or otherwise make the response faster this works depends on your provider.

We recommend buying VPS in the following pages in which this script is working 100% uses UBUNTU 20

https://greencloudvps.com/billing/aff.php?aff=3478

https://my.hostus.us/aff.php?aff=2897

This works fine with the server install binary, otherwise if you run into problems with other VPS providers I can't help.


Information about the installation binary server:

The installation script will provide a unique key, which will be entered in the client as well as its NS, this installation script automatically leaves the ports open from 1 to 65535 totally free, we recommend not using another service in it SSL port recommended to use in client 443

INSTALL Command

apt-get install wget

wget https://raw.githubusercontent.com/UnknownDev2018/DNSTT_Custom_Server/main/DNSTT-Custom-Server-Binary -O DNSTT-Custom-Server-Binary && chmod +x DNSTT-Custom-Server-Binary

./DNSTT-Custom-Server-Binary

Reboot Server
