# bna-create
Creates a .bna file from single ".cto .json .acl .js (.md)" files for Hyperledger Composer

To install the script, make it executable with `chmod +x` and move it into ~/bin

To use it, open a Terminal (bash), go into the folder with your .cto .json .acl .js (optional: .md) files for the Hyperledger Composer Blockchain. If you just start the script, the .bna will be named composer.bna. If you add a name after the command, the .bna will have this name. e.g. `bna-create fooname` --> fooname.bna

This script is only for 1 file each, because of simplicity. It creates a bna file with the correct folder structure. After that, you can upload it to your Hyperledger Blockchain.
Why? Because the "composer archive create" never works :p
