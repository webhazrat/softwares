# releases

## tasklist command missing issue
1. Open Command Prompt as Administrator
2. Run the WMI repair commands
   net stop winmgmt /y
3. Rebuild the repository
  winmgmt /resetrepository
4. Start the WMI service again
  net start winmgmt
5. Restart your PC
