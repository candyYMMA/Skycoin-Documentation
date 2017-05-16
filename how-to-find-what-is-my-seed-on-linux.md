# How to find what is my wallet seed on linux.

Open terminal.

Go to our home director.

There you should a see the  Skycoin folder - called ".skycoin"

Go inside ".skycoin" folder.

_~$ ll .skycoin/_

now go to .wallets

_~/.skycoin$ cd wallets_

Now we can just search our seed in the \*wlt file, like that:

_~/.skycoin/wallets$ grep "seed" \*wlt_

copy the value between the bracelets.

Now you can paste wherever needed.

