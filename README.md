FuzzDB was created to increase the likelihood of finding application security vulnerabilities through dynamic application security testing. It's the first and most comprehensive open dictionary of fault injection patterns, predictable resource locations, and regex for matching server responses.

Attack Patterns - FuzzDB contains comprehensive lists of [attack payload] primitives for fault injection testing. These patterns, categorized by attack and where appropriate platform type, are known to cause issues like OS command injection, directory listings, directory traversals, source exposure, file upload bypass, authentication bypass, XSS, http header crlf injections, SQL injection, NoSQL injection, and more. For example, FuzzDB catalogs 56 patterns that can potentially be interpreted as a null byte and contains lists of [commonly used methods]) such as "get, put, test," and name-value pairs than [trigger debug modes]

Discovery - The popularity of standard software packaging distribution formats and installers resulted in resources like logfiles and administrative directories frequently being located in a small number of [predictable locations]. FuzzDB contains a comprehensive dictionary, sorted by platform type, language, and application, making brute force testing less brutish.
https://github.com/fuzzdb-project/fuzzdb/tree/master/discovery

Response Analysis - Many interesting server responses are [predictable strings] FuzzDB contains a set of regex pattern dictionaries to match against server responses. In addition to common server error messages, FuzzDB contains regex for credit cards, social security numbers, and more.

Other useful stuff - Webshells in different languages, common password and username lists, and some handy wordlists.

Documentation - Many directories contain a README.md file with usage notes. A collection of [documentation] from around the web that is helpful for using FuzzDB to construct test cases is also included.

How people use FuzzDB
FuzzDB is like an application security scanner, without the scanner. Some ways to use FuzzDB:

Website and application service black-box penetration testing with
OWASP Zap proxy's FuzzDB Zap Extension
Burp Proxy's intruder tool and scanner
PappyProxy, a console-based intercepting proxy
To identify interesting service responses using grep patterns for PII, credit card numbers, error messages, and more
Inside custom tools for testing software and application protocols
Crafting security test cases for GUI or command line software with standard test automation tools
Incorporating into other Open Source software or commercial products
In training materials and documentation
To learn about software exploitation techniques
To improve your security testing product or service
How were the patterns collected?
Many, many hours of research and pentesting. And

Analysis of default app installs
Analysis of system and application documentation
Analysis of error messages
Researching old web exploits for repeatable attack strings
Scraping scanner payloads from http logs
Various books, articles, blog posts, mailing list threads
Other open source fuzzers and pentest tools and the input of contributors: https://github.com/fuzzdb-project/fuzzdb/graphs/contributors
Places you can find FuzzDB
Other security tools and projects that incorporate FuzzzDB in whole or part

OWASP Zap Proxy fuzzdb plugin https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project
SecLists https://github.com/danielmiessler/SecLists
TrustedSec Pentesters Framework https://github.com/trustedsec/ptf
Rapid7 Metasploit https://github.com/rapid7/metasploit-framework
Portswigger Burp Suite http://portswigger.net
Protofuzz https://github.com/trailofbits/protofuzz
BlackArch Linux https://www.blackarch.org/
ArchStrike Linux https://archstrike.org/
