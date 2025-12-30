REQS

--Telescope

    sudo apt install rgrep
    sudo apt install fd-find

--Treesitter

    sudo apt intall gcc

BROKEN

-Blink.cmp signatures with function arguments

TODO


FIXES

-- Fixes issues where lua_ls needs 2.38 but others need a newer version
  
    sudo ln -s /usr/lib/x86_64-linux-gnu/libbfd-2.42-system.so /usr/lib/x86_64-linux-gnu/libbfd-2.38-system.so
