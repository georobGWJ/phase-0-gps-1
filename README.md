# phase-0-gps-1

  516  mkdir phase0-gps-1-driver 
  
  517  mkdir phase0-gps-1-pair
        
        Commands 516 and 517 create empty repo directories to clone the project into from GitHub

  518  cd phase0-gps-1-driver/
  
  519  git clone https://github.com/georobGWJ/phase-0-gps-1.git
        
        Command 519 clones the project from GitHub into the driver directory
  
  520  ls
  
  521  cd phase-0-gps-1/
  
  522  ls
  
  523  ls -la
        
        Command 523 was done to check for a .git directory
  
  524  touch awesome_page.md
        
        Command 524 created an empty file to add to the project
  
  525  git add awesome_page.md
        
        Command 525 added the new file to the git Queue for committing later
  
  526  git status
        
        Command 526 confirms that the new file has been added
  
  527  git commit -m "Initial commit"
        
        Command 527 commits the new file with the message "Initial commit." locally
  
  528  push push origin master
  
  529  git push origin master
        
        Command 529 is uploading the updated master branch to the GitHub project location via push
  
  530  cd ..
  
  531  cd ..
  
  532  ls
  
  533  cd phase0-gps-1-pair/
  
  534  git clone https://github.com/georobGWJ/phase-0-gps-1.git
        
        Command 534 clones the project from GitHub into the pair directory
  
  535  ls
  
  536  cd phase-0-gps-1/
  
  537  ls
  
  538  ls -la
  
  539  cd ..
  
  540  cd ..
  
  541  ls
  
  542  cd phase0-gps-1-driver/
  
  543  ls
  
  544  cd phase-0-gps-1/
  
  545  git checkout -b add-command-log
        
        Command 545 creates a new branch to work in called ad-command-log
  
  546  git branch
        
        Command 546 was run to see what branches exist and to confirm I'm in add-command-log
  
  547  ls
  
  548  subl README.md
        
        Command 548 is opening the README.md file to annotate reasoning for the non-trivial commands

  
