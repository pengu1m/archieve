# Archieve

A box for archieved projects

## How to archieve

1. Download a project with `git clone` at `repos` folder
2. Zip target folder with `tar -zcvf` at `repos` folder
3. Remove previous folder

```bash
#!/bin/bash

git clone $2 repos/$1
tar -zcvf repos/$1.tar.gz repos/$1
rm -rf repos/$1
```

```bash
# Use archieve command with 'ar'
alias ar=". ./archieve"
```

## License

All licenses of projects in this repository follows **GPL 3.0**.
Even they dont follow GPL 3.0 in their own LICENSE.
