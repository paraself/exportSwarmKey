# exportBeeKey

Currently it is a pain in the A** to export bee key in to metamask as they are not compatible.
This programe will export the private key so that people can import it in metamask or other wallets.


Usage: `beekey-mac64 /path/to/key/folder/ password`

Folder structure
```
-keyfolder
---swarm.key
```

It will create a file named `private.json` next to `swarm.key`

Assumption: currently it assumes that you use the same password for all the keys in the dir :-)

Disclaimer: 
- This will display the private key so please do it in a safe place.
- There is absolutely no gurantee that your key will work or your fund security. 

**Please use at your own risk**


