## Markdown baby

## to commit in the jaseci folder type:
```
git add .
git commit -m "This is my first commit"
git push 
```

## to select Jaseci folder
```
cd jaseci
```

## the full commit journet explained
``` 
git add .
git commit -m "description"
git push
done.
```

# Installing Jaseci
To get the best Jaseci experience, you should start by installing both Ubuntu 20 and Git.

Locate Ubuntu 20 in the Microsoft Store and install it. Once complete, open Ubuntu to access the command line.

Next, configure your Ubuntu by setting your desired username and password.

>### **TIP**
>You will not see your characters appear when typing the password. Carefully type your password twice to set it. You will be prompted if you type it incorrectly.

## Install Python 3.18
 
Ubuntu 20 typically comes with 3.18. However, confirm your python version with:
```
python --version
```
You must be running **3.18.10** or you'll experience errors.

If you need to reinstall Python 3.18, start by typing:
```
sudo apt install python3
```
Follow the prompts and agree to the installation. Press "y" to confirm the install.

## Install Git ##
You will need to install git to access the required code repo. From Ubuntu, type:
```
sudo apt install git
```
Follow the prompts and agree to the installation. Press "y" to confirm the install.

## Install Jaseci ##
It's time to install the Jaseci code base. Type:
``` 
sudo pip3 install jaseci
```
You will Jaseci start to install. Agree to any prompts. 

Next, let's ensure you are accessing the right git URL. Type:
``` 
git clone "URL"
```
Once complete, you are ready to code. Type:
``` 
cd jaseci
```
This will change your current directory to the location of Jaseci. To start coding, type:
``` 
code . 
```
Visual Studio Code will open. Authorize the app by givingf it the necessary permissions. Now it's time to code. 

