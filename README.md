
## Installing whois
This plugin uses the "whois" command. It is usually installed by default, but if not, you can get it via your favourite package manager.

Debian/Ubuntu:
```sh
apt-get install whois
```
RHEL/CentOS:
```sh
yum install whois
```

## Usage
```sh
bash ./my_check_domain.sh -d domain.com
OR bash ./my_check_domain.sh -d domain.com >> ./log/domain.log
```
