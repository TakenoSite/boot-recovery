# How to boot-recovery

## grub command

1:  grub rescue > ls 
    
    (hd0) (hd1) (hd2)
    
2: grub rescue > ls (ud0)/boot/grub/x86_64-efi/normal.mod
    
    error : unknown filesystem 
    
3: grub rescue > set prefix=(hd0)/boot/grub

4: grub rescue > insmod (hd0)/boot/grub/x86_64-efi/normal.mod

5: grub rescue > normal

## grub isntall 

1: # grub-install /

2: # update-grubs


  
  
