
# HANDS ON STATIC ANALYSIS 🧑‍💻
- Get Malware samples which you want and download it (Go snd copy paste it to browser to download) - [Malware](https://urlhaus.abuse.ch/browse/)
- Download [HXD](https://github.com/Tripati3000/Malware-ANALYSIS/blob/main/HxDSetup.zip) to configure the keywrods and paste the malware file on it. 
- Find keywords - **4D,5A,MZ,This program cannot be run on DOS mode**
- If these keywords the file may have then it is a malware because if it is any kind like Jpeg,jpg,pdf,exe or anything else these keywords are there and it means it is executable.
- if we do any changes like making jpeg to exe or anykind of changes, the file will not change❌

# Checking file is which type of malware like trojan,virus or something else

# Open [Hashmyfiles](https://github.com/Tripati3000/Malware-ANALYSIS/blob/main/hashmyfiles-x64.zip)

# Drag and put the file on it👇 and copy🔗 the given line👍

<img src="https://github.com/Tripati3000/Malware-ANALYSIS/assets/160244601/ffe2d66d-0bfe-4463-b6ca-46781073fed2" height="80%" width="80%" alt="SIEM System steps"/>

# After Copy the line 🔗 Paste it on [virustotal](https://www.virustotal.com/gui/) in browser

<img src="https://github.com/Tripati3000/Malware-ANALYSIS/assets/160244601/0f91512b-0aef-402b-9b7d-6a8f5e27fd26" height="80%" width="80%" alt="SIEM System steps"/>

# It shows malware file details👍

<img src="https://github.com/Tripati3000/Malware-ANALYSIS/assets/160244601/487f8590-243d-42ed-b54e-db6392019f21" height="80%" width="80%" alt="SIEM System steps"/>

# If you want to search something like strings in malware file or anything you can use [bintext](https://github.com/Tripati3000/static-ANALYSIS/blob/main/bintext303.zip) (You can download the raw file from my added files)

- **Install it and open it up👇**

- **Drag the file paste it here 👇 and you can search whatever you want yo know👍**

<img src="https://github.com/Tripati3000/static-ANALYSIS/assets/160244601/d4f6e15c-47e4-4426-bca8-629000bf29fc" height="80%" width="80%" alt="SIEM System steps"/>

# Packing

**Packing in malware is like wrapping it up in layers of disguise to make it harder for security tools to detect. It's a bit like putting a fancy cover on a book to hide its real content. The packed malware looks harmless at first glance, but once it's opened, its true harmful nature is revealed. It was attackers technique to hide files. neither any virustotal or any websites cannot detect it.**

**There are some popular packers like**

- UPX (Ultimate Packer for eXecutables)
- PE compact
- Themida
- VM protect
- Armadillo
- 

# Lets Know how we can do it 

# Encode (to know what pack it uses?)

- Download exeinfo - https://exeinfo-pe.en.uptodown.com/windows

**Drag and put it here 👇 and you can see that it is UPX**
  
<img src="https://github.com/Tripati3000/static-ANALYSIS/assets/160244601/48154232-6142-4ab7-88ec-9677b84ce36b" height="80%" width="80%" alt="SIEM System steps"/>

# Decode (making unpack and spot difference)

**Download cmder - https://cmder.app/**

**Run `ls`**

**Open the folder were you saved malware file `cd malware`**

**Now you are in malware folder so run `ls`**

**Copy and paste filename or type ( `upx -d -o` newfilename filename  )**
- `-d` for making changes
- `-o` for output 

**After that file will be changed and they are same but you can spot the difference by the file size like**

- (Same file name)packed malware file = 12 kb
- (same file name)unpacked malware file = 54 kb



