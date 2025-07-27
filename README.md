
<p align="center">
<img src="https://github.com/user-attachments/assets/8ec3d5a3-5348-49d9-8862-9e8430a685e5", width="500", height="500">
</p>

<h1 align="center">DEDSEC_GSTRIKE</h1> <h4 align="center">Spear Phishing Toolkit Designed to Simulate Real-Life Attacks</h4>

## DESCRIPTION

GSTRIKE is a powerful Google-based spear phishing toolkit created to simulate realistic social engineering attacks. It’s designed for red teaming, awareness training, and ethical phishing simulations. The toolkit includes automated email template generation, and port forwarding for live payload interaction.

GSTRIKE makes it easier to craft convincing phishing emails that look and feel legitimate by mimicking Google's native email styles and integrating user-supplied data dynamically.

## FEATURES
   * Automated Email Template Generator: Generate Google-style emails with custom content, links, and spoofed addresses.
     
   * Realistic Email Templates: Includes multiple prebuilt templates resembling real Google security alerts — designed to trigger user interaction by mimicking security warnings, login alerts, or unusual activity messages.
     
   * 2FA OTP Capture: Includes support for harvesting one-time passcodes (OTP). When the victim enters a 2FA code into the spoofed login form, the tool can capture and display it in real time.
     
   * Port Forwarding Support: Integration with services like ngrok for exposing local phishing pages or payloads over the internet for testing or engagement.
     
   * EML File Support: Allows importing and modifying .eml message files. Useful for cloning and customizing authentic email layouts.
     
   * Built-in Email Sender: Send phishing emails directly from the tool using your own SMTP credentials. Just enter your email address and app-specific password to start sending.



### HOW TO GET YOUR GMAIL KEY
   1. goto this link: https://myaccount.google.com/u/0/apppasswords

<p align="center">
<img src="https://i.stack.imgur.com/Xe8Jt.gif", width="800", height="800">
</p>
   2. Then copy your email and app password, and provide them to the tool.

### SCREENSHOT 
<p align="center">
<img src="https://github.com/user-attachments/assets/896e6463-4875-46da-a7b3-25a095805cc2", width="500", height="500">
<img src="https://github.com/user-attachments/assets/c0674ef8-6f03-47b8-a309-efd6fcaa47d5" width="500", height="500">
<img src="https://github.com/user-attachments/assets/a9aa1b69-8097-466e-86d4-4f4c0a3d13f4" width="500", height="500">
<img src="https://github.com/user-attachments/assets/0a0596d5-a68c-483a-abaa-5a788b6aeca0" width="500", height="500">
<img src="https://github.com/user-attachments/assets/cfc99a12-8353-4abe-9ac8-ea5c1fe9a4ed" width="500", height="500">
<img src="https://github.com/user-attachments/assets/e652f625-6ca6-42ae-93a9-6be653ddeb6a" width="500", height="500">
<img src="https://github.com/user-attachments/assets/c2c803c3-1c3c-4f4e-828f-40342a72eb95" width="500", height="500">
<img src="https://github.com/user-attachments/assets/e0a6b599-cdc3-4f3a-8e19-61a90cc953f6" width="500", height="500">
</p>

### INSTALLATION

    git clone https://github.com/0xbitx/DEDSEC_GSTRIKE.git
    pip3 install requests qrcode[pil] tabulate tqdm beautifulsoup4
    cd DEDSEC_GSTRIKE
    chmod +x dedsec-gstrike
    ./dedsec-gstrike
    
    or
    
    sudo apt install ./dedsec-gstrike.deb
    dedsec-gstrike
  
### TESTED ON FOLLOWING
* Kali Linux 
* Parrot OS 
* Ubuntu
  
## Legal Disclaimer

This tool is intended for educational and security research purposes only. Unauthorized usage may be illegal in your jurisdiction. The author is not responsible for any misuse of this tool.

