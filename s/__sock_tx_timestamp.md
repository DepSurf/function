# Function: <code>__sock_tx_timestamp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __sock_tx_timestamp(const struct sock *sk, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fb6b0)
Location: net/socket.c:589
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff816fb6b0-ffffffff816fb6f3: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81762110)
Location: net/socket.c:590
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff81762110-ffffffff81762146: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8178f120)
Location: net/socket.c:616
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff8178f120-ffffffff8178f156: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ad120)
Location: net/socket.c:614
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff817ad120-ffffffff817ad156: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81825120)
Location: net/socket.c:619
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff81825120-ffffffff81825156: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186f120)
Location: net/socket.c:623
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff8186f120-ffffffff8186f156: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8188f5d0)
Location: net/socket.c:603
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff8188f5d0-ffffffff8188f606: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818d9650)
Location: net/socket.c:614
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff818d9650-ffffffff818d9686: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190b650)
Location: net/socket.c:614
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff8190b650-ffffffff8190b686: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819dd840)
Location: net/socket.c:629
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff819dd840-ffffffff819dd876: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819dd230)
Location: net/socket.c:629
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff819dd230-ffffffff819dd266: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c3480)
Location: net/socket.c:631
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff819c3480-ffffffff819c34b6: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a72d30)
Location: net/socket.c:681
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff81a72d30-ffffffff81a72d66: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be5540)
Location: net/socket.c:682
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff81be5540-ffffffff81be558a: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d917a0)
Location: net/socket.c:684
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff81d917a0-ffffffff81d917ea: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81dffa70)
Location: net/socket.c:689
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff81dffa70-ffffffff81dffaba: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebbf50)
Location: net/socket.c:691
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff81ebbf50-ffffffff81ebbf9a: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba0a50)
Location: net/socket.c:614
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffff800010ba0a50-ffff800010ba0aa8: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc2edc)
Location: net/socket.c:614
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
c0cc2edc-c0cc2f14: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c74960)
Location: net/socket.c:614
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
c000000000c74960-c000000000c74998: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073885c)
Location: net/socket.c:614
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffe00073885c-ffffffe0007388a8: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ab650)
Location: net/socket.c:614
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff818ab650-ffffffff818ab686: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818655a0)
Location: net/socket.c:614
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff818655a0-ffffffff818655d6: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fc650)
Location: net/socket.c:614
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff818fc650-ffffffff818fc686: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __sock_tx_timestamp(__u16 tsflags, __u8 *tx_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191d650)
Location: net/socket.c:614
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/tcp.c:tcp_tx_timestamp
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff8191d650-ffffffff8191d686: __sock_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>__u16 tsflags</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct sock *sk</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
