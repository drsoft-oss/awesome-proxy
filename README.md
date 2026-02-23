<p align="center">
  <a href="https://www.anonymous-proxies.net?utm_source=github&utm_medium=banner&utm_campaign=awesome-proxy" target="_blank" rel="noopener noreferrer">
    <img src="banner.svg" alt="proxybench banner" width="768" />
  </a>
</p>

# Awesome Proxies [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> The most comprehensive, curated list of **proxy tools, libraries, servers, VPNs, and resources** for developers, security researchers, and privacy advocates.

Whether you need **HTTP proxies**, **SOCKS5 proxies**, **Shadowsocks**, **Trojan proxies**, **WireGuard VPN**, or **censorship circumvention tools** — this list has you covered. Updated regularly by the community and the team at [anonymous-proxies.net](https://anonymous-proxies.net?utm_source=github&utm_medium=link&utm_campaign=awesome-proxy).

---

## Contents

- [Proxy Libraries & SDKs](#proxy-libraries--sdks)
- [Shadowsocks & Variants](#shadowsocks--variants)
- [Trojan & Censorship Circumvention](#trojan--censorship-circumvention)
- [WireGuard & VPN Tools](#wireguard--vpn-tools)
- [Forward Proxies & HTTP/HTTPS Proxies](#forward-proxies--httphttps-proxies)
- [SOCKS5 Proxy Servers](#socks5-proxy-servers)
- [Reverse Proxies & Load Balancers](#reverse-proxies--load-balancers)
- [DNS Proxies & Encrypted DNS](#dns-proxies--encrypted-dns)
- [Proxy Clients & GUI Tools](#proxy-clients--gui-tools)
- [Web Scraping with Proxies](#web-scraping-with-proxies)
- [Proxy Checkers & Validators](#proxy-checkers--validators)
- [Proxy Scrapers & Free Lists](#proxy-scrapers--free-lists)
- [Anonymity Networks](#anonymity-networks)
- [Proxy Providers](#proxy-providers)
- [Related Awesome Lists](#related-awesome-lists)

---

## Proxy Libraries & SDKs

Libraries for integrating proxy rotation, management, and connections into your applications.

- [brozeph/simple-socks](https://github.com/brozeph/simple-socks) — Event-driven SOCKS5 proxy server library for Node.js.
- [JaredLGillespie/proxyscrape](https://github.com/JaredLGillespie/proxyscrape) — Python library for retrieving free proxies (HTTP, HTTPS, SOCKS4, SOCKS5).
- [snail007/goproxy](https://github.com/snail007/goproxy) — High-performance HTTP(S), SOCKS5, WebSocket proxy library in Go with chaining and encryption.

> 💡 **Building with proxies?** [anonymous-proxies.net](https://anonymous-proxies.net?utm_source=github&utm_medium=link&utm_campaign=awesome-proxy) offers HTTP, SOCKS5, Shadowsocks, Trojan, and WireGuard proxies with API access for programmatic rotation.

---

## Shadowsocks & Variants

Shadowsocks is a fast, secure proxy protocol originally designed to bypass internet censorship. It encrypts traffic and tunnels it through a remote server.

- [shadowsocks/shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev) — Lightweight, full-featured C implementation; the canonical Shadowsocks server and client.
- [shadowsocks/shadowsocks-rust](https://github.com/shadowsocks/shadowsocks-rust) — Rust port with better performance, async I/O, and modern cipher support.
- [shadowsocks/go-shadowsocks2](https://github.com/shadowsocks/go-shadowsocks2) — Clean Go implementation focused on core features and simplicity.
- [shadowsocksr-backup/shadowsocksr](https://github.com/shadowsocksr-backup/shadowsocksr) — ShadowsocksR (SSR) fork with protocol and obfuscation plugins.
- [dnomd343/shadowsocks-all](https://github.com/dnomd343/shadowsocks-all) — One-click install script for multiple Shadowsocks implementations.
- [teddysun/shadowsocks_install](https://github.com/teddysun/shadowsocks_install) — Auto-install scripts for various Shadowsocks versions on Linux.

---

## Trojan & Censorship Circumvention

Tools for bypassing internet restrictions, deep packet inspection (DPI), and the Great Firewall (GFW). Includes Trojan proxy, V2Ray, Xray, and anti-censorship protocols.

- [v2fly/v2ray-core](https://github.com/v2fly/v2ray-core) — Platform for building proxies to bypass network restrictions; supports VMess, VLESS, Trojan, Shadowsocks.
- [XTLS/Xray-core](https://github.com/XTLS/Xray-core) — Next-gen V2Ray with XTLS and Reality protocol for ultra-low-latency, anti-detection tunneling.
- [trojan-gfw/trojan](https://github.com/trojan-gfw/trojan) — Bypasses GFW by masquerading as legitimate HTTPS traffic — unidentifiable by DPI.
- [p4gefau1t/trojan-go](https://github.com/p4gefau1t/trojan-go) — Full-featured Trojan proxy in Go with multiplexing, routing, and CDN support.
- [klzgrad/naiveproxy](https://github.com/klzgrad/naiveproxy) — Uses Chrome's network stack to camouflage traffic as ordinary browser HTTPS.
- [SagerNet/sing-box](https://github.com/SagerNet/sing-box) — Universal proxy platform: Shadowsocks, V2Ray, Trojan, TUIC, Hysteria2 with unified config.
- [MHSanaei/3x-ui](https://github.com/MHSanaei/3x-ui) — Xray web panel for multi-protocol, multi-user traffic management.
- [2dust/v2rayN](https://github.com/2dust/v2rayN) — Windows GUI for V2Ray/Xray/sing-box with subscription support.
- [2dust/v2rayNG](https://github.com/2dust/v2rayNG) — Android client for V2Ray/Xray supporting VMess, VLESS, Shadowsocks, Trojan.
- [proxysu/ProxySU](https://github.com/proxysu/ProxySU) — One-click Windows installer for Xray, V2Ray, Trojan, NaiveProxy, and more.

> 🔒 **Need ready-to-use Trojan or Shadowsocks proxies?** [anonymous-proxies.net](https://anonymous-proxies.net?utm_source=github&utm_medium=link&utm_campaign=awesome-proxy) provides dedicated Trojan, Shadowsocks, and Amnezia VPN connections — no server setup required.

---

## WireGuard & VPN Tools

WireGuard is a modern, high-performance VPN protocol. These tools help you deploy, manage, and automate VPN servers.

- [WireGuard/wireguard-linux](https://github.com/WireGuard/wireguard-linux) — Official WireGuard kernel module for Linux.
- [WireGuard/wireguard-go](https://github.com/WireGuard/wireguard-go) — Cross-platform Go userspace implementation.
- [trailofbits/algo](https://github.com/trailofbits/algo) — Ansible scripts to set up a personal WireGuard and IPsec VPN in the cloud.
- [pivpn/pivpn](https://github.com/pivpn/pivpn) — Simple OpenVPN and WireGuard installer for Raspberry Pi and Linux.
- [angristan/wireguard-install](https://github.com/angristan/wireguard-install) — WireGuard VPN server one-click installer for Linux.
- [firezone/firezone](https://github.com/firezone/firezone) — Self-hosted WireGuard VPN platform with web UI and access management.
- [Nyr/openvpn-install](https://github.com/Nyr/openvpn-install) — OpenVPN road warrior installer for Debian, Ubuntu, Fedora, CentOS, Arch.
- [hwdsl2/setup-ipsec-vpn](https://github.com/hwdsl2/setup-ipsec-vpn) — IKEv2/IPsec VPN setup scripts for Ubuntu, Debian, CentOS.
- [pritunl/pritunl](https://github.com/pritunl/pritunl) — Enterprise distributed OpenVPN, IPsec, and WireGuard server with web UI.
- [freifunkMUC/wg-access-server](https://github.com/freifunkMUC/wg-access-server) — All-in-one WireGuard VPN with web UI for user and device management.

---

## Forward Proxies & HTTP/HTTPS Proxies

Forward proxy servers for web traffic filtering, caching, privacy, and traffic inspection.

- [squid-cache/squid](https://github.com/squid-cache/squid) — Full-featured web proxy cache supporting HTTP, HTTPS, FTP with extensive ACLs.
- [mitmproxy/mitmproxy](https://github.com/mitmproxy/mitmproxy) — Interactive HTTPS proxy for penetration testing, traffic inspection, and debugging.
- [tinyproxy/tinyproxy](https://github.com/tinyproxy/tinyproxy) — Lightweight HTTP/HTTPS proxy for low-resource systems.
- [XX-net/XX-Net](https://github.com/XX-net/XX-Net) — Proxy tool designed to bypass internet censorship.
- [snail007/goproxy](https://github.com/snail007/goproxy) — High-performance proxy in Go with chaining, encryption, and rate limiting.
- [bytedance/g3proxy](https://github.com/bytedance/g3) — HTTP/SOCKS/SNI proxy by ByteDance with MITM interception and ICAP adaptation.
- [3proxy/3proxy](https://github.com/3proxy/3proxy) — Tiny universal proxy supporting HTTP, HTTPS, SOCKS, POP3, FTP.

---

## SOCKS5 Proxy Servers

SOCKS5 proxies handle any type of traffic (not just HTTP) and support authentication and UDP.

- [shadowsocks/shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev) — Secure SOCKS5 proxy with encryption, designed to protect internet traffic.
- [rofl0r/microsocks](https://github.com/rofl0r/microsocks) — Tiny, portable SOCKS5 server with minimal resource usage.
- [brozeph/simple-socks](https://github.com/brozeph/simple-socks) — Simple SOCKS5 server library for Node.js.
- [bhhbazinga/socks5](https://github.com/bhhbazinga/socks5) — Lightweight SOCKS5 proxy in C using epoll and non-blocking sockets.
- [jgaa/shinysocks](https://github.com/jgaa/shinysocks) — Ultrafast async SOCKS proxy built with Boost.Asio.

---

## Reverse Proxies & Load Balancers

- [nginx/nginx](https://github.com/nginx/nginx) — High-performance HTTP server, reverse proxy, and load balancer.
- [traefik/traefik](https://github.com/traefik/traefik) — Cloud-native reverse proxy with automatic service discovery for Docker/K8s.
- [caddyserver/caddy](https://github.com/caddyserver/caddy) — Web server and reverse proxy with automatic HTTPS via Let's Encrypt.
- [haproxy/haproxy](https://github.com/haproxy/haproxy) — Reliable TCP/HTTP load balancer for large-scale deployments.
- [envoyproxy/envoy](https://github.com/envoyproxy/envoy) — Cloud-native L7 proxy for service meshes.
- [microsoft/reverse-proxy](https://github.com/microsoft/reverse-proxy) — YARP: customizable .NET reverse proxy library.
- [jwilder/nginx-proxy](https://github.com/jwilder/nginx-proxy) — Automated nginx reverse proxy for Docker containers.
- [NginxProxyManager/nginx-proxy-manager](https://github.com/NginxProxyManager/nginx-proxy-manager) — Web UI for managing Nginx proxies with automatic SSL.
- [flomesh-io/pipy](https://github.com/flomesh-io/pipy) — Programmable proxy for cloud, edge, and IoT.
- [inconshreveable/ngrok](https://github.com/inconshreveable/ngrok) — Secure tunnels to expose local servers through NATs and firewalls.

---

## DNS Proxies & Encrypted DNS

DNS proxy servers for privacy, ad-blocking, and encrypted DNS resolution (DoH, DoT, DNSCrypt).

- [jedisct1/dnscrypt-proxy](https://github.com/jedisct1/dnscrypt-proxy) — Flexible DNS proxy with DoH, DoT, and DNSCrypt support.
- [pi-hole/pi-hole](https://github.com/pi-hole/pi-hole) — Network-wide ad and tracker blocking via DNS sinkhole.
- [AdguardTeam/AdGuardHome](https://github.com/AdguardTeam/AdGuardHome) — Network-wide DNS ad blocker with web UI, DoH/DoT support.
- [0xERR0R/blocky](https://github.com/0xERR0R/blocky) — Fast DNS proxy with ad blocking, conditional forwarding, and caching.
- [NLnetLabs/unbound](https://github.com/NLnetLabs/unbound) — Validating, recursive, caching DNS resolver with DNSSEC.
- [thekelleys/dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html) — Lightweight DNS forwarder and DHCP server for small networks.

---

## Proxy Clients & GUI Tools

Desktop and mobile apps for managing proxy connections across multiple protocols.

- [Dreamacro/clash](https://github.com/Dreamacro/clash) — Rule-based tunneling proxy in Go: VMess, VLESS, Shadowsocks, Trojan, SOCKS5, HTTP.
- [MetaCubeX/mihomo](https://github.com/MetaCubeX/mihomo) — Enhanced Clash kernel with TUIC, Hysteria2, VLESS Reality, and advanced routing.
- [hiddify/hiddify-app](https://github.com/hiddify/hiddify-app) — Multi-platform proxy client on sing-box supporting all major protocols.
- [v2rayA/v2rayA](https://github.com/v2rayA/v2rayA) — Web GUI for V2Ray/Xray/sing-box with subscription management.
- [clash-verge-rev/clash-verge-rev](https://github.com/clash-verge-rev/clash-verge-rev) — Cross-platform Clash desktop client built with Tauri + React.
- [MatsuriDayo/NekoBoxForAndroid](https://github.com/MatsuriDayo/NekoBoxForAndroid) — Android proxy client for sing-box, V2Ray, Xray, Shadowsocks.
- [Qv2ray/Qv2ray](https://github.com/Qv2ray/Qv2ray) — Cross-platform V2Ray GUI in Qt with plugin support.

---

## Web Scraping with Proxies

Frameworks and tools for web scraping that support proxy rotation — essential for large-scale data collection without getting blocked.

- [apify/crawlee](https://github.com/apify/crawlee) — Scalable web crawling library for Node.js with Puppeteer, Playwright, Cheerio — built-in proxy rotation.
- [scrapy/scrapy](https://github.com/scrapy/scrapy) — Fast, high-level Python web scraping framework with middleware for proxy rotation.
- [AmazingAng/proxy-pool](https://github.com/AmazingAng/proxy-pool) — Python proxy pool for web scraping with automated collection and validation.
- [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl) — Turn entire websites into LLM-ready markdown — handles proxies, JS rendering, and dynamic content.

> 🕷️ **Scraping at scale?** Rotating residential and datacenter proxies prevent IP bans. [anonymous-proxies.net](https://anonymous-proxies.net?utm_source=github&utm_medium=link&utm_campaign=awesome-proxy) offers HTTP and SOCKS5 proxies in 100+ locations, optimized for scraping workloads.

---

## Proxy Checkers & Validators

Tools to test, validate, and benchmark proxy speed, anonymity, and geo-location.

- [drsoft-oss/proxybench](https://github.com/drsoft-oss/proxybench) — Proxy checker and health monitor CLI — validate and benchmark HTTP, SOCKS5, and Shadowsocks proxies.
- [fate0/proxypool](https://github.com/fate0/proxypool) — Automated proxy pool with collection, validation, and a REST API.
- [monosans/proxy-list](https://github.com/monosans/proxy-list) — Continuously updated proxy lists with built-in validation.

---

## Proxy Scrapers & Free Lists

Auto-updated lists and scrapers for free public proxies. Note: free proxies are unreliable and slow — for production use, consider a [dedicated proxy provider](#proxy-providers).

- [TheSpeedX/PROXY-List](https://github.com/TheSpeedX/PROXY-List) — Auto-updated daily list of free HTTP, HTTPS, and SOCKS5 proxies.
- [clarketm/proxy-list](https://github.com/clarketm/proxy-list) — Daily-updated free public proxy list.
- [hookzof/socks5_list](https://github.com/hookzof/socks5_list) — Constantly updated SOCKS5 proxy list with validation.
- [monosans/proxy-list](https://github.com/monosans/proxy-list) — HTTP, SOCKS4, SOCKS5 proxies from multiple sources.
- [sakha1370/OpenRay](https://github.com/sakha1370/OpenRay) — Large-scale proxy collection and validation pipeline.

---

## Anonymity Networks

Privacy-focused overlay networks for anonymous communication.

- [torproject/tor](https://gitlab.torproject.org/tpo/core/tor) — The Tor network — encrypted onion routing to anonymize TCP traffic.
- [i2p/i2p.i2p](https://github.com/i2p/i2p.i2p) — I2P (Invisible Internet Project) — private, self-contained anonymizing network.
- [PurpleI2P/i2pd](https://github.com/PurpleI2P/i2pd) — Fast, lightweight C++ I2P router.
- [rahra/onioncat](https://github.com/rahra/onioncat) — IPv6 VPN adapter for Tor and I2P networks.
- [Ayms/node-Tor](https://github.com/Ayms/node-Tor) — JavaScript Tor implementation for Node.js and browsers.
- [thaliproject/Tor_Onion_Proxy_Library](https://github.com/thaliproject/Tor_Onion_Proxy_Library) — Java/Android library to embed Tor in mobile apps.

---

## Related Awesome Lists

- [dariubs/awesome-proxy](https://github.com/dariubs/awesome-proxy) — Collaborative list of proxy servers and resources.
- [cedrickchee/awesome-wireguard](https://github.com/cedrickchee/awesome-wireguard) — WireGuard tools, projects, and resources.
- [ajvb/awesome-tor](https://github.com/ajvb/awesome-tor) — Tor-related projects, articles, and papers.

---

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting a PR.

If you know a project that belongs here, [open an issue](../../issues/new) or submit a pull request.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

---

<sub>Maintained by the team at <a href="https://anonymous-proxies.net?utm_source=github&utm_medium=link&utm_campaign=awesome-proxy">anonymous-proxies.net</a> — HTTP, SOCKS5, Shadowsocks, Trojan, DNS & WireGuard proxies for developers.</sub>
