# commands
- Check all file types at once: Run "  file ./*  "
- 1033: The numeric value representing the size you are looking for. " find -size 1033c "
- "./-file2: This is a file where the literal name starts with a dash (-). Because the cat command usually thinks a      dash indicates an option (like -v), you correctly used ./ to tell the system "look for a file named -file2 in       this folder."
   .file2: This is a hidden file (dotfile). In Linux, any file starting with a . is hidden from a standard ls           command."
