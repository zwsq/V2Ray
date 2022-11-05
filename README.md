# ZWSQ V2Ray ToolKit
### Introduction 
V2Ray is responsible for network protocols and communications. It can work alone, as well as combine with other tools. It is widely used in countries like China, Iran, Cuba and Russia to circumvent Internet censorship.

### Features

- Multiple inbound/outbound proxies: one V2Ray instance supports in parallel multiple inbound and outbound protocols. Each protocol works independently.
- Customizable routing: incoming traffic can be sent to different outbounds based on routing configuration. It is easy to route traffic by target region or domain.
- Multiple protocols: V2Ray supports multiple protocols, including Socks, HTTP, Shadowsocks, VMess etc. Each protocol may have its own transport, such as TCP, mKCP, WebSocket etc.
- Obfuscation: V2Ray has built in obfuscation to hide traffic in TLS, and can run in parallel with web servers.
- Reverse proxy: General support of reverse proxy. Can be used to build tunnels to localhost.
- Multiple platforms: V2Ray runs natively on Windows, Mac OS, Linux, etc. There is also third party support on mobile.

## Installation

### On Server

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.
It's easy to install v2ray on server. All you need is just a Linux server or VPS and a domain that points to the server address.

> Notes:
> `V2Ray Server` works on CentOS, Ubuntu and Fedora.
> The domain it is optional but recommended.


Install V2Ray server using following command.

```sh
bash <(curl -L -s https://raw.githubusercontent.com/zwsq/V2Ray/main/install.sh) | tee v2ray_ins.log
```
Select Option 1 to install V2Ray on your server and continue the installation. The script is written by [Vulabing](https://github.com/wulabing) but it language is Chinese. I tried to translate some parts of it to English for better understanding.
## License

MIT

**Free Software, Hell Yeah!**