hi this tool is experimental, use in your onw risk

you need 2 wallets
run your own node
need patience:
create a new wallet and send come junkcoins, use like your paying inscriptions wallet, in console use command:
dumpprivkey your wallet, use this data in example.wallet.json, rename to .wallet.json

now create a new wallet, to receive the inscriptions, you need choose file mint.js in folder SRC, open the file with a text editor, edit the line : const DESTINATION_ADDRESS = "yourwallet"; only add your wallet receiver here, , save.

check  your env. file this need to be the same like you junkcoin.conf.

now in your console use the command:  node src/mint.js

enjoy.
