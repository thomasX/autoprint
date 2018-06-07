# autoprint
autoprint is a shell script for autoamtically printing email-attachments to a printer   

supported file types: pdf,jpg,png
supported printers: all postscript printers ... you can add multiple printer-types with cups

it does automatically print all attachments of the given e-mail addresses         


files: autoprint .... shell script
       autoprint.cfg ... config file

the config file has 1 configline per e-mail containing the following parameters:         
    param 1:  mail-server         
    param 2:  mail-address         
    param 3:  password         
    param 4:  printserver     
    param 5:  printqueue         
    param 6:  attachment types (.pdf.jpg.gif.png)         
    param 7:  copies                                      
    param 8:  keep mail on Server (Y/N)                  
    param 9:  folder  (optional parameter if folder is set only this mail-folder will be downloaded  
   
   
   
