1. echo "#Personal Knowledge Repo" >> README.md
2. git init
3. git add .
4. git commit -m "first commit"
5. git branch -M main
6. git remote add origin git@github.com:AtharvaVaze/Personal-Knowledge-Repo.git
7. ssh-add ~/.ssh/id_ed25519_personal
8. git push -u origin main

To create SSH key like 'id_ed25519_personal':
1. On terminal, run ssh-keygen -t ed25519
2. The `ssh-keygen` utility will prompt you to enter the file in which to save the key. 
   Press Enter to accept the default location, which is typically `~/.ssh/id_rsa`, but rename recommended
3. You will be prompted to enter a passphrase. Enter a strong passphrase