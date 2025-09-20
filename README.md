# Notice
- Some of data files in zip are still encrypted or incomplete, please do not use zip for now. I'm trying to troubleshoot the problem.
- This is a temporary solution:  
  1. Download the .msixvc file and install it by this command (run in Powershell):   
      ```
      Add-AppxPackage -Volume <DISK_LABEL> -Path <MSIXVC_FILE_PATH>
      ```  
  2. When installed done, you should firstly run the game to decrypt some files. This step need a license of this game in your Microsoft account.  
  3. Then use the decrypted exe file in this repository replacing your local installed one so that you can run the game without installed.

# Disclaimer
- The content provided here is for **educational and informational purposes** only. Use at your own risk.
- I will not provide any support about unlocking full game features or any other related issues.

# Usage
You can access all version's packages in repository [tags](https://github.com/bubbles-wow/mcbe-gdk-unpack-archive/tags). The preview version is set as the `Pre-release` tag.  
