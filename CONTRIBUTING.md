# Welcome to the How to contribute section 🤝

Flutter has given developers a super power to create innovative and creative UIs for Mobile and Desktop both 🦾😎. 

So why don't we create something awesome and contribute to Flutter community and also show the power or height of feasibility for creating beautiful things🤩 and if you want to contribute then you are at the right place☑!!

here, than you are on the right place, here are the steps that how you can contribute to this project!!

### 1. READ CODE OF CONDUCT
   Read the [Code of Conduct](https://github.com/clubgamma/code-of-conduct) before starting contributing.
### 2. Fork the repo
   First of all fork the repo to your own GitHub account by clicking the **Fork** button on top-right corner. Still could not find 🙄,check the below image
   ![fork](https://user-images.githubusercontent.com/58077762/93772626-ac77ef80-fc3c-11ea-8ee6-e381e1d68280.png)
   After a sucessful fork, you'll see a copy of this repo in your own account.

### 3. Clone the repo    
   Now it's time to copy this repo to own laptop/PC. 
   To clone the repo you can write the below command in **Git Bash**
    
   > git clone <REPO_LINK_FROM_YOUR_ACCOUNT>
    
   You can get the repo link from the Download section in the **repo copied in your own account**. Still having trouble🙄,see the below image
    
   ![clone](https://user-images.githubusercontent.com/58077762/93773696-fad9be00-fc3d-11ea-8981-5f6b31cefee1.png)
   
 ### 4. Set up remote repo
  - When you cloned your fork, that should have automatically set your fork as the "origin" remote. Use git remote -v to show your current remotes. You should see the URL of your fork (which you copied in step 3) next to the word "origin". 
      If you don't see an "origin" remote, you can add it using below git command
    
  > git remote add origin <REPO_LINK_FROM_YOUR_ACCOUNT>
      
  - Now you have to setup **upstream**. For that write the below git command
      
  > git remote add upstream https://github.com/clubgamma/Awesome-Flutter-Art
        
  - Now pull the latest changes from original repo to your local changes by firing thee below command
        
  > git pull upstream master
  
 ### 5. Inough BoilerPlates, It's Flutter time now!!
  - Open cloned Project in your favourite IDE. After that go to the lib->categories. In categories choose the folder in which you want to create riddle and in that perticular Category, create
    one folder named **(Categoryname + currentOrderNumber + @yourUserName)** . Boom, that's your playground, create your own riddle in it! Still not got it, don't worry, here is the example.
     
     ![FolderExample](https://user-images.githubusercontent.com/57007680/94572422-a0201200-028e-11eb-92e6-41bc2a6af9a0.PNG)

 - After Creating your riddle, you have to go **ListOfGames.dart** file and call the **ActionCard** class which is already created. Pass the required argument like Name, discreption, orderNumber
   etc. In OnPressed, give the className which you have created just now in your playground, I mean in your folder😉 Example below!
   
   ![FileExample](https://user-images.githubusercontent.com/57007680/94575402-d4490200-0291-11eb-93f7-c431427be883.png)
   
 ### 6. Now it's time to save the work
      
  - Stage the changes you have made by firing the below command
   > git add -A
  - Commit the changes 
   > git commit -m "Description of changes/your work"
  - Push the changes to your forked repo
   > git push origin master
  
### 7. Let's finish this
  
  - Go to your forked repo on GitHub website and refresh the page, you'll see something like the below image
  ![pr1](https://user-images.githubusercontent.com/58077762/93778051-172c2980-fc43-11ea-97bb-410e1689df4d.png)
        
  - Click on pull-request and you will be redirected to another page where you will see something like below image
  ![pr2](https://user-images.githubusercontent.com/58077762/93778056-185d5680-fc43-11ea-8477-a2b6773266e2.png)
        
  - After that you have to write your GitHub username as the title of your pull-request and describe your work if you want and that's it!!
    Create a pull-request by clicking the button
        
    Mark the pull request as **Ready for Review**
        
    Also add the below 2 lines in the description. It is compulsory for sucessful submission.
        
    - [X] I have read the Code Of Conduct.
        
    - [X] I have followed all the steps of submission properly.
        
    ![pr3](https://user-images.githubusercontent.com/58077762/93779010-1e076c00-fc44-11ea-86f0-7a6d74380624.png)

**Woohoo!! Congratulations on making your open source contribution🎉🎉**                                         
**Wait for some time to get your PR merged by our team**
