   cd Desktop
      mkdir learn_git
      cd learn_git
      touch third.txt
      git init
      git add third.txt
      git commit -m "adding third text"
      git log
    touch fourth.txt
     git add fourth.txt
     git commit -m "adding fourth.txt"
     rm third.txt
     git add .
     git commit -m "removing third.txt"
     git log
     git config --global core.pager cat
     git config --global --list
     history > command_history.txt
