

### Step 1: Install Acrylic DNS Proxy on Windows
[Download Acrylic DNS Proxy](https://sourceforge.net/projects/acrylic/)

### Step 2: Navigate to Program Files (x86) and open the Acrylic DNS Proxy folder
![](assets/Pasted%20image%2020260909203846.png)

### Step 3: Open AcrylicConfiguration.ini and AcrylicHosts.txt
![](assets/Pasted%20image%2020260909203951.png)

### Step 4: Change these lines in the config file
![](assets/Pasted%20image%2020260909204032.png)

*   **For the primary server address** (near the top):
    ![](assets/Pasted%20image%2020260909204138.png)
*   **OPTIONAL: For the secondary server address:**
    ![](assets/Pasted%20image%2020260909204252.png)
*   **Remove the `;`** to enable all PCs to request for DNS (near the bottom).

### Step 5: Change these lines in the hosts file
![](assets/Pasted%20image%2020260909204416.png)

Add all the DNS addresses you need (near the bottom).

*   **Template:** `[ip address] [url/domain name]`
*   **Example:** `10.10.10.1` [netacadz.org](http://netacadz.org) [www.netacads.org](http://www.netacads.org)

### Step 6: Open Services and restart the Acrylic DNS Proxy service
![](assets/Pasted%20image%2020260909204656.png)
![](assets/Pasted%20image%2020260909204708.png)

*   Click **Restart**.