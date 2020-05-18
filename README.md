# .emacs.d 
My configuration of emacs editor



### ¿Cómo compartir la conf entre Remote Desktop y host?

- Directorio de conf de emacs del usuario es un link a directorio montado compartido por el RDP.
  - Windows RDP: 
    - Share LINUX_HOST folder with RDP and make link to repo
    - `C:\Users\\[User name]\AppData\Roaming\\.emacs.d => LINUX_HOST@~/src/fun/.emacs.d`
  - Linux Host: 
    - Link ${HOME}/.emacs.d to repo
    - `~/.emacs.d => src/fun/.emacs.d`





## Features deseadas

- [ ] Autoguardado
  - [ ] https://www.emacswiki.org/emacs/AutoSave#toc4
- [ ] Directory Tree navegable siempre en un buffer a la izquierda
- [ ] Vim keymappings
- [ ] Ansible editing mode
- [ ] Abrir terminal de git bash en un buffer (windows)