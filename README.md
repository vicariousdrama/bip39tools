# bip39tools
Holding area for scripts and tools that leverage bip39


## 1password / BIP-39

- 1password-bip39.py - will accept a secret key for a 1password account,
and encode it as a set of BIP39 compatible seed words.  This is useful if
you want to backup your secret to metal plates for safe keeping and later
recovery.

Example: `python3 1password-bip39.py B4-JJ32K1-WP9XC5-R7NJ7-12LWQ-UIU3B-XRW52`


- bip39-1password.py - will accept a list of seed words and decode out a
secret key for a 1password account.

Example: `python3 bip39-1password.py embark crumble loan eternal boring abuse patrol mention manual snack icon bean own skull govern harsh master december antique still palm ride arm theme`
