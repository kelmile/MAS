# Microsoft Activation Script (MAS)

Method 1:

1. Windows 8, 10, 11

  irm https://get.deadtrain.dev | iex


2. Windows 7 or Later:

  iex ((New-Object Net.WebClient).DownloadString('https://get.deadtrain.dev'))


3. If the domain is blocked by ISP or DNS, try this (needs updated Windows 10 or 11):

  iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.deadtrain.dev | Out-String)


Method 2:
  
  1. Download the script: MAS_AIO.cmd (https://temp-git.deadtrain.dev/latest/MAS_AIO.cmd) or the full ZIP.
  2. Run the file named MAS_AIO.cmd.
  3. You will see the activation options. Follow the on-screen instructions.
  4. That's all.

