# My Linux Cheat Sheet 🐧

Hi, I'm Alina! This is my personal, human-written guide for Linux. No complicated definitions here—just straight-to-the-point explanations, clean syntax, and everyday examples.

---

##  location commands

### 1. pwd  (print working directory)
* **In Simple Words:** "Where am I right now?" It prints your current location.
* **Syntax:** `pwd`
* **Real Example:** 
  ```bash
  pwd
  # Result: /home/alina/Documents
  ```

### 2. ls  (list)
* **In Simple Words:** "Show me what's inside this folder." (Like opening a folder on Windows).
* **Syntax:** `ls`

### 3. ls -l
* **In Simple Words:** "Show me details." Gives a long list with file sizes and permissions.
* **Syntax:** `ls -l`

### 4. ls -a
* **In Simple Words:** "Show me EVERYTHING, even the hidden files." (Files starting with a dot `.`).
* **Syntax:** `ls -a`

### 5. cd  (change directory)
* **In Simple Words:** "Go to this folder." (Change Directory).
* **Syntax:** `cd [folder_name]`
* **Real Example:** `cd Desktop`

### 6. cd ..
* **In Simple Words:** "Go back." Takes you one step backward to the previous folder.
* **Syntax:** `cd ..`

### 7. cd ~
* **In Simple Words:** "Take me home!" Instantly jumps back to your main user folder.
* **Syntax:** `cd ~`

---

## 📁 Managing Files & Folders 

### 8. mkdir  (make directory)
* **In Simple Words:** "Create a new folder.".
* **Syntax:** `mkdir [folder_name]`
* **Real Example:** `mkdir Cybersecurity`

### 9. touch
* **In Simple Words:** "Create a blank file." 
* **Syntax:** `touch [file_name]`
* **Real Example:** `touch notes.txt`

### 10. cat
* **In Simple Words:** "Show me what is written inside this file." Prints text on the screen.
* **Syntax:** `cat [file_name]`
* **Real Example:** `cat notes.txt`

### 11. cp  (copy)
* **In Simple Words:** Copy a file from source to destination.
* **Syntax:** `cp [file] [new_location]`
* **Real Example:** `cp notes.txt /home/alina/Desktop`

### 12. cp -r
* **In Simple Words:** Copy an entire folder along with everything inside it.
* **Syntax:** `cp -r [folder] [new_location]`
* **Real Example:** `cp -r Cybersecurity /home/alina/Backup`

### 13. mv (move)
* **In Simple Words:** Move a file to another folder, OR rename a file.
* **Syntax:** `mv [old_name] [new_name]`
* **Real Example:** `mv notes.txt hacking_notes.txt`

### 14. rm  (remove)
* **In Simple Words:** Delete a file permanently.
* **Syntax:** `rm [file_name]`
* **Real Example:** `rm useless.txt`

### 15. rm -rf
* **In Simple Words:** "Force delete a folder!" It deletes an entire folder without warning. Use carefully!
* **Syntax:** `rm -rf [folder_name]`
* **Real Example:** `rm -rf old_junk_folder`

---

## 🔑 Permissions & Admin Power (Power aur Haqooq)

### 16. chmod
* **In Simple Words:** Change file permissions (Who can read, write, or run a file).
* **Syntax:** `chmod [permission] [file]`
* **Real Example:** `chmod +x script.sh` *(Gives permission to run the script)*

### 17. sudo  (super user do)
* **In Simple Words:** "Run as Administrator." Gives root/boss privileges to a command.
* **Syntax:** `sudo [command]`
* **Real Example:** `sudo apt update`

---

##  Terminal Helpers

### 18. clear
* **In Simple Words:** "Clean the screen." If your terminal screen is full of messy text, this wipes it clean so you can start fresh.
* **Syntax:** `clear`

### 19. Tab (Keyboard Key)
* **In Simple Words:** "Auto-complete my typing!" Type the first few letters of a command or folder name, then press the Tab key on your keyboard. Linux will automatically fill in the rest of the name for you. It saves a lot of time!
* **How to use:** Just hit the `Tab` key while typing.
