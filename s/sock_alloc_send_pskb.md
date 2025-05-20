# Function: <code>sock_alloc_send_pskb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817025f0)
Location: net/core/sock.c:1841
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff817025f0-ffffffff817027fb: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81769820)
Location: net/core/sock.c:1870
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81769820-ffffffff81769a43: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81796740)
Location: net/core/sock.c:1868
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81796740-ffffffff81796959: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b4b10)
Location: net/core/sock.c:2007
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff817b4b10-ffffffff817b4d27: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182cd50)
Location: net/core/sock.c:2045
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff8182cd50-ffffffff8182cf6b: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81876b40)
Location: net/core/sock.c:2065
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81876b40-ffffffff81876d63: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81897310)
Location: net/core/sock.c:2061
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81897310-ffffffff81897533: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e1760)
Location: net/core/sock.c:2202
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff818e1760-ffffffff818e1971: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81913950)
Location: net/core/sock.c:2217
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff81913950-ffffffff81913b65: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e6040)
Location: net/core/sock.c:2326
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff819e6040-ffffffff819e616d: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e5410)
Location: net/core/sock.c:2318
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff819e5410-ffffffff819e556c: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cb440)
Location: net/core/sock.c:2341
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff819cb440-ffffffff819cb671: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7aad0)
Location: net/core/sock.c:2465
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff81a7aad0-ffffffff81a7ad01: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bee9f0)
Location: net/core/sock.c:2634
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/mctp/af_mctp.c:mctp_sendmsg
```
**Symbols:**

```
ffffffff81bee9f0-ffffffff81beec3f: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9b040)
Location: net/core/sock.c:2713
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/mctp/af_mctp.c:mctp_sendmsg
```
**Symbols:**

```
ffffffff81d9b040-ffffffff81d9b28f: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0a230)
Location: net/core/sock.c:2773
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/mctp/af_mctp.c:mctp_sendmsg
```
**Symbols:**

```
ffffffff81e0a230-ffffffff81e0a476: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec6c20)
Location: net/core/sock.c:2753
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:xsk_build_skb
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/mctp/af_mctp.c:mctp_sendmsg
```
**Symbols:**

```
ffffffff81ec6c20-ffffffff81ec6e6a: sock_alloc_send_pskb (STB_GLOBAL)
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
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bab398)
Location: net/core/sock.c:2217
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffff800010bab398-ffff800010bab604: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc9f84)
Location: net/core/sock.c:2217
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
c0cc9f84-c0cca1c0: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c81c20)
Location: net/core/sock.c:2217
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
c000000000c81c20-c000000000c81f20: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073ecee)
Location: net/core/sock.c:2217
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffe00073ecee-ffffffe00073ee96: sock_alloc_send_pskb (STB_GLOBAL)
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
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b3950)
Location: net/core/sock.c:2217
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff818b3950-ffffffff818b3b65: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186d8a0)
Location: net/core/sock.c:2217
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff8186d8a0-ffffffff8186dab5: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81904950)
Location: net/core/sock.c:2217
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff81904950-ffffffff81904b65: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_pskb(struct sock *sk, long unsigned int header_len, long unsigned int data_len, int noblock, int *errcode, int max_page_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819259f0)
Location: net/core/sock.c:2217
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/sock.c:sock_alloc_send_skb
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff819259f0-ffffffff81925c05: sock_alloc_send_pskb (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
