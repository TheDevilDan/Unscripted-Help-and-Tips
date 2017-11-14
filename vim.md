# Command fast and usefull
  
On a VI document, "echap" and ":"  
  
    set number
    set syntax on  
  
# Disable vim automatic visual mode on mouse select
  
## Tested and work fine
  
    vi /usr/share/vim/vim80/defaults.vim  
  
and edit the line 70 for remove the "a" character :  
  
#### Original
  
    69 if has('mouse')  
    70   set mouse=a  
    71 endif  
  
#### New
  
    69 if has('mouse')  
    70   set mouse=a  
    71 endif  
  
## Non tested
  
    issue: :set mouse-=a  
    add to ~/.vimrc: set mouse-=a   
