# Recon Tools Auto Installer 🛠️

This bash script automates the setup of a comprehensive bug bounty and red teaming toolkit on Debian/Ubuntu-based systems. It installs and configures a wide range of reconnaissance, enumeration, and vulnerability scanning tools using `apt`, `go`, `pip3`, and GitHub repositories.

---

## 📦 Features

- Automatic system update and package upgrade
- Installs essential tools: `git`, `wget`, `unzip`, `zip`, etc.
- Installs Golang and configures Go-based tools
- Installs Python3 and pip-based tools
- Downloads and configures tools from GitHub
- Moves all binaries to `/usr/local/bin` for global use
- Creates a `~/tools` directory for organizing cloned repos

---

## 🧰 Tools Installed

### Go-based Tools:
- [naabu](https://github.com/projectdiscovery/naabu)
- [unew](https://github.com/rix4uni/unew)
- [httprobe](https://github.com/tomnomnom/httprobe)
- [xsschecker](https://github.com/rix4uni/xsschecker)
- [qsreplace](https://github.com/tomnomnom/qsreplace)
- [dalfox](https://github.com/hahwul/dalfox)
- [Gxss](https://github.com/KathanP19/Gxss)
- [katana](https://github.com/projectdiscovery/katana)
- [waybackurls](https://github.com/tomnomnom/waybackurls)
- [bxss](https://github.com/ethicalhackingplayground/bxss)
- [freq](https://github.com/takshal/freq)
- [hakrawler](https://github.com/hakluke/hakrawler)
- [gauplus](https://github.com/bp0lr/gauplus)
- [assetfinder](https://github.com/tomnomnom/assetfinder)
- [gf](https://github.com/tomnomnom/gf)
- [httpx](https://github.com/projectdiscovery/httpx)
- [urlprobe](https://github.com/1ndianl33t/urlprobe)
- [go-dork](https://github.com/dwisiswant0/go-dork)

### Apt-based Tools:
- `httpx-toolkit`
- `cargo`
- `subfinder`
- `amass`
- `naabu`
- `masscan`
- `feroxbuster`
- `gobuster`
- `getallurls`

### Other Tools:
- [urldedupe](https://github.com/ameenmaali/urldedupe)
- [xlsninja](https://github.com/nischalbijukchhe/lostools)
- [loxs](https://github.com/coffinxp/loxs)
- [Gf-Patterns](https://github.com/1ndianl33t/Gf-Patterns)
- [findomain](https://github.com/findomain/findomain)
- [aquatone](https://github.com/michenriksen/aquatone)
- [rustscan](https://github.com/RustScan/RustScan)
- [duplicut](https://github.com/nil0x42/duplicut)
- [SecretFinder](https://github.com/m4ll0k/SecretFinder)

---

## 🚀 Usage

```bash
chmod +x webtools.sh
sudo ./webtools.sh
