![Logo](https://i.imgur.com/vd7tjsE.png)

[![License](https://img.shields.io/badge/license-Public_domain-red.svg)](https://wiki.creativecommons.org/wiki/Public_domain)

**denybook** is a historical (Deny)list of malicious domains created as part of the periodic automated heuristic check (i.e. WHOIS, HTTP, etc.) of newly reported entries from public lists of malicious URLs (currently [CyberCrime](https://cybercrime-tracker.net/), [URLhaus](https://urlhaus.abuse.ch/), [ScumBots](https://twitter.com/scumbots), [Benkow](http://benkow.cc/passwords.php) and [VirusTracker](https://tracker.stf.st/)). Main goal is listing those that are/were malware **dedicated** (e.g. C&C) - thus, excluding compromised sites. It is supposed to be used for detection of malware beaconing infected clients by inspection of associated DNS traffic, with significant reduce of false-positives.

![Example](https://i.imgur.com/FN8r3um.png)

Up-to-date detailed CSV list of domains can be found [here](denybook.csv), while the raw TXT version can be found [here](https://raw.githubusercontent.com/spacial/DenyBook/master/denybook.txt).

Based on [stamparm](https://github.com/stamparm/blackbook) work.
