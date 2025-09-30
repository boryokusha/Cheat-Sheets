**Target Specification**:

	Scan a Single IP:	
		nmap 192.168.0.1
	Scan a Specific IPs:
		nmap 192.168.0.1 192.168.0.2
	Scan Range IPs:
		nmap 192.168.0.1-254 or 192.168.0.0/24
	Scan a domain:
		nmap tesla.com

**Scan Parameters**:

	-sS : TCP SYN port scan
	-sT : TCP connect port scan
	-sU : UDP port scan
	-sA : TCP ACK port scan
	-sL : No scan list targets only
	-p : Port specification -p (desired port)
	-sV : show the version of the running port
	-O : Remote Os detection
	-sC : Scan the default scripts

**Performance And Visibility Settings**:

	-T0 : Paranoid
	-T1 : Sneaky
	-T2 : Polite
	-T3 : Normal
	-T4 : Aggressive
	-T5 : Insane 
	
	Normally all scans running on T3 but when you need to pentest on black box or any sketchy activities 
	you need to use 0 or 1 for bypass IDS,IPS or Firewall devices.
**Output Parameters**:

	-oN : Normal output for use you need to be dedicated directory usage (-oN test.txt)
	-oA : Output on the three major file formats come in handy on the pentest reports
	
	
