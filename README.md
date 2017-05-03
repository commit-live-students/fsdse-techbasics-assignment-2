# Tech Basics - Assignment 2 

### Download Anaconda and Make It Executable
* The best way to install Anaconda is to download the latest Anaconda installer bash script and then run it.
* Find the latest version of Anaconda for Python 2.7 at the [Anaconda Downloads Page](https://www.continuum.io/downloads))
* Next, change to the /tmp directory. This is a good directory to download ephemeral items, like the Anaconda bash script, which we won't need after running it.
```
cd /tmp
```
* Use curl to download the link that you copied from the Anaconda website
```
curl -O https://repo.continuum.io/archive/Anaconda2-4.3.1-Linux-x86_64.sh
```
* Now let make Anaconda file executable by using `chmod` command
```
chmod +x Anaconda2-4.3.1-Linux-x86_64.sh
```

Note :: How to install and run Anaconda is covered in next assignment.
