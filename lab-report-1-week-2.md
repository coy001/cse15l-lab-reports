# **Lab Report 1**

### **1.Installing VS Code**
 
 I.Go to [Page of VS Code](https://code.visualstudio.com) on your browser and install the appropriate version that fit your own operating system (MacOs,Windows,Linux), and this guide will use MacOs as example.
 
![image](https://user-images.githubusercontent.com/103301184/162617995-64676694-13a5-4c41-90d4-a33a5745d142.png)

II.Try to open the VS Code you just downloaded. If you successfully installed VS Code, you can see a page like below. If you do see a similar page, congradualations! You can go to next step.

![image](https://user-images.githubusercontent.com/103301184/162618002-38ee6f4f-e5fd-4b86-9528-0271069424db.png)

### **2.Remote Connecting**
I.Find your course specific account on [Educational Technology Services](https://sdacs.ucsd.edu/~icc/index.php) , you can see an address like cs15lsp22zz@ieng6.ucsd.edu, but zz will be replaced by another two letters consistent with your course special account.

II.Open teriminal, use ssh command to access your account:ssh cs15lsp22zz@ieng6.ucsd.edu (zz will be replaced)

III.If this is the first time you access, it might ask you a yes or no question. Type yes to continue.

IV.Enter your password.If you see the screen of terminal is like below, it works!

![image](https://user-images.githubusercontent.com/103301184/162618006-914d99e7-8c6f-4f0e-89de-27285c8cb13d.png)

### **3.Try Some Commands**
I. We have many commands and each has its own meaning, please try some to be familiar with them.

i. cd to change directory

ii. ls to list file

iii. exit to log out from the remote connect 

![image](https://user-images.githubusercontent.com/103301184/162618012-3883f22c-ba58-414a-803e-16033b41f5b3.png)

### **4.Moving File with scp**
I.Edit the program WhereAmI.java, and then store it on your own device.

![image](https://user-images.githubusercontent.com/103301184/162618024-d25e4246-33ae-4849-be6a-9737274ae310.png)

II.Run the code on your terminal to check the result. The result can be different with different operating system, don't worry if your result is different from mine.

![image](https://user-images.githubusercontent.com/103301184/162618039-5203c408-b503-491a-9185-0fcb13f83734.png)

III.Use scp command to move WhereAmI.java to your cs15lsp22zz@ieng6.ucsd.edu (zz will be replaced). When you see WhereAmI.java with ls command in your account, it works!

![image](https://user-images.githubusercontent.com/103301184/162618045-0538fd0a-f445-49f3-9f65-b51761431dee.png)

IV.Try to run the program on cs15lsp22zz@ieng6.ucsd.edu (zz will be replaced) to compare the result with the result on your own device.

![image](https://user-images.githubusercontent.com/103301184/162618051-3dc3c880-1775-4a3f-a536-abbae71b4da6.png)

### **5.Setting an SSH key**
I.Type ssh-keygen on terminal of your own computer, not the remote account!

II.Press the enter key several times until it show you a image

III.Use scp command to move the key into your account.

![image](https://user-images.githubusercontent.com/103301184/162618057-358f0c7e-3719-431a-b7fe-25668cf0cdf1.png)

IV.Use ssh command to log in your account ssh cs15lsp22zz@ieng6.ucsd.edu (zz will be replaced) If you don't need to enter password, it works! Congradualations!

![image](https://user-images.githubusercontent.com/103301184/162618070-f50109d3-2da4-4985-a473-ef0d238a506b.png)

### **6.Optimizing Remote running**
I.The Process already shows in part 4, just run WhereAmI.java both on your computer and on your account and see their difference. 

![image](https://user-images.githubusercontent.com/103301184/162618079-5ee480ba-b0fe-429a-bd8c-a9e6e5e838df.png)

### Thank You! 


