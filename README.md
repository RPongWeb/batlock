# batlock
How to lock your personal folders in windows 10 using bat files 
# Step 1 
Download lock.txt file and make changes it by modifying the following code. 

# Step 2 
Make a new folder if you don't have one already. If you do proceed by taking the text file and dragging it into the folder that you wish to lock. 

# Step 3 
Opoen the text file and scroll down to line 23 of the code or where it says "if NOT %pass%== PASSWORD_GOES_HERE goto FAIL". You will replace "PASSWORD_GOES_HERE" with the password you'd wish to set. (It can be numeric or alphabetical) 

# Step 4
Go to File -- > Save as ---> Save as type (ALL FILES) * It's very important that you save this file as a .bat file by using the bat extension instead of txt. 

[You can rename the file anything you'd like; just as long as it's ending in .bat instead of .txt!] 

So the finished file should be named e.g locker.bat and the type of file should be set to "ALL FILES". 
The default is text document because windows recognizes the .txt extension as a text file but you need to change it to accept "ALL FILES". 

# Step 5 
After you created your password and saved the file as a bat file , proceed by deleting the lock.txt file that you've downloaded and by now you should see a bat file created within the folder that your text file was in. 

# Step 6 
Doubel click the bat file in your folder and press any key to continue when the command prompt pops up. 

# Step 7
That will create a new empty folder. You can open the new folder but it will be empty. 

# Step 8 
Now we go back to the bat file and double click it. It will ask you if you'd like to lock the folder. Press "Y" for Yes and "N" for No.

# Step 9 
If you pressed Y and enter the empty folder that it created for you before will be gone because it has locked the folder for you. 
In order to see the contents within that folder , you'd need to unlock the folder by clicking the bat file and entering your password. 

# Step 10 
To lock your folder , follow the instructions on the command prompt. 

That is it! This works with all files and is a great way to store your private content. 

(Just be sure to remember your password) 
