# awesome-proxies

> A curated list of awesome open-source proxy tools, servers, clients, VPNs, and related resources — organized by topic.

---

## Table of Contents

- [Shadowsocks & Variants](#shadowsocks--variants)
- [V2Ray / Xray / Censorship Circumvention](#v2ray--xray--censorship-circumvention)
- [WireGuard & VPN](#wireguard--vpn)
- [Reverse Proxies](#reverse-proxies)
- [Forward Proxies & HTTP(S) Proxies](#forward-proxies--https-proxies)
- [SOCKS Proxies](#socks-proxies)
- [DNS Proxies & Tools](#dns-proxies--tools)
- [Proxy Clients & Management UIs](#proxy-clients--management-uis)
- [Anonymity Networks](#anonymity-networks)
- [Proxy Scrapers & Lists](#proxy-scrapers--lists)

---

## Shadowsocks & Variants

- [shadowsocks/shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev) — Lightweight, full-featured port forwarding and traffic tunneling tool written in C; the canonical Shadowsocks implementation.
- [shadowsocks/shadowsocks-rust](https://github.com/shadowsocks/shadowsocks-rust) — A Rust port of Shadowsocks offering better performance, async I/O, and modern cipher support.
- [shadowsocks/go-shadowsocks2](https://github.com/shadowsocks/go-shadowsocks2) — A clean Go implementation of Shadowsocks, focused on core features and simplicity.
- [shadowsocksr-backup/shadowsocksr](https://github.com/shadowsocksr-backup/shadowsocksr) — ShadowsocksR (SSR) fork with protocol and obfuscation plugins to disguise traffic patterns.
- [dnomd343/shadowsocks-all](https://github.com/dnomd343/shadowsocks-all) — One-click install script for multiple Shadowsocks implementations including shadowsocks-libev, go, and plugins.
- [teddysun/shadowsocks_install](https://github.com/teddysun/shadowsocks_install) — Auto-install scripts for various Shadowsocks versions on Linux servers.

---

## V2Ray / Xray / Censorship Circumvention

- [v2fly/v2ray-core](https://github.com/v2fly/v2ray-core) — A platform for building proxies to bypass network restrictions; supports VMess, VLESS, Trojan, Shadowsocks, and more.
- [XTLS/Xray-core](https://github.com/XTLS/Xray-core) — Next-generation V2Ray core featuring XTLS and the Reality protocol for ultra-low-latency, anti-detection tunneling.
- [trojan-gfw/trojan](https://github.com/trojan-gfw/trojan) — An unidentifiable mechanism to bypass GFW by masquerading as legitimate HTTPS traffic.
- [p4gefau1t/trojan-go](https://github.com/p4gefau1t/trojan-go) — Full-featured Trojan proxy written in Go, with multiplexing, routing, and CDN support.
- [klzgrad/naiveproxy](https://github.com/klzgrad/naiveproxy) — NaiveProxy uses Chrome's network stack to camouflage traffic as ordinary browser HTTPS, defeating deep packet inspection.
- [SagerNet/sing-box](https://github.com/SagerNet/sing-box) — Universal proxy platform supporting Shadowsocks, V2Ray, Trojan, TUIC, Hysteria2, and more with a unified config format.
- [MHSanaei/3x-ui](https://github.com/MHSanaei/3x-ui) — Xray web panel supporting multi-protocol, multi-user traffic management with expiry, quota, and IP limits.
- [2dust/v2rayN](https://github.com/2dust/v2rayN) — Windows GUI client for V2Ray/Xray/sing-box with subscription support and system proxy management.
- [2dust/v2rayNG](https://github.com/2dust/v2rayNG) — Android client for V2Ray/Xray, supporting VMess, VLESS, Shadowsocks, Trojan, and more.
- [proxysu/ProxySU](https://github.com/proxysu/ProxySU) — Windows-based one-click installer for Xray, V2Ray, Trojan, NaiveProxy, ShadowsocksR, and MTProto.

---

## WireGuard & VPN

- [WireGuard/wireguard-linux](https://github.com/WireGuard/wireguard-linux) — Official WireGuard kernel module for Linux; a fast, modern, and secure VPN tunnel protocol.
- [WireGuard/wireguard-go](https://github.com/WireGuard/wireguard-go) — Cross-platform Go userspace implementation of the WireGuard protocol.
- [trailofbits/algo](https://github.com/trailofbits/algo) — Ansible scripts to set up a personal WireGuard and IPsec VPN in the cloud with minimal configuration.
- [pivpn/pivpn](https://github.com/pivpn/pivpn) — Simple, audited OpenVPN and WireGuard installer for Raspberry Pi and other Linux devices.
- [Nyr/openvpn-install](https://github.com/Nyr/openvpn-install) — OpenVPN road warrior installer for Debian, Ubuntu, Fedora, CentOS, Arch, and more.
- [angristan/wireguard-install](https://github.com/angristan/wireguard-install) — WireGuard VPN server one-click installer for Linux.
- [firezone/firezone](https://github.com/firezone/firezone) — Self-hosted WireGuard-based VPN and network access management platform with a web interface.
- [hwdsl2/setup-ipsec-vpn](https://github.com/hwdsl2/setup-ipsec-vpn) — Scripts to set up IKEv2/IPsec VPN with Libreswan and xl2tpd on Ubuntu, Debian, CentOS, and more.
- [pritunl/pritunl](https://github.com/pritunl/pritunl) — Enterprise-grade distributed OpenVPN, IPsec, and WireGuard server with a web management UI.
- [freifunkMUC/wg-access-server](https://github.com/freifunkMUC/wg-access-server) — All-in-one WireGuard VPN solution with a web UI for user and device management.

---

## Reverse Proxies

- [nginx/nginx](https://github.com/nginx/nginx) — High-performance HTTP and reverse proxy server, also used as a load balancer and mail proxy.
- [traefik/traefik](https://github.com/traefik/traefik) — Cloud-native reverse proxy and load balancer with automatic service discovery for Docker and Kubernetes.
- [caddyserver/caddy](https://github.com/caddyserver/caddy) — Fast, extensible, multi-platform web server and reverse proxy with automatic HTTPS via Let's Encrypt.
- [haproxy/haproxy](https://github.com/haproxy/haproxy) — Reliable, high-performance TCP and HTTP load balancer and reverse proxy used in large-scale deployments.
- [envoyproxy/envoy](https://github.com/envoyproxy/envoy) — Cloud-native, high-performance L7 edge/middle/service proxy designed for service meshes.
- [microsoft/reverse-proxy](https://github.com/microsoft/reverse-proxy) — YARP (Yet Another Reverse Proxy): a customizable .NET library for building reverse proxy servers.
- [jwilder/nginx-proxy](https://github.com/jwilder/nginx-proxy) — Automated nginx reverse proxy for Docker containers using docker-gen.
- [nicholasgasior/nginx-proxy-manager](https://github.com/NginxProxyManager/nginx-proxy-manager) — Web-based UI for managing Nginx proxy hosts with automatic SSL certificate provisioning.
- [jiangplus/pipy](https://github.com/flomesh-io/pipy) — Programmable network proxy for cloud, edge, and IoT, scriptable with PipyJS.
- [inconshreveable/ngrok](https://github.com/inconshreveable/ngrok) — Secure tunnels to expose local servers to the public internet over any NAT or firewall.

---

## Forward Proxies & HTTP(S) Proxies

- [squid-cache/squid](https://github.com/squid-cache/squid) — Full-featured web proxy cache supporting HTTP, HTTPS, FTP, and more with extensive access control.
- [mitmproxy/mitmproxy](https://github.com/mitmproxy/mitmproxy) — Interactive HTTPS man-in-the-middle proxy for penetration testing, traffic inspection, and debugging.
- [tinyproxy/tinyproxy](https://github.com/tinyproxy/tinyproxy) — Lightweight HTTP/HTTPS proxy daemon designed for low-resource systems.
- [privoxy/privoxy](https://github.com/priv-oxy/privoxy) — Non-caching web proxy with advanced filtering for privacy protection and ad blocking.
- [XX-net/XX-Net](https://github.com/XX-net/XX-Net) — Proxy tool designed to bypass internet censorship, focused on China's GFW.
- [snail007/goproxy](https://github.com/snail007/goproxy) — High-performance HTTP(S), SOCKS5, WebSocket, TCP, UDP proxy server in Go with chaining, encryption, and rate limiting.
- [bytedance/g3proxy](https://github.com/bytedance/g3) — HTTP/SOCKS/SNI/Transparent proxy by ByteDance supporting proxy chaining, MITM interception, and ICAP adaptation.
- [vzex/3proxy](https://github.com/3proxy/3proxy) — Tiny, universal free proxy server supporting HTTP, HTTPS, SOCKS, POP3, FTP, and more.

---

## SOCKS Proxies

- [shadowsocks/shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev) — Secure SOCKS5 proxy with encryption, designed to protect your internet traffic.
- [rofl0r/microsocks](https://github.com/rofl0r/microsocks) — Tiny, portable SOCKS5 server with very moderate resource usage and optional authentication.
- [brozeph/simple-socks](https://github.com/brozeph/simple-socks) — Simple, event-driven SOCKS5 proxy server library for Node.js.
- [dante/dante](https://github.com/notpeter/dante) — Free, BSD-licensed SOCKS server and client library supporting SOCKS4 and SOCKS5.
- [bhhbazinga/socks5](https://github.com/bhhbazinga/socks5) — Lightweight SOCKS5 proxy server implemented in C using epoll and non-blocking sockets.
- [jgaa/shinysocks](https://github.com/jgaa/shinysocks) — Small, ultrafast asynchronous SOCKS proxy server built with Boost.Asio.

---

## DNS Proxies & Tools

- [thekelleys/dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html) — Lightweight DNS forwarder, DHCP server, and network boot server for small networks.
- [jedisct1/dnscrypt-proxy](https://github.com/jedisct1/dnscrypt-proxy) — Flexible DNS proxy with support for DoH, DoT, and DNSCrypt to encrypt and anonymize DNS traffic.
- [nicowillis/pi-hole](https://github.com/pi-hole/pi-hole) — Network-level advertisement and tracker blocker acting as a DNS sinkhole for all devices on your network.
- [nicowillis/AdGuardHome](https://github.com/AdguardTeam/AdGuardHome) — Network-wide ad and tracker blocking DNS server with a web interface and DoH/DoT support.
- [0xERR0R/blocky](https://github.com/0xERR0R/blocky) — Fast, memory-efficient DNS proxy with ad blocking, conditional forwarding, and caching.
- [nicowillis/Unbound](https://github.com/NLnetLabs/unbound) — Validating, recursive, caching DNS resolver with DNSSEC support.

---

## Proxy Clients & Management UIs

- [Dreamacro/clash](https://github.com/Dreamacro/clash) — Rule-based tunneling proxy in Go supporting VMess, VLESS, Shadowsocks, Trojan, SOCKS5, and HTTP.
- [MetaCubeX/mihomo](https://github.com/MetaCubeX/mihomo) — Enhanced Clash.Meta kernel (now mihomo) with TUIC, Hysteria2, VLESS Reality, and advanced routing.
- [hiddify/hiddify-app](https://github.com/hiddify/hiddify-app) — Multi-platform proxy client built on sing-box, supporting all major protocols with a simple UI.
- [v2rayA/v2rayA](https://github.com/v2rayA/v2rayA) — Web-based GUI for V2Ray/Xray/sing-box/Trojan with subscription management and Linux transparent proxy support.
- [clash-verge-rev/clash-verge-rev](https://github.com/clash-verge-rev/clash-verge-rev) — Modern cross-platform Clash/Mihomo desktop client built with Tauri and React.
- [NekoBoxForAndroid/NekoBox](https://github.com/MatsuriDayo/NekoBoxForAndroid) — Android proxy client supporting sing-box, V2Ray, Xray, Shadowsocks, and more.
- [Qv2ray/Qv2ray](https://github.com/Qv2ray/Qv2ray) — Cross-platform V2Ray GUI client in Qt with plugin support.
- [v2fly/v2raya](https://github.com/v2rayA/v2rayA) — Browser-based proxy manager supporting V2Ray, Xray, and Trojan.

---

## Anonymity Networks

- [torproject/tor](https://gitlab.torproject.org/tpo/core/tor) — The Tor anonymity network — an encrypted overlay network using onion routing to anonymize TCP traffic.
- [i2p/i2p.i2p](https://github.com/i2p/i2p.i2p) — I2P (Invisible Internet Project) — a private, self-contained anonymizing network for communication and services.
- [PurpleI2P/i2pd](https://github.com/PurpleI2P/i2pd) — Fast, lightweight C++ implementation of the I2P router.
- [rahra/onioncat](https://github.com/rahra/onioncat) — VPN adapter for Tor and I2P, enabling IPv6-based VPN over anonymity networks.
- [Ayms/node-Tor](https://github.com/Ayms/node-Tor) — JavaScript implementation of the Tor protocol, usable in Node.js and browser environments via WebSockets/WebRTC.
- [thaliproject/Tor_Onion_Proxy_Library](https://github.com/thaliproject/Tor_Onion_Proxy_Library) — Java/Android library for embedding the Tor Onion Proxy into mobile and desktop applications.

---

## Proxy Scrapers & Lists

- [TheSpeedX/PROXY-List](https://github.com/TheSpeedX/PROXY-List) — Auto-updated daily list of free public HTTP, HTTPS, and SOCKS5 proxies collected from across the web.
- [clarketm/proxy-list](https://github.com/clarketm/proxy-list) — List of free, public, forward proxy servers updated daily.
- [hookzof/socks5_list](https://github.com/hookzof/socks5_list) — Constantly updated list of working SOCKS5 proxies with automated validation.
- [monosans/proxy-list](https://github.com/monosans/proxy-list) — Continuously updated lists of HTTP, SOCKS4, and SOCKS5 proxies scraped from multiple sources.
- [sakha1370/OpenRay](https://github.com/sakha1370/OpenRay) — Large-scale system for collecting, validating, and curating free proxy servers via a three-stage hourly pipeline.

---

## Related Awesome Lists

- [dariubs/awesome-proxy](https://github.com/dariubs/awesome-proxy) — A collaborative list of awesome proxy servers, resources, and protocols.
- [cedrickchee/awesome-wireguard](https://github.com/cedrickchee/awesome-wireguard) — Curated list of WireGuard tools, projects, and resources.
- [ajvb/awesome-tor](https://github.com/ajvb/awesome-tor) — A list of awesome Tor-related projects, articles, and papers.

---

*Contributions welcome. If you know a project that belongs here, open a PR.*
