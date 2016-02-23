# chinhead
:eggplant: Scripts that simplify access and management of IST's sigma cluster

## What does these scripts do, exactly?
1. sigma is pretty straightforward, it just establishes an ssh session with sigma.ist.utl.pt
    `usage: sigma`
2. stsigma stands for *Send to Sigma* and it simplifies sending files to sigma's /web/ folder. 
    `usage: stsigma [filename] [option]` 
    1. When sending recursive files (folders) you must add the `-r` option. 
       Example: `stsigma folder1 -r`
    

## General Instructions
1. Download zip.
2. Extract zip into the directory you want.
3. Open the terminal in the directory you chose and run `export PATH=$PATH:~/chinhead-master`
    1. Note: `chinhead-master` is the default directory when you download the zip. You may change the directory name but when you run the command, you have to replace `chinhead-master` with your directory name.
4. Change the ist username in the scripts to yours. 
5. You're good to go!


    
