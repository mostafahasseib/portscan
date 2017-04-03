# portscan
port scan



for More Help: portscan.py -h
python portscan.py -h www.whatever.com -p 443 80 110 
(443 80 110) port that wanted to check it 

[+] Scan Results for: 119.75.218.70
		Scanning port 443
		Scanning port 110
		Scanning port 80
		[+]443/tcp open
		[+] HTTP/1.1 302 Moved Temporarily
		Server: bfe/1.0.8.18
		Date: Sun, 03 mar 2017 08:43:40 GMT
		Content-T
		[-]110/tcp closed
		[-]80/tcp closed
    
    
    Also, You can local test , The python script support domain or ip mode
	Example:
		python PortScan.py -H 127.0.0.1 -p 80
