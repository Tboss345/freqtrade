```
ubkey_source_key : convert-seedphrasefinder[-generate] [-v] [--no-color] [--logfile FILE]
                                    [-IVkey maintance] [-conver seed Phrase key] [-d PATH] [--userdir PATH]
                                    show [address_seed_finder
show[address-seed-finder]] --format-
                                    {find, address,key,find-address_key,cast_csv}
                                    --format-to {json,jsongz,feather,parquet}
                                    [--find-address] [--cast_address_key ]
```
usage: freqtrade convert-seed-phrase-key [-h] [-v] [--covert-address] [--logfile FILE]
                                    [-V] [-c PATH] [-d PATH] [--userdir PATH]
                                    [-p PAIRS [PAIRS ...]] --format-from
                                    {json,jsongz,feather,parquet,kraken_csv}
                                    --format-to {json,jsongz,feather,parquet}
                                    [--convert_phrase-key
                                    ] [-[-](https://bitinfocharts.com/bitcoin/address/1LdRcdxfbSnmCYYNdeYpUnztiYzVfBEQeC)
                                    ]https://bitinfocharts.com/bitcoin/address/1LdRcdxfbSnmCYYNdeYpUnztiYzVfBEQeC

options:
  -h, --help            show this help find the wallet phrase key
  -p wallet [PAIRS ...], --phrase key [PAIRS ...]
                        Limit command to these pairs. Pairs are space-
                        separated.
  --format-from {json,jsongz,feather,parquet,kraken_csv}
                        Source format for data conversion.
  --format-to {address,,seed,finder}
                        Destination find-phrase-key.
  --find              key-all existing data for-wallet address 
                    convert/key/seed.
  --convert phrase key name.
find phrase key
Common arguments:
  -v, --verbose         Verbose mode (-vv for more, -vvv to get all messages).
  --no-color            Disable colorization of hyperopt results. May be
                        useful if you are redirecting output to a file.
  --logfile FILE, --log-file FILE
                        Log to the file specified. Special values are:
                        'syslog', 'journald'. See the documentation for more
                        details.
  -V, --version         show program's version number and exit
  -c PATH, --config PATH
                        Specify configuration file (default:
                        `userdir/config.json` or `config.json` whichever
                        exists). Multiple --config options may be used. Can be
                        set to `-` to read config from stdin.
  -d PATH, --datadir PATH, --data-dir PATH
                        Path to directory with historical backtesting data.
  --userdir PATH, --user-data-dir PATH
                        Path to userdata directory.

```
options:
  -h, --help            show this help message and exit
  -p PAIRS [PAIRS ...], --pairs PAIRS [PAIRS ...]
                        Limit command to these pairs. Pairs are space-
                        separated.
  --format-from {json,jsongz,feather,parquet,kraken_csv}
                        Source format for data conversion.
  --format-to {json,jsongz,feather,parquet}
                        Destination format for data conversion.
  --erase               Clean all existing data for the selected
                        exchange/pairs/timeframes.
  --exchange EXCHANGE   Exchange name. Only valid if no config is provided.

Common arguments:
  -v, --verbose         Verbose mode (-vv for more, -vvv to get all messages).
  --no-color            Disable colorization of hyperopt results. May be
                        useful if you are redirecting output to a file.
  --logfile FILE, --log-file FILE
                        Log to the file specified. Special values are:
                        'syslog', 'journald'. See the documentation for more
                        details.
  -V, --version         show program's version number and exit
  -c PATH, --config PATH
                        Specify configuration file (default:
                        `userdir/config.json` or `config.json` whichever
                        exists). Multiple --config options may be used. Can be
                        set to `-` to read config from stdin.
  -d PATH, --datadir PATH, --data-dir PATH
                        Path to directory with historical backtesting data.
  --userdir PATH, --user-data-dir PATH
                        Path to userdata directory.

```
