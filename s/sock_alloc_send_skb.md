# Function: <code>sock_alloc_send_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81702800)
Location: net/core/sock.c:1885
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_send
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81702800-ffffffff8170281a: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81769a50)
Location: net/core/sock.c:1914
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81769a50-ffffffff81769a6a: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81796960)
Location: net/core/sock.c:1912
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81796960-ffffffff8179697a: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b4d30)
Location: net/core/sock.c:2051
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff817b4d30-ffffffff817b4d4a: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182cf70)
Location: net/core/sock.c:2089
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff8182cf70-ffffffff8182cf8a: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81876d70)
Location: net/core/sock.c:2109
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff81876d70-ffffffff81876d8a: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81897540)
Location: net/core/sock.c:2105
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff81897540-ffffffff8189755a: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e1980)
Location: net/core/sock.c:2246
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff818e1980-ffffffff818e199a: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81913b70)
Location: net/core/sock.c:2261
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffffffff81913b70-ffffffff81913b8a: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e6170)
Location: net/core/sock.c:2370
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff819e6170-ffffffff819e618a: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e5570)
Location: net/core/sock.c:2362
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff819e5570-ffffffff819e558a: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cb680)
Location: net/core/sock.c:2385
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
**Symbols:**

```
ffffffff819cb680-ffffffff819cb69a: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7ad10)
Location: net/core/sock.c:2509
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
**Symbols:**

```
ffffffff81a7ad10-ffffffff81a7ad2a: sock_alloc_send_skb (STB_GLOBAL)
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
In net/ipv4/ip_output.c (ffffffff81cdb366)
Location: include/net/sock.h:1859
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/raw.c (ffffffff81d167eb)
Location: include/net/sock.h:1859
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/unix/af_unix.c (ffffffff81d81693)
Location: include/net/sock.h:1859
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81d89881)
Location: include/net/sock.h:1859
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81dbd41a)
Location: include/net/sock.h:1859
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81dc2e1a)
Location: include/net/sock.h:1859
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/packet/af_packet.c (ffffffff81df6e7b)
Location: include/net/sock.h:1859
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/xdp/xsk.c (ffffffff81e181c7)
Location: include/net/sock.h:1859
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mctp/af_mctp.c (ffffffff81e3720b)
Location: include/net/sock.h:1859
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
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
In net/ipv4/ip_output.c (ffffffff81e9bc1a)
Location: include/net/sock.h:1884
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/raw.c (ffffffff81edcf9b)
Location: include/net/sock.h:1884
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/unix/af_unix.c (ffffffff81f4c748)
Location: include/net/sock.h:1884
Inline: True
Inline callers:
  - net/unix/af_unix.c:queue_oob
```
```
In net/ipv6/ip6_output.c (ffffffff81f5772e)
Location: include/net/sock.h:1884
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81f8d95a)
Location: include/net/sock.h:1884
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81f9386a)
Location: include/net/sock.h:1884
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/packet/af_packet.c (ffffffff81fcb496)
Location: include/net/sock.h:1884
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/xdp/xsk.c (ffffffff81fef377)
Location: include/net/sock.h:1884
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mctp/af_mctp.c (ffffffff8201004b)
Location: include/net/sock.h:1884
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
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
In net/ipv4/ip_output.c (ffffffff81efa6ec)
Location: include/net/sock.h:1875
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/raw.c (ffffffff81f3c1eb)
Location: include/net/sock.h:1875
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/unix/af_unix.c (ffffffff81fad814)
Location: include/net/sock.h:1875
Inline: True
Inline callers:
  - net/unix/af_unix.c:queue_oob
```
```
In net/ipv6/ip6_output.c (ffffffff81fb7213)
Location: include/net/sock.h:1875
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81fee136)
Location: include/net/sock.h:1875
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81ff41c9)
Location: include/net/sock.h:1875
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/packet/af_packet.c (ffffffff8202c783)
Location: include/net/sock.h:1875
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/xdp/xsk.c (ffffffff8206b374)
Location: include/net/sock.h:1875
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mctp/af_mctp.c (ffffffff8208cc76)
Location: include/net/sock.h:1875
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
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
In net/ipv4/ip_output.c (ffffffff81fbe626)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/raw.c (ffffffff82002315)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/unix/af_unix.c (ffffffff8207a0e4)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/unix/af_unix.c:queue_oob
```
```
In net/ipv6/ip6_output.c (ffffffff820848ad)
Location: include/net/sock.h:1851
Inline: True
```
```
In net/ipv6/raw.c (ffffffff820bbd0a)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff820c111a)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/packet/af_packet.c (ffffffff820fc21d)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/xdp/xsk.c (ffffffff8213ec71)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mctp/af_mctp.c (ffffffff82163143)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
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
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bab608)
Location: net/core/sock.c:2261
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffff800010bab608-ffff800010bab65c: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cca1c0)
Location: net/core/sock.c:2261
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
c0cca1c0-c0cca1f8: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c81f20)
Location: net/core/sock.c:2261
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
c000000000c81f20-c000000000c81f48: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073ee96)
Location: net/core/sock.c:2261
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffffffe00073ee96-ffffffe00073eedc: sock_alloc_send_skb (STB_GLOBAL)
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
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b3b70)
Location: net/core/sock.c:2261
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffffffff818b3b70-ffffffff818b3b8a: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186dac0)
Location: net/core/sock.c:2261
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffffffff8186dac0-ffffffff8186dada: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81904b70)
Location: net/core/sock.c:2261
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffffffff81904b70-ffffffff81904b8a: sock_alloc_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *sock_alloc_send_skb(struct sock *sk, long unsigned int size, int noblock, int *errcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81925c10)
Location: net/core/sock.c:2261
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81925c10-ffffffff81925c2a: sock_alloc_send_skb (STB_GLOBAL)
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
