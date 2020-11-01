# Lecture 1:
## Introduction to the Linux cluster, basic BASH commands and git:


  - Pre-requisities:
  
    - Email <can.keles@rhul.ac.uk> for checking whether your access to the cluster is granted. You should be doing this well in advance because it might take IT team.
    - For Mac users use the terminal. Install git on your Mac. An easy installation guide is provided in the video: https://www.youtube.com/watch?v=PSULlxUk744
    
    - For Windows users install the full version of cmder as a terminal. Download and extract cmder from the link: https://github.com/cmderdev/cmder/releases/download/v1.3.16/cmder.zip. Inside the extracted folder double-click the cmder executable to launch the terminal. If you need any further help in the installation of cmder, please look at the official installation documentation https://github.com/cmderdev/cmder/blob/master/README.md#installation.
    
    - Github for Poets. Watch the following tutorial videos for familiarization with Git: (A lot of these will be covered in the lecture)
    
      -- Intro to Github
          https://www.youtube.com/watch?v=BCQHnlnPusY

      -- Branches
          https://www.youtube.com/watch?v=oPpnCh7InLY
      
      -- Forks and Pull Request
          https://www.youtube.com/watch?v=_NrSWLQsDL4

      -- Rename the Repository
          https://help.github.com/en/github/administering-a-repository/renaming-a-repository
    
    

  - Familiarization with the cluster architecture
  
    In this lecture you would get familiarized with the cluster architecture. (Schematic diagram is shared in https://github.com/RHULPsychology/Important_Tutorials/blob/master/README.md). You whould be able to relate to terms like a login node, a master node and worker nodes. This would be essential to understand how the parallelization would work.
    
  - Basic BASH commands:
  
    Learn basic Bash Scripting. Please follow tutorials and exercises provided at https://github.com/RHULPsychology/Important_Tutorials/blob/master/Bash/Important_Commands.md.
   
   
    - Essential_commands (Look at --help):
      
      Check current path (location):
      
      ```bash
      1. pwd
      ```
      Make a new folder(directory) at that path:
      
      ```bash
      2. mkdir (mkdir -p)
      ```
      Check the content of a folder(directory):
      
      ```bash
      3. ls (ls -ll)
      ```
      Change the directory (navigate):
      
      ```bash
      2. cd
      ```
      Print on the command prompt:

      ```bash
      5. echo
      ```
      File Editor (create new file and open):

      ```bash
      7. nano
      ```
      Reverse search of all previous commands:
      
      ```bash
      8. CRTL+R and CRTL+G
      ```
      Remove/delete files or folders:

      ```bash
      10. rm
      ```

    - Conditionals (What is Boolean?): 

      Tutorial link: 

      if-else:
      https://linuxize.com/post/bash-if-else-statement/

      Switch-case: 
      https://www.thegeekstuff.com/2010/07/bash-case-statement/

      ```bash

      1. if

      2. if - else

      3. if - elif - else

      ```

    - Loop: 

      Tutorial link: 

      for loop:
      https://www.cyberciti.biz/faq/bash-for-loop/

      while loop: 
      https://www.cyberciti.biz/faq/bash-while-loop/

      ```bash

      1. break

      2. continue

      ```

    - Exercises (to be done in the lecture): 

      -- Print your name for 5 times by writing a script.

      -- Create directory structure like /mnt/c/subfolder1/subfolder2/subfolder3. Create trial.txt file under subfolder3 and write your name for 5 times into that file by writing a script.
             

    - Git usage on the cluster
  
      You would use the following command to update git on the cluster. 

      ```bash
          source /usr/local/apps/psycapps/config/conda_bash_update
      ```

   You would be able to fork a repository from github or create a new repo in github, clone it on the cluster, make changes, git add, git commit and git pull and git push from the command line. It is very important for any further steps. Please refer to the tutorials mentioned in https://github.com/RHULPsychology/Important_Tutorials/blob/master/Git/Important_Links.md
