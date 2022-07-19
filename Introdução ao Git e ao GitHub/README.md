### Link p/ o Repositório criado para o curso "Introdução ao Git e ao GitHub": https://github.com/Taresu/livro-receitas



### :key: SSH Key configuration:

• Type ssh-keygen -t ed25519 -C email@domínio.com
• Type cd /c/users/User/.ssh/
• Type cat ed25519.pub     (public key)
• Copy and paste this public key in SSH and GPG keys GitHub Page (https://github.com/settings/keys)
• Type eval $(ssh-agent -s)
• Type ssh-add id_ed25519     (private key)

### :computer: Commands:

- git init

- git add "file" OR *   (for all files)

- git commit -m "message"

- git status

- git push     (empurra - falso cognato)

- git pull     (puxa) 

- git clone "link"     (GitHub Repository - SSH or HTTPS)

  #### :gear: Config:

  - git config --list
  - git config --global "property" "value"

  - git config --global --unset "property"

    **OBS:** Press 'q' to exit!

  #### :space_invader: Conflicts:

  - git remote add origin "link"     (GitHub Repository - SSH or HTTPS)
  - git branch -M main
  - git push -u origin main

