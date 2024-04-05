port: 7890
socks-port: 7891
allow-lan: false
mode: Rule
log-level: info
external-controller: :9090
proxies:
  - {name: toy美国US1, server: us1.toytoy.top, port: 4431, type: trojan, password: MOL0ib7vsKrXxbCW, sni: usa1.toy0001.top, skip-cert-verify: false}
  - {name: toy美国US2, server: us2.toytoy.top, port: 443, type: trojan, password: MOL0ib7vsKrXxbCW, sni: hka2.toy0001.top, skip-cert-verify: false}
  - {name: toy新加坡sg1Gdd, server: 2ss1.ssss678.top, port: 35501, type: ss, cipher: chacha20-ietf-poly1305, password: d44f68f2-ae8f-4efe-9e38-d19a8a76774e}
  - {name: toy新加坡sg2Gdd, server: 2ss1.ssss678.top, port: 35501, type: ss, cipher: aes-128-ctr, password: d44f68f2-ae8f-4efe-9e38-d19a8a76774e}
  - {name: toy新加坡sg3Gdd, server: 2ss1.ssss678.top, port: 35501, type: ss, cipher: rc4-md5, password: d44f68f2-ae8f-4efe-9e38-d19a8a76774e}
  - {name: toy日本jp2, server: jpa2.toytoy.top, port: 443, type: trojan, password: MOL0ib7vsKrXxbCW, sni: jpa2.toytoy.top, skip-cert-verify: false}
  - {name: toy1香港hk, server: hka2.toytoy.top, port: 8999, type: vmess, uuid: 9089F4B8-0B6A-297B-C818-F208B0EED767, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /viee, headers: {Host: hka2.toytoy.top}}}
  - {name: toy17a新加坡sg, server: sga2.toytoy.top, port: 12560, type: vmess, uuid: D7565FA0-243B-789E-6180-CEA58DCC7673, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /viee, headers: {Host: sga2.toytoy.top}}}
  - {name: toy台湾tw1, server: twa2.toytoy.top, port: 20000, type: ssr, cipher: aes-128-ctr, password: 9atHSG, protocol: auth_aes128_md5, obfs: tls1.2_ticket_auth, protocol-param: 28965:lx0arf3orhp, obfs-param: 489f223165.microsoft.com}
  - {name: toy香港hk3, server: hkb2.toytoy.top, port: 20000, type: ssr, cipher: aes-128-ctr, password: 9atHSG, protocol: auth_aes128_md5, obfs: tls1.2_ticket_auth, protocol-param: 23876:lx0arf3orhp, obfs-param: 489f223165.microsoft.com}
