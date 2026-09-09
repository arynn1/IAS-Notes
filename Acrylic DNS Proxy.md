### Step 1 Install Acrylic DNS Proxy on windows

### Step 2 Navigate to Program Files (x86) and open the Acrylic DNS Proxy folder
![](Pasted%20image%2020260909203846.png)
### Step 3 Open AcrylicConfigration.ini and AcrylicHosts.txt
![](Pasted%20image%2020260909203951.png)
### Step 4 Change These lines in the config file
![](Pasted%20image%2020260909204032.png)
for the primary server address (near the top)
![](Pasted%20image%2020260909204138.png)
OPTIONAL: for secondary server address
![](Pasted%20image%2020260909204252.png)
remove the ';' to enable all pcs to request for DNS (near the bottom)

### Step 5 Change These lines in the hosts file
![](Pasted%20image%2020260909204416.png)
add all the dns addresses you need (near the bottom)

template: (ip address) (url/domain name)
example: 10.10.10.1 netacadz.org www.netacads.org 

### Step 6 Open Services and restart the Acrylic DNS Proxy service
![](Pasted%20image%2020260909204656.png)
![](Pasted%20image%2020260909204708.png)
Click restart