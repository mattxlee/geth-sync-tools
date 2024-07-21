# Geth-sync-tools

Use this script to add nodes from `nodes.txt` for those who cannot find health nodes when you are starting a new fresh ethereum node.

You can find the nodes from [https://www.ethernodes.org](https://www.ethernodes.org), paste the nodes from the website and run `add_peers.sh`, the rpc port in the script is 3334, change it according your geth setup.

`parser.go` I didn't use it, it seems it will generate `nodes.txt` by reading data from [https://www.ethernodes.org](https://www.ethernodes.org).