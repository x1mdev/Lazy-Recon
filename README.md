# Lazy-Recon

Bash script to help make recon for bug bounty programs a bit easier.

This is still a work in progress, more functionality will be added soon.

Martijn (X1M) - martijn@x1m.nl

## Installation
### Download

```bash
  git clone https://github.com/x1mdev/Lazy-Recon.git
```

### Requirements

For now the script depends on Sublist3r (https://github.com/aboul3la/Sublist3r).

If you do not have it already, download it to be able to use Lazy Recon.

### Installation

Just to make it a bit more lazy:

```bash
  alias lazy='path/to/Lazy-Recon/lazy '
```


## Usage

To keep your work organized I suggest creating a new folder for the program you want to start on.

```bash
  mkdir [ProgramName]
```

```bash
cd [ProgramName]
``` 

```bash
  bash lazy domain.tld
```

The script will create to files: domainsfile.txt & resolveddomains.txt

## ToDo

- Add more recon tools
- fix alias: now requires ```bash lazy domain.tld``` but should be: ```lazy domain.tld```


## Thanks

Thanks @EdOverflow for your helpful blog and inspiration to start working on a lazy shell script ;)
