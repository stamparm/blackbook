![Logo](https://i.imgur.com/Nji9ubM.jpg)

[![License](https://img.shields.io/badge/license-Public_domain-red.svg)](https://wiki.creativecommons.org/wiki/Public_domain)

**blackbook** is a historical (black)list of malicious domains created as part of the hourly automated heuristic check (i.e. WHOIS, HTTP, etc.) of newly reported entries from public lists of malicious URLs (currently [CyberCrime](https://cybercrime-tracker.net/), [URLhaus](https://urlhaus.abuse.ch/), [ScumBots](https://twitter.com/scumbots) and [Benkow](http://benkow.cc/passwords.php)) in search of those that are/were malware **dedicated** (e.g. C&C) - thus, excluding compromised sites. It is supposed to be used for detection of malware beaconing infected clients by inspection of associated DNS traffic with significantly reduced number of false-positives.

![Example](https://i.imgur.com/FN8r3um.png)

Up-to-date list of domains can be found [here](blackbook.csv).

Note: If you just need a (newline delimited) domain list you can run:

`curl https://raw.githubusercontent.com/stamparm/blackbook/master/blackbook.csv 2>/dev/null | cut -d ',' -f 1 | tail -n +2`
