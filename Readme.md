1. Scan with nmap.

	$$ nmap -sV -sC -oN nmap 10.10.122.142

	==> # Nmap 7.91 scan initiated Thu Feb 10 07:05:27 2022 as: 
		Nmap scan report for 10.10.122.142
		Host is up (0.32s latency).
		Not shown: 998 closed ports

		PORT   STATE SERVICE VERSION
		
		22/tcp open  ssh     OpenSSH 7.2p2 Ubuntu 4ubuntu2.6 (Ubuntu Linux; protocol 2.0)
		| ssh-hostkey: 
		|   2048 43:39:50:55:f7:39:4f:3c:d1:d2:89:c1:cb:41:32:36 (RSA)
		|   256 b9:00:54:69:53:16:4b:bc:64:dd:0b:ba:53:e8:eb:ec (ECDSA)
		|_  256 68:8a:75:2e:12:d4:b8:93:4e:63:7c:93:39:b0:06:df (ED25519)

		80/tcp open  http    Apache httpd 2.4.18 ((Ubuntu))
		|_http-server-header: Apache/2.4.18 (Ubuntu)
		|_http-title: Rick is sup4r cool

		Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel
		# Nmap done at Thu Feb 10 07:06:03 2022 -- 1 IP address (1 host up) scanned in 35.43 seconds


2. 

	$$ nikto -h http://10.10.122.142 | tee nikto.log

	==> 



## Robots.txt: 'Wubbalubbadubdub' (This is actually the password)


<!--

    Note to self, remember username!

    Username: R1ckRul3s

  -->



# If python -V returned 2.X.X
python -m SimpleHTTPServer

# If python -V returned 3.X.X
python3 -m http.server

# Note that on Windows you may need to run python -m http.server instead of python3 -m http.server


