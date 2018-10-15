<div align="center" style="max-width:100%">
	<img width="300" src="media/logo.svg" alt="infosec.guide">
	<h1 align="center">infosec.guide</h1>
	<br><br><br>
</div>

This is an introductory guide to tools, knowledge and resources useful for those in the InfoSec field. I was inspired to make this after seeing [Sindre Sorhus' awesome list](https://github.com/sindresorhus/awesome/) and also realising that the domain [infosec.guide](http://infosec.guide/) was available. Different from Sorhus' awesome list, this list will include things that are probably less than awesome, like proprietary software, because they are widely recognised and used.

If you think the list lack something that could be useful, either do a pull request or file an issue. Either way is fine, but please format it as following:

- [Awesome thing](https://awesome-thing.com/) - Description of awesome thing.

**Anything else won't be accepted.** You could also suggest a new section if you believe it does not fit the ones below.

This is by no means any study plan or definite guide to every aspect that you will probably need, however I do think that as this list grows it will be able to give you a helping hand in what to learn next. If, however, you want me to create a sort of study plan, just ping me and I will try to start a list for that as well. A good starting point is to build stuff in Python (or any high-level language) and try to correlate it with InfoSec. Build a scraper; build something that utilises an exploit that you've heard of. The interpreter is the limit.

## Contents

- [Programming Languages](#programming-languages)
- [Books](#books)
- [Editors](#editors)
- [Software](#software)
- [Journals](#journals)
- [Blogs](#blogs)
- [Podcasts](#podcasts)
- [Video channels](#video-channels)
- [Guides and cheat sheets](#guides-and-cheat-sheets)
- [Other](#other)

## Programming languages

### Low level

- [C](https://en.wikipedia.org/wiki/C_\(programming_language\)) - Low-level language useful to know if you are planning to dig into operative systems and understand their inner workings.
- [Go](https://golang.org/) - Go (or golang) is a new language by Google that is specialises in concurrent execution. It is useful for making scalable web servers, but also for InfoSec tools that require speed. [Bettercap](https://github.com/bettercap/bettercap) is written in Go.
- [Rust](https://www.rust-lang.org/) - Rust is a blazingly fast language with focus on safe and secure code. [Redox](https://www.redox-os.org), a new microkernel based operative system, is written in Rust.

### High level

- [Python](https://www.python.org/) - Python is a valuable tool for scripting things that cannot easily be done in shell scripting. It's also the perfect beginner's language with an extensive library and many resources available.

### Scripting etc

- [bash](https://www.gnu.org/software/bash/) - Unix shell with its own command language that can be executed as shell script files (.sh).
- [cmd](https://en.wikipedia.org/wiki/Cmd.exe) - Windows' CLI with a primitive scripting language that can be executed as batch files (.bat).
- [Powershell](https://github.com/powershell/powershell) - Microsoft's framework for task automation with its own scripting language. Useful from devOps to keystroke injection.

## Books

### Operative systems

- [The Design and Implementation of the FreeBSD Operating System, Second Edition](https://www.amazon.com/Design-Implementation-FreeBSD-Operating-System/dp/0321968972) - An extensive book about FreeBSD's kernel and internal workings.

### Privacy, surveillance, censorship and privacy

- [Data and Goliath by Bruce Schneier](https://www.schneier.com/books/data_and_goliath/) - An important book to read to understand aspects of data collection, surveillance, censorship and privacy.

### Management

- [The Book of Risk by Dan Borge](https://www.bookdepository.com/Book-Risk-Dan-Borge/9780471323785) - An introduction to why and how you should think about risk management.

### Learning hacking tools

- [Metasploit Penetration Testing Cookbook by M. Agarwal and A. Singh](https://www.packtpub.com/networking-and-servers/metasploit-penetration-testing-cookbook) - Featuring over 80 recipes to master the most widely used penetration testing framework, this is a good book to start with if you know little to nothing about how to use the MSF framework and Metasploit.
- [Penetration Testing by Georgia Weidman](https://nostarch.com/pentesting) - A highly praised introduction to pentesting going over a wide range of techniques. NB: [Second edition is in the works.](https://twitter.com/georgiaweidman/status/1001162312965869568)

### Miscellaneous

- [PoC||GTFO by Travis Goodspeed et al.](https://www.alchemistowl.org/pocorgtfo/) - Valuable source of both knowledge and inspiration to any hacker of any sort. In addition to the free issues available online, they are also published as a book that looks like a bible (because it is).
- [Schneier on Security by Bruce Schneier](https://www.schneier.com/books/schneier_on_security/) - Collection of essays from June 2002 to June 2008 that was published on his blog. For those with little to no initial knowledge in the field, this is a really good book to start with.

## Editors

### GUI

- [Atom](https://github.com/atom/atom) - GitHub's open source editor that is highly customisable with unique features like collaborative writing (Teletype, using WebRTC).
- [Mark Text](https://github.com/marktext/marktext/) - Mark Text is an open source Markdown editor that features WYSIWYG editing, focus and typewriter modes, as well as a dark theme for your sore eyes. Can export to PDF and HTML.
- [Visual Studio Code](https://github.com/Microsoft/vscode) - Microsoft's open source editor with a wide range of features like git integration, plugins and debuggers.

### Terminal

- [emacs](https://www.gnu.org/software/emacs/) - More than just a text editor. Highly customisable with a mind boggling set of features.
- [Nano](https://www.nano-editor.org/) - A very simple text editor that is easy to learn.
- [vim](https://www.vim.org) - Vim is a highly configurable and efficient text editor. (You quit vim by typing ":q")

## Software

### Frameworks

- [Metasploit Framework](https://github.com/rapid7/metasploit-framework) - Vulnerability and exploitation automation framework.

### Automatic exploitation tools

- [sqlmap](https://github.com/sqlmapproject/sqlmap) - Automatic SQL injection and database takeover tool.

### Disassemblers and debuggers

- [Cutter](https://github.com/radareorg/cutter) - GUI frontend for radare 2.
- [IDA Pro](https://www.hex-rays.com/products/ida/index.shtml) !--NOT FOSS--! - IDA Pro is a widely used proprietary disassembler and debugger.
- [Radare 2](https://github.com/radare/radare2) - Forensics tool, scriptable CLI editor able to open disk files, analysing binaries, disassembling code, debugging programs, attaching to remote gdb servers, and so forth.
- [x64dbg](https://github.com/x64dbg/x64dbg) - Open-source x64/x32 debugger for Windows.

### Information gathering

- [amass](https://github.com/caffix/amass) - In-depth subdomain enumeration written in Go.
- [DotDotPwn](https://github.com/wireghoul/dotdotpwn) - Directory Traversal Fuzzer
- [Golismero](https://github.com/golismero/golismero) - Open source framework for security testing.
- [Lynis](https://github.com/CISOfy/lynis) - Security auditing tool assisting compliance testing and system hardening.
- [Masscan](https://github.com/robertdavidgraham/masscan) - TCP port scanner, spews SYN packets asynchronously, scanning entire Internet in under 5 minutes.
- [Nikto](https://github.com/sullo/nikto) - Open source webscanner.
- [Nmap](https://github.com/nmap/nmap) - Network mapper; scans ports and has scripitng capabilities.
- [Pyparazzi](https://github.com/vagnes/pyparazzi) - Link scanning on any domain.
- [Recon-ng](https://bitbucket.org/LaNMaSteR53/recon-ng) - Web Reconnaissance framework written in Python.
- [Snort](https://www.openhub.net/p/snort) - lightweight network IDS, with real-time traffic analysis and packet logging on IP networks.
- [Tripwire](https://github.com/Tripwire/tripwire-open-source) - Security and data integrity tool for monitoring and alerting on file & directory changes.

### Linux/BSD/UNIX tools

> These tools are not a complete overview of what you need to know to get started using the terminal environment effectively. For that, there is a good and easy to follow [video tutorial by Joe Collins](https://www.youtube.com/watch?v=oxuRxtrO2Ag) that would help you.

- [alias](https://www.linux.org/docs/man1/alias.html) - Creates an [alias](http://www.linfo.org/alias.html).
- [base64](https://www.linux.org/docs/man1/base64.html) - Base64 encode/decode data and print to standard output.
- [csplit](https://www.linux.org/docs/man1/csplit.html) - Split a file into sections determined by context lines
- [curl](https://www.linux.org/docs/man1/curl.html) - Transfer data from or to a server, using various protocols.
- [cut](https://www.linux.org/docs/man1/cut.html) - Remove sections from each line of files.
- [file](https://www.linux.org/docs/man1/file.html) - Determine file type.
- [find](https://www.linux.org/docs/man1/find.html) - Search for files in a directory hierarchy.
- [grep, egrep, fgrep](https://www.linux.org/docs/man1/grep.html) - Print lines matching a pattern.
- [gzip, gunzip, zcat](https://www.linux.org/docs/man1/gzip.html) - Compress or expand files.
- [hexdump](https://www.linux.org/docs/man1/hexdump.html) - Display file contents in ascii, decimal (base10), hexadecimal (base16), or octal (base8).
- [history](https://www.linux.org/docs/man1/history.html) - Display the command history list with line numbers.
- [link](https://www.linux.org/docs/man1/link.html) - Create a [hard link or symbolic link (symlink)](https://en.wikipedia.org/wiki/Ln_(Unix)).
- [strings](https://www.linux.org/docs/man1/strings.html) - Print the strings of printable characters in files.
- [pinky, finger](https://www.linux.org/docs/man1/pinky.html) - Displays user activity.
- [tail](https://www.linux.org/docs/man1/tail.html) - Output the last part of files.
- [unzip](https://www.linux.org/docs/man1/unzip.html) - List, test and extract compressed files in a ZIP archive.
- [zipgrep](https://www.linux.org/docs/man1/zipgrep.html) - Search files in a ZIP archive for lines matching a pattern.
- [zip](https://www.linux.org/docs/man1/zip.html) - Package and compress (archive) files.

## Projects

### Privacy

- [Tor](https://torproject.org/) - A network that helps you defend against traffic analysis, network surveillance etc.

## Journals and indices

- [CVE](https://cve.mitre.org/) - Common Vulnerabilities and Exposures is a list of publicly known cybersecurity vulnerabilities.
- [Directory of Open Access Journals (DOAJ)](https://doaj.org/) - DOAJ is a community-curated online directory that indexes open access, peer-reviewed journals. All data is freely available under CC BY-SA.

## Blogs

- [Krebs on Security](https://krebsonsecurity.com/) - Brian Krebs is an American journalist and investigative reporter with great coverage on cybercrime.
- [Schneier on Security](https://www.schneier.com/) - Bruce Schneier is an American cryptographer, computer security professional, privacy specialist and writer.
- [Talos Intelligence](https://blog.talosintelligence.com/) - Cisco Talos Intelligence Group is one of the largest commercial intelligence teams in the world.
- [Shawn Webb (@lattera)](https://github.com/lattera/articles/) - Security engineer for and cofounder of HardenedBSD.

## Podcasts

- [Defensive Security](https://defensivesecurity.org/) - Cyber security podcast covering breaches and strategies for defence.

## Video channels

- [13Cubed](https://www.youtube.com/channel/UCy8ntxFEudOCRZYT1f7ya9Q) - Infosec related topics including Digital Forensics and Incident Response (DFIR) and Penetration Testing.

## Governmental sites

- [The National Cyber Security Centre](https://www.ncsc.gov.uk/) - NSCS of the UK.
- [CRSC](https://csrc.nist.gov/) - Computer Security Resource Center of National Institute of Standards and Technology.

## Guides and cheat sheets

### Web security

- [Hacker101](https://www.hacker101.com/) - Free class for web security for those interested in bug bounties as well as seasoned security professionals.
- [SQL Injection Cheat Sheet](https://www.netsparker.com/blog/web-security/sql-injection-cheat-sheet/) - Many different variants of the SQL Injection vulnerability.
- [SQL Injection Knowledge Base](https://websec.ca/kb/sql_injection) - Many different variants of the SQL Injection vulnerability.

## Other

- [asciinema](https://asciinema.org/) - Record and share your terminal sessions. Entirely terminal based; no GIFs or videos.
- [peek](https://github.com/phw/peek) -  Simple animated GIF screen recorder with an easy to use interface.
