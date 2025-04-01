# Git - Working with Remotes

- I repository remoti sono versioni del tuo progetto che sono ospitate su internet
- La collaborazione con altri programmatori implice la gestione di questi repository remoti e il push e il pull di dati
  Fondamentale è saper **sincronizzare il nostro lavolo locale con un repository remoto.**

  *comandi principali:*
  
    `git remote -v` --> visualizza i server collegati al nostro repository
  
  ## Aggiungiere o rimuovere un repository remoto
  `git remote add <nome> <url>`
  
## Caricare il lavoro locale sul repository remoto
`git push add <remote> <remo-locale>`

## Aggiungere la copia locale del repository, allinenandola con la verione remota
`git pull <remote> <ramo-locale>`
