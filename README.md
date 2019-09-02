# automod
Smple script to cat multiple automod files together for easier management of long lists of rules.

### running
on unix: run cat.sh
on windows: run cat.bat
your output is in the file output, copy paste that to your subs automod config page.

### adding/removing files
make a new file in the same folder
add the file name to the list in line 2 of both both cat.sh and cat.bat along woth another brk
eg: cat approved **brk newFile** brk spam brk trolls

for removing, you just need to remove from the cat command, the file itself can stay. or you can just deñete the xontents and leave it in the comand.
