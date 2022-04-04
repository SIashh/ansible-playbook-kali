# Ansible 4 Kali
>  Manually configuring Kali? Ain't nobody got time for that.

These playbooks install most of the tools that I require with some tweaks for hardening, personalization, and making Kali quieter.

Steps:
1. Deploy a minimal Kali install. See https://github.com/iesplin/kali-minimal for an example
2. Clone this repo 
```bash
git clone https://github.com/iesplin/ansible-playbook-kali
```
3. Run the deploy script
```bash
cd ansible-playbook-kali
./deploy.sh
```
4. Add go repos
```bash
go install github.com/ropnop/kerbrute@latest
go install github.com/jaeles-project/gospider@latest
go install github.com/tomnomnom/assetfinder@latest
go install github.com/evilsocket/dnssearch@latest
go install github.com/gwen001/github-subdomains@latest
go install github.com/hakluke/hakrawler@latest
go install github.com/tomnomnom/httprobe@latest
go install github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest
go install github.com/haccer/subjack@latest
```

License
-------

MIT
