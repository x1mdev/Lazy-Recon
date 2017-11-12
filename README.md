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

- Sublist3r (https://github.com/aboul3la/Sublist3r).
- webscreenshot (https://github.com/maaaaz/webscreenshot)

Take note: webscreenshot requires PhantomJS (https://github.com/maaaaz/webscreenshot/wiki/Phantomjs-installation)

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

The script will create two files: domainsfile.txt & resolveddomains.txt

After this it will run webscreenshot on the resolveddomains.txt file. Just sit back and relax

## ToDo

- Add more recon tools
- fix alias: now requires ```bash lazy domain.tld``` but should be: ```lazy domain.tld```


## Thanks

Thanks @EdOverflow for your helpful blog and inspiration to start working on a lazy shell script ;)
