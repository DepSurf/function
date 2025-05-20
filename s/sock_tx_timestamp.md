# Function: <code>sock_tx_timestamp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff815eead4)
Location: include/net/sock.h:2188
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/ipv4/tcp.c (ffffffff81766bde)
Location: include/net/sock.h:2188
Inline: True
```
```
In net/ipv4/raw.c (ffffffff8178515a)
Location: include/net/sock.h:2188
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8178771b)
Location: include/net/sock.h:2188
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff817a3ab7)
Location: include/net/sock.h:2188
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff817c615a)
Location: include/net/sock.h:2188
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818074c8)
Location: include/net/sock.h:2188
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817d3095)
Location: include/net/sock.h:2169
Inline: True
```
```
In net/ipv4/raw.c (ffffffff817f275d)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff817f4ea7)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff8181083b)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff8183316b)
Location: include/net/sock.h:2169
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81879c26)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81803025)
Location: include/net/sock.h:2236
Inline: True
```
```
In net/ipv4/raw.c (ffffffff818235c5)
Location: include/net/sock.h:2236
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81825f72)
Location: include/net/sock.h:2236
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81841d3b)
Location: include/net/sock.h:2236
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81864ce3)
Location: include/net/sock.h:2236
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818ae323)
Location: include/net/sock.h:2236
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81823225)
Location: include/net/sock.h:2263
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81843fa2)
Location: include/net/sock.h:2263
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81846703)
Location: include/net/sock.h:2263
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff8186361a)
Location: include/net/sock.h:2263
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81888307)
Location: include/net/sock.h:2263
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d4d25)
Location: include/net/sock.h:2263
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a1392)
Location: include/net/sock.h:2277
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (ffffffff818c38f1)
Location: include/net/sock.h:2277
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff818c6133)
Location: include/net/sock.h:2277
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff818e375a)
Location: include/net/sock.h:2277
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff8190a6e9)
Location: include/net/sock.h:2277
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819597a7)
Location: include/net/sock.h:2277
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818f5eac)
Location: include/net/sock.h:2284
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (ffffffff819197d3)
Location: include/net/sock.h:2284
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8191b885)
Location: include/net/sock.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81939fe4)
Location: include/net/sock.h:2284
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81961ae8)
Location: include/net/sock.h:2284
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819b0454)
Location: include/net/sock.h:2284
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8191926c)
Location: include/net/sock.h:2412
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff819253ac)
Location: include/net/sock.h:2412
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv6/ip6_output.c (ffffffff81995c6d)
Location: include/net/sock.h:2412
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8197b5a0)
Location: include/net/sock.h:2418
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff8198700a)
Location: include/net/sock.h:2418
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv6/ip6_output.c (ffffffff81a019b2)
Location: include/net/sock.h:2418
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819b24a5)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff819bd79a)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv6/ip6_output.c (ffffffff81a38573)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a9baf5)
Location: include/net/sock.h:2491
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff81aa8baa)
Location: include/net/sock.h:2491
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv6/ip6_output.c (ffffffff81b2e407)
Location: include/net/sock.h:2491
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81aa5955)
Location: include/net/sock.h:2512
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff81ab305a)
Location: include/net/sock.h:2512
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ce57)
Location: include/net/sock.h:2512
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a91095)
Location: include/net/sock.h:2548
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff81a9e2ba)
Location: include/net/sock.h:2548
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv6/ip6_output.c (ffffffff81b2a2b7)
Location: include/net/sock.h:2548
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81b4be25)
Location: include/net/sock.h:2607
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff81b59c0a)
Location: include/net/sock.h:2607
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv6/ip6_output.c (ffffffff81befe92)
Location: include/net/sock.h:2607
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81cd9555)
Location: include/net/sock.h:2731
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff81ce8131)
Location: include/net/sock.h:2731
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv6/ip6_output.c (ffffffff81d87f27)
Location: include/net/sock.h:2731
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81e99cb4)
Location: include/net/sock.h:2777
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff81eaca61)
Location: include/net/sock.h:2777
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv6/ip6_output.c (ffffffff81f55cc3)
Location: include/net/sock.h:2777
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81ef8624)
Location: include/net/sock.h:2765
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81f0cf6e)
Location: include/net/sock.h:2765
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81fb569b)
Location: include/net/sock.h:2765
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81fbc533)
Location: include/net/sock.h:2756
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81fd106e)
Location: include/net/sock.h:2756
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff82082d89)
Location: include/net/sock.h:2756
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffff800010c6201c)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffff800010c6f30c)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv6/ip6_output.c (ffff800010cf8af8)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c0d71a4c)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (c0d7e500)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv6/ip6_output.c (c0e0021c)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c000000000d66640)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (c000000000d76034)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv6/ip6_output.c (c000000000e21cd8)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffe0007caa5e)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffe0007d46ea)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv6/ip6_output.c (ffffffe000844818)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81952315)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff8195d60a)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv6/ip6_output.c (ffffffff819d7c03)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8190be05)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff819170fa)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv6/ip6_output.c (ffffffff819949c3)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819bcae5)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff819c7dda)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv6/ip6_output.c (ffffffff81a42683)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819c63f5)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff819d192a)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv6/ip6_output.c (ffffffff81a4e313)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
</ul>

## Differences
