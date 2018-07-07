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
* git clone (not necessary)

## Connect to a server
ip: 140.112.2.71  
port: 22  
user: guest66  
pass: NTUguest66  
* For mac, find Terminal then `ssh -p 22 guest66@140.112.2.71` 
* For Windows, PuTTY/Pietty/MobaXterm 

## To know who and where you are
`whoami`: who you are  
`pwd`: where you are (print current directory)  
`passwd`: change password (Don't change now)

## Look around
`ls`: list directory contents, `-alt` are commonly accompanied.  
`cd`: change directory, `~` to home directory, `..` to upper directory, `/` to root directory.  
`lscpu`: list cpu info.  
`df -h`: report file system disk sapce.  
`du -h`: space usage.  
`man`: helps to understand the command usage in detail.

## Make folders and files
`mkdir`: make a folder.  
Please name a folder to keep your following operation inside.  
`touch`: create a file.  
Try to `cd` to your folder and create a file. And `ls -l` it.  
Permission settings can be done by `chmod`.  

## Read/write a file
There are many ways to read a file content. If it's small, you can `cat` it. If it's big, you can `head` or `less` it.  
You can use a friendly text editor to create/read/write a file.  
Try `nano` first. It's simple for beginners like myself since you don't need to memorize anything.  
However, experienced programmers tend to use `vi`. For a biginner, at least you need to know `:q` to quit.

## Download and extract files
There are some files we need to use for the following schedule.  
For Python course, we choose Anaconda for Python 3.6 version.
`wget`
For Blast, we choose ncbi-blast-2.7.1. 

## To Move on
Now, we can check for what BLAST is.  
* To get the idea https://digitalworldbiology.com/tutorial/blast-for-beginners
* Hands-on https://github.com/enormandeau/ncbi_blast_tutorial
