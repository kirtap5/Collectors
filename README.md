# Collectors
Digital version of the board game Collectors. (Group 5)


First project setup:

1. Run git clone https://github.com/kirtap5/collectors-skeleton.git in desired directory
2. Enter local folder, run cd Collectors -> cd collectors-skeleton-main
3. run: npm install
4. run: npm run serve

Starting new task:

1. From branch "main", create a new branch with command: checkout -b "branch_name"
2. När task klar:

  2.1 Merge main med task först:
    checkout main
    git pull
    checkout branch_name
    git merge main
    
  2.2 Merge task med main efter:
      Gå in på github och skapa pull request.
      Säkerställ att du väljer lokala "main" och inte fork origin.
