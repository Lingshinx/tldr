# deluge

> A BitTorrent client.
> More information: <https://manned.org/deluge>.

- Download a torrent:

`deluge {{url|magnet|path/to/file}}`

- Download a torrent using a specific configuration file:

`deluge {{[-c|--config]}} {{path/to/configuration_file}} {{url|magnet|path/to/file}}`

- Download a torrent and launch the specified user interface:

`deluge -u {{gtk|web|console}} {{url|magnet|path/to/file}}`

- Download a torrent and output the log to a file:

`deluge {{[-l|--logfile]}} {{path/to/log_file}} {{url|magnet|path/to/file}}`
