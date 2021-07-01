# Git Full Setup and Connect to Github Account : 
**Here I provide the full instruction to install Git on linux and set it up with your github repo.**

**1) First to install all about git in linux :**


	**`$ sudo apt-get install git`**

	Now git is installed and no need to build it from Source !

**2) Then to connect git to your github account, 
you need a SSH key to introduce your device to your account :**


	To generate SSH key on your linux device , use this command : 

	**`$ ssh-keygen -t rsa -b 4096 -C "your_email_here"`**

	After running the above command press **Enter** to save the SSH key in its default path !

	Otherwise can set your own password to generate files there (just has 2 files)

	Now asks for password : Enter your password. ( If no need for password --- again press **Enter**)


	After this part you have 2 files created at the path you specified :(by default : /home/ali/.ssh )

	These 2 files have default names (defualt names : id_rsa, id_rsa.pub ) 



	The content of file at **`/home/ali/.ssh/id_rsa.pub`** is your public key needed, 
	
	needed to introduce your device to your account !
