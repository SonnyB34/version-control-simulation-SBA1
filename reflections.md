# Reflections

## Steps to create and manage branches

  1. I created a folder called SBA. 
  2. Initialized a repository using git init. 
  3. Created a index.html file and added it to the staging area using $ git add index.html. 
  4. Commited the index.html file in order to create a main branch.
  5. Created another branch using $ git checkout -b feature/header and made sure i was in feature/header branch.
  6. I then added a header to the html file and stage and commited the changes.
  7. Switched back to the main branch using $ git checkout main.
  8. Then i created another branch called feature/footer using $ git checkout -b feature/footer.
  9. Added a footer element to the bottom of the index.html file and stage and commited the changes.
  10. Switch back to the feature/header branch and updated footer section which caused and issue when i merged all branched to the main branch.

 ## Handling merge conflict
 
  I manually removed the the code i didnt want in my html page to resolve the merge conflict. I then added the updated code to the staging are with $ git add . and then i committed the changes to the main branch and push my code to GitHub using $ git push origin main.

  ## How the pull request process helped

  The pull request process helped me ensure i had no errors in my code and how to fix it. It also helps because you can work on a separate branch without changing the main project.