
# Welcome! Currently this repository is available:

# getChromeExtensions 
  Get all of currently installed chrome extensions from all users and profiles.\
  In addition, it will extract all of the URLs and IPs which are inside the js/json/txt/html/md files of the extensions.\
  Available for MacOS, Linux and Win10!
  
 <b> --> On Win10 it will also verify the URLs against urlhaus db!</b>

  ## --> <a href="https://github.com/tomerhaimof/getChromeExtensions">Go to github repo!</a> <--

  <b>On MacOS/Linux, open terminal and run:
  </b>

   
    chmod u+x getChromeExtensions.py
    ./getChromeExtensions.py [checkExtensions]
   
    
  In order to get information from all users, it should run with "sudo":
  
   
    sudo ./getChromeExtensions.py [checkExtensions]
   
    
   <b>Please note that "requests" library is required</b>

 

   <b>On Win10, open powershell and run:</b>

    
    ./getChromeExtensions.ps1
    Get-ChromeExtensions [-checkURLs]
    
    
   In case you get an error regarding "Execution Policy", just run:

    
    powershell.exe -executionpolicy bypass -file FULLFILEPATHHERE
    
   For example:

    
    powershell.exe -executionpolicy bypass -file "c:\cyberiko\getChromeExtensions.ps1"
    
   In order to get information from all users, it should run with admin privileges (Run As Administrator) 
  
