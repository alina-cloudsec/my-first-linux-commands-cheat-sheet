# Permissions commands

##What I Did

I made a small script file called `script.sh`. I checked its
permissions using `ls -l`. It did not have permission to run yet.

I used `chmod +x` to give it permission to run. I checked `ls -l`
again, and the permission letters changed. 

When I first ran `./script.sh`, it gave an error because the file only had plain text. I fixed this by using `echo` to put a proper `echo` command inside the script. 

After fixing some typos with spaces and filenames, I ran the script again using `./script.sh` to prove the permission really worked and it successfully printed the message.
