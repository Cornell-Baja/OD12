# OD12
There will be an altuim project in here eventually. The goal is to practice our skills using version control software and git to complete a very simple project.

Instructions on how to set up git and Altuim:

1. Initialize a git repository where you want the project to be
   
    touch README.md
    
    git init
    
    git add README.md
    
    git commit -m "first commit"
    
    git remote add origin XXXX@github.com:XXXXX/XXXXX.git
    
    git push -u origin master

2. Open up Altium
   Go to Preferences (It's an option under the top left corner (DXP))
    
    ->Data Management
      
        ->Design Repositories
3. Then click "connect to" SVN. A dialog should appear. The name is just a local reference so you can distinguish the server if you have multiple.
    
Method: https \n
    
Server: github.com
    
Server Port: Default

Repository Sub Folder: /xxxx/xxxxx

These instructions are adapted from:
 http://stackoverflow.com/a/20271900

