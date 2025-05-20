# Function: <code>sk_filter_trim_cap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179b720)
Location: net/core/filter.c:68
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff8179b720-ffffffff8179b963: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ca8c0)
Location: net/core/filter.c:69
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_filter
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
**Symbols:**

```
ffffffff817ca8c0-ffffffff817cab26: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e9a70)
Location: net/core/filter.c:72
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_filter
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
**Symbols:**

```
ffffffff817e9a70-ffffffff817e9c18: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818650e0)
Location: net/core/filter.c:74
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_filter
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
**Symbols:**

```
ffffffff818650e0-ffffffff8186528d: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b2c00)
Location: net/core/filter.c:85
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_filter
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
**Symbols:**

```
ffffffff818b2c00-ffffffff818b2db0: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d5b30)
Location: net/core/filter.c:90
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff818d5b30-ffffffff818d5cd1: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819232c0)
Location: net/core/filter.c:90
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff819232c0-ffffffff819234d8: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819554f0)
Location: net/core/filter.c:90
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff819554f0-ffffffff81955707: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2bac0)
Location: net/core/filter.c:90
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81a2bac0-ffffffff81a2bbd4: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2d050)
Location: net/core/filter.c:120
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81a2d050-ffffffff81a2d17e: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a140a0)
Location: net/core/filter.c:120
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81a140a0-ffffffff81a142cb: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac5970)
Location: net/core/filter.c:121
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81ac5970-ffffffff81ac5b9a: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3c980)
Location: net/core/filter.c:122
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb_reason
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81c3c980-ffffffff81c3cacd: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfa370)
Location: net/core/filter.c:124
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb_reason
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81dfa370-ffffffff81dfa4c3: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6b710)
Location: net/core/filter.c:124
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb_reason
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81e6b710-ffffffff81e6b877: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2a8c0)
Location: net/core/filter.c:129
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb_reason
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81f2a8c0-ffffffff81f2aa27: sk_filter_trim_cap (STB_GLOBAL)
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
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010c01fe8)
Location: net/core/filter.c:90
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffff800010c01fe8-ffff800010c02208: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d103d4)
Location: net/core/filter.c:90
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
c0d103d4-c0d10674: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cdcd80)
Location: net/core/filter.c:90
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
c000000000cdcd80-c000000000cdd064: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe000778532)
Location: net/core/filter.c:90
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffe000778532-ffffffe000778702: sk_filter_trim_cap (STB_GLOBAL)
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
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f54c0)
Location: net/core/filter.c:90
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff818f54c0-ffffffff818f56d7: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818af2f0)
Location: net/core/filter.c:90
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff818af2f0-ffffffff818af507: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819464f0)
Location: net/core/filter.c:90
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff819464f0-ffffffff81946707: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock *sk, struct sk_buff *skb, unsigned int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81967de0)
Location: net/core/filter.c:90
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:sock_queue_rcv_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81967de0-ffffffff81968013: sk_filter_trim_cap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
