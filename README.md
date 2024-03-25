Catalog categorized lists of domain names people may want to block. Current focus is on corporations.

Files in this project list the domain names of servers: one per line can be added to the local hosts file to block connections to servers on that domain name

These domain names can be also added to [pi-hole](https://github.com/pi-hole/pi-hole) blocklists for network-wide effect.

Hosts file Location:

- Linux, Unix and macOS: `/etc/hosts`
- Windows: `C:\WINDOWS\system32\drivers\etc\hosts`

Domains can also be efficiently blocked with [Dnsmasq](https://thekelleys.org.uk/dnsmasq/doc.html) and [Privoxy](https://www.privoxy.org/). See [drduh/config/domains](https://github.com/drduh/config/tree/master/domains) and [drduh/config/privoxy/user.action](https://github.com/drduh/config/blob/master/privoxy/user.action) for examples.

Additional ad server, malware and other blocklists can be found at [StevenBlack/hosts](https://github.com/StevenBlack/hosts) and [Sinfonietta/hostfiles](https://github.com/Sinfonietta/hostfiles)
