Sample usage of libbitdht
=========================

How to compile:

 * Make sure libbitdht is built. Check ../README.md for details.
 * run `make` in /example/ folder.

This example feel use peers from bdboot.txt to bootstrap access to DHT
network. If it become stale, the easiest way I found myself to get new
list of peer to play with is to use NodeJS library `bittorrent-dht`
available at https://www.npmjs.org/package/bittorrent-dht . Simply
copy-paste example from README.md of this project and run it. It will
begin printing found peers into STDOUT. Replace with these content of
`bdboot.txt` making sure to replace `:` with ` ` (space).
