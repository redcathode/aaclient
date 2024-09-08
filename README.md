# aaclient
aaclient is a command-line tool to download anna's archive listings (currently, only via the torrent).  

## basic usage
```shell
aaclient https://annas-archive.org/md5/dd632c78acf44ca9ccbcc716a5727f68
```

## todos
- [x] progress bar
- [x] optionally add file extensions and descriptive filenames (note: should eventually be able to use the AA filename instead)
- [ ] autoremove .parts files
- [ ] allow adding to an existing torrent client via JSON-RPC
- [ ] downloading multiple torrents at a time w/ deduplication
- [ ] downloading via IPFS
