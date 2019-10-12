# AWSCLI
Several notes for starter trouble shooting
- File association not found for extension .py
  https://secretweaponsdigital.wordpress.com/2015/07/23/error-file-association-not-found-for-extension-py/

- To run cmd as Admin:
  Press Windows+R to open the “Run” box. Type “cmd” into the box and then press Ctrl+Shift+Enter to run the command as an administrator
- An error occurred (SignatureDoesNotMatch) when calling the CreateStack operation: Signature not yet current: 20191012T000244Z is still later than 20191012T000104Z (20191011T235604Z + 5 min.)
  Change local Machine Time to match with AWS Server time
 
 -If the stack is not shown in console
  Change regio to US West Oregon
  
 - Make sure the console is working on the current directory
