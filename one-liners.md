## usefull oneliners for productivity

> ps aux | convert label:@- process.png

This commmand allows you to convert your shell output into an image as this makes it much easier than taking a screenshot of your shell if you want to share your output with someone.

Note:convert utility is part of imagemagick if you don't have convert you can install by installing imagemagick.

> curl ipinfo.io

If you want to know your external ip address using ipinfo.io you can simple run this command or you even add this command as your bash alias.

> git log --format='%aN' | sort -u

This comes in very handy especially if you are working on an open source project and wants to know who has contributed to the project.

> history | awk '{print $2}' | sort | uniq -c | sort -rn | head.

If you want to see which commands you run often you can run the following command and you can even add in your .bashrc as an alias.

> ls -d */

As someone who uses commandline everyday, this command is very useful when listing directories only and you can always set this command as a bash alias so you can access it quickily.

> du -hs */ | sort -hr | head

This command will allow you to view 10 largest directories in your current directory.

> ss -p

This command allows you to see what apps are consuming internet.

> grep . *

If you want to cat bunch of files at once you can run this command.

> rm -f !(test.txt).

This command will remove all the files from the directory but the not the one specified within brackets.

> python3 -m http.server

This command will allow you start an http server and serve your files. It comes in handy when you want share an html file over the network.

> mkfifo hello; script -f hello

This command will allow you to share your terminal session in real time. this was something I recently discovered and I was totally surprised by this command.
