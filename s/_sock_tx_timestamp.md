# Function: <code>_sock_tx_timestamp</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
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
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff819253ac)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (ffffffff819480bf)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81995c6d)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (ffffffff819be5f9)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff819e7c5a)
Location: include/net/sock.h:2399
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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8197b5a0)
Location: include/net/sock.h:2405
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff8198700a)
Location: include/net/sock.h:2405
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (ffffffff819ac387)
Location: include/net/sock.h:2405
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a019b2)
Location: include/net/sock.h:2405
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (ffffffff81a2d049)
Location: include/net/sock.h:2405
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a547ef)
Location: include/net/sock.h:2405
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff819bd79a)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (ffffffff819e2e1c)
Location: include/net/sock.h:2426
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a38573)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (ffffffff81a63b8a)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81a8b3df)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff81aa8baa)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (ffffffff81ad06fd)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (ffffffff81b2e407)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (ffffffff81b5c61a)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81b871ff)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff81ab305a)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (ffffffff81adc70d)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ce57)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (ffffffff81b6ae5a)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81b96d58)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/net/sock.h:2535
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff81a9e2ba)
Location: include/net/sock.h:2535
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (ffffffff81ac7758)
Location: include/net/sock.h:2535
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (ffffffff81b2a2b7)
Location: include/net/sock.h:2535
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (ffffffff81b59165)
Location: include/net/sock.h:2535
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81b85d5b)
Location: include/net/sock.h:2535
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/net/sock.h:2594
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff81b59c0a)
Location: include/net/sock.h:2594
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (ffffffff81b85fa1)
Location: include/net/sock.h:2594
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (ffffffff81befe92)
Location: include/net/sock.h:2594
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (ffffffff81c20752)
Location: include/net/sock.h:2594
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81c52101)
Location: include/net/sock.h:2594
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/net/sock.h:2718
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff81ce8131)
Location: include/net/sock.h:2718
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (ffffffff81d168f3)
Location: include/net/sock.h:2718
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (ffffffff81d87f27)
Location: include/net/sock.h:2718
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (ffffffff81dbd4d7)
Location: include/net/sock.h:2718
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81df413a)
Location: include/net/sock.h:2718
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/net/sock.h:2764
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff81eaca61)
Location: include/net/sock.h:2764
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (ffffffff81edd0a2)
Location: include/net/sock.h:2764
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (ffffffff81f55cc3)
Location: include/net/sock.h:2764
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (ffffffff81f8da16)
Location: include/net/sock.h:2764
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81fc8f68)
Location: include/net/sock.h:2764
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/net/sock.h:2752
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81f0cf6e)
Location: include/net/sock.h:2752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff81f3c2f2)
Location: include/net/sock.h:2752
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (ffffffff81fb569b)
Location: include/net/sock.h:2752
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (ffffffff81fee1f2)
Location: include/net/sock.h:2752
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff820298ff)
Location: include/net/sock.h:2752
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/net/sock.h:2743
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81fd106e)
Location: include/net/sock.h:2743
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff8200241c)
Location: include/net/sock.h:2743
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (ffffffff82082d89)
Location: include/net/sock.h:2743
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (ffffffff820bbdc2)
Location: include/net/sock.h:2743
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff820f93c9)
Location: include/net/sock.h:2743
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffff800010c6f30c)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (ffff800010c97bf8)
Location: include/net/sock.h:2426
Inline: True
```
```
In net/ipv6/ip6_output.c (ffff800010cf8af8)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (ffff800010d29c38)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffff800010d59f04)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (c0d7e500)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (c0da59f0)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (c0e0021c)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (c0e2d9dc)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (c0e5897c)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (c000000000d76034)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (c000000000da8b50)
Location: include/net/sock.h:2426
Inline: True
```
```
In net/ipv6/ip6_output.c (c000000000e21cd8)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (c000000000e5aa50)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (c000000000e9417c)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffe0007d46ea)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (ffffffe0007f6050)
Location: include/net/sock.h:2426
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffe000844818)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (ffffffe00086a464)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffe00088fe00)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff8195d60a)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (ffffffff81982c8c)
Location: include/net/sock.h:2426
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819d7c03)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (ffffffff81a0321a)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81a2aa6f)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff819170fa)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (ffffffff8193c74c)
Location: include/net/sock.h:2426
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819949c3)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (ffffffff819bffda)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff819e7c5f)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff819c7dda)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (ffffffff819ed45c)
Location: include/net/sock.h:2426
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a42683)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (ffffffff81a6dc9a)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81a9661f)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/tcp.c (ffffffff819d192a)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/raw.c (ffffffff819f733c)
Location: include/net/sock.h:2426
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4e313)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/raw.c (ffffffff81a7a2ba)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81aa3299)
Location: include/net/sock.h:2426
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
</details>
</li>
</ul>

## Differences
