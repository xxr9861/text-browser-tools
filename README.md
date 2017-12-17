# text-browser-tools
browsers have the ability to pass uri to external programs. let us hack the same.

# gitclone


- requirements: lynx and dialog
-
- This entry is needed in lynx.cfg
- EXTERNAL:http:gitclone %s
-
- location of lynx.cfg usually at
- $HOME/.lynx/lynx.cfg
- /etc/lynx/lynx.cfg
-
- copy gitclone to $HOME/bin/
- and 
- chmod +x gitclone
- 
- create a directory
- $HOME/githubrepo/ 
- this is where all the repositories will be cloned

while you are in github repository page
press comma (,) to activate this script
it would display an input field 
and prompt you to enter an intelligible directory name to clone the repository in

you would find your cloned repositories in
$HOME/githubrepo/intelligible_name_you_input/repository_name/


 _______________________
< I know this is silly. >
 -----------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||



