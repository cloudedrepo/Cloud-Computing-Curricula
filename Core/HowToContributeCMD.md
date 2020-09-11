# How to contribute from the command line

## Overview of the command line
For beginner users, we recommend using GitHub client or website (see bottom) for an easier start. If you are a terminal person, on the other hand, please complete the following steps:

- Create a personal fork of the repository by clicking on Fork button on GitHub. 
- Go to a folder where you will clone from your forked repository. 
- Type the following:
```
sudo git clone git://<GITHUBUSERNAME>/Cloud-Computing-Curricula.git
cd Cloud-Computing-Curricula
```
- make changes 
  - make a personal copy of `Module.md` template file and add it to the `Content` folder
  - rename it (using the `.md` extension) 
  - edit/update with your relevant content
  - save your changes
 - add your new file to the repository
       ```
       sudo git add .
       ```
 - commit changes to your FORKED repo
        ```
        sudo git commit
        ```
 - push your changes to the master copy on your FORKED repo
        ```
        sudo git push
        ```
        
[THIS PROBABLY IS NOT NEEDED]    - [you may get an error message if someone else has already committed changes to the master repository while you are working on your updates. the error message will state something like "following changes since commit..." on master repository at https://github.com/cloudcomputingcurricula/Cloud-Computing-Curricula.git. in that case, run the following command:]
        - sudo git pull https://github.com/cloudcomputingcurricula/Cloud-Computing-Curricula.git
    
    
    - create a pull-request on the master repository
        - sudo git request-pull master https://github.com/cloudcomputingcurricula/Cloud-Computing-Curricula.git
    

If you'd prefer contribute from the browser, see [these instructions.](https://github.com/cloudcomputingcurricula/Cloud-Computing-Curricula/blob/master/Core/HowToContributeBrowser.md)
