# A  Step to Step Guide to Install Anaconda in Ubuntu

In this repository, I am going to guide the following things 
* [How to download and install anaconda](#how-to-download-and-install-anaconda)
* [How to create conda environment and run your code](#how-to-create-conda-environment-and-run-your-code)

## How to download and install Anaconda

### Downlod Anaconda Installer

You can download the Anaconda installer either `Terminal` or `manually from the website`. Follow the following steps to download it manullay from [Anaconda Distribution Page](https://www.anaconda.com/products/individual). 

1. Go to the [Anaconda Distributionn Page](https://www.anaconda.com/products/individual#linux) and click `Download`.

2. After clicking you will redirect to the various `Anaconda Installer`. Download specific installer for your OS. 

3. `Anaconda3-2020.07-Linux-x86_64` will download.

### Install Anaconda

After downloading the installer(`Anaconda3-2020.07-Linux-x86_64`), please make sure where it is located. I put the installer in `Downloads` folder. To install, do following steps

1. Open your `Terminal` and go to the specific folder(in my case, the folder `Downloads`). Then use the following command

```sh
pratik@PRATIK-YOGA:~$ cd Downloads/    
pratik@PRATIK-YOGA:~/Downloads$ bash Anaconda3-2020.07-Linux-x86_64
```
 2. You will see the following output
 
 3. Click `ENTER` and finally it prompts `yes or no`. Hit enter. It will take a few minutes to install the anaconda.
 
 4. The installer prompts `Do you wish the installer to initialize Anaconda3 by running conda init?` Enter `“yes”`.
 
 5. To check if Anaconda install properly, close your terminal and then reopen it. Then type 
 ```sh
pratik@PRATIK-YOGA:~$ conda list    
```
It will show a list of packages install through Anaconda

## How to create conda environment and run your code
