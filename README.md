# Hello-World-Linux
This workshop will contain the stuffs include:
1. Connect to a server.
2. To konw who and where you are.
3. Look around.
4. Make folders and files.
5. Read/write a file.
6. Download and extract files.
7. Execute files.

### Before we begin:
To find this document, you can choose one of the following:
* link: https://github.com/WebbYang/Hello-World-Linux
* git clone (not necessary if you don't have git)

## Connect to a server
* ip: 140.112.2.71  
* port: 22  
* user: guest66  
* pass: NTUguest66  
For mac, find Terminal then `ssh guest66@140.112.2.71` (-p 22).  
For Windows, pick one of the following to download: PuTTY/Pietty/MobaXterm(https://twfunnews.com/mobaxterm/ Kevin's favoriate) 

## To know who and where you are
`whoami`: who you are.  
`pwd`: where you are. (print current directory)  
`passwd`: change password. (Don't change now). 
`echo`: print. Try `echo $0` and `echo $SHELL`.

## Look around
`ls`: list directory contents, `-alt` are commonly accompanied.  
`cd`: change directory, `~` to home directory, `..` to upper directory, `/` to root directory.  
`lscpu`: list cpu info.  
`df -h`: report file system disk sapce.  
`du -h`: space usage.  
`man`: helps to understand the command usage in detail.

## Make folders and files
`mkdir`: make a folder.  
**Please name a folder to keep your following operation inside.**    
`touch`: create a file.  
Try to `cd` to your folder and create a file. And `ls -l` it.  
Permission settings can be done by `chmod`.  
`mv`: move a file. If the path to move doesn't exist, it means to change the file name. 
`cp`: copy a file.  
`rm`: remove a file.
For folder operation, using `-r`.

## Read/write a file
There are many ways to read a file content. If it's small, you can `cat` it. If it's big, you can `head` or `less` it.  
You can use a friendly text editor to create/read/write a file.  
Try `nano` first. It's simple for beginners like myself since you don't need to memorize anything.  
However, experienced programmers tend to use `vi`. For a biginner, at least you need to know `:q` to quit.

## Download and extract files
There are some files we need to use for the following schedule.  
For Python courses, we choose Anaconda for Python 3.6 version. Go to https://www.anaconda.com to look around.  
`wget`: download data from given URL. Try to find the URL for Linux installer to download the script. (Should be https://repo.anaconda.com/archive/Anaconda3-5.2.0-Linux-x86_64.sh). 
If the file is big, ftp software like Filezilla may be a better choice.  
`tar`: to package/compress/decompress files. `-j`: through bzip2. `-c`: compress. `-x`: decompress. `-v`: show the processing filename. `-f`: filename for the output.    
For Blast, which will be used later in this course, check ftp://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/LATEST/. We'll use ncbi-blast-2.7.1+-x64-linux.tar.gz.  

## Execute files
We will run the the script simply by `./`.  
Sometimes we cannot execute the file due to permission, remember to check its mode setting. 

## To Move on
Now, we can check for what BLAST is.  
* To get the idea https://digitalworldbiology.com/tutorial/blast-for-beginners
* Hands-on https://github.com/enormandeau/ncbi_blast_tutorial

## More information
Please check the slides in the /home/guest/guest66/linux_workshop/old_slides.
