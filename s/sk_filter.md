# Function: <code>sk_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sk_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81730a50)
Location: net/core/filter.c:66
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/sock.c:sock_queue_rcv_skb
  - net/core/sock.c:sk_receive_skb
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81730a50-ffffffff81730b9c: sk_filter (STB_GLOBAL)
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
In drivers/net/tun.c (ffffffff8164d450)
Location: include/linux/filter.h:488
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81768536)
Location: include/linux/filter.h:488
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff817b8025)
Location: include/linux/filter.h:488
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ebfcf)
Location: include/linux/filter.h:488
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/unix/af_unix.c (ffffffff8182ea6e)
Location: include/linux/filter.h:488
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860b77)
Location: include/linux/filter.h:488
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In drivers/net/tun.c (ffffffff8167f18b)
Location: include/linux/filter.h:569
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81795586)
Location: include/linux/filter.h:569
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff817e7b05)
Location: include/linux/filter.h:569
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff818604ee)
Location: include/linux/filter.h:569
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff816943cf)
Location: include/linux/filter.h:668
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff817b3b46)
Location: include/linux/filter.h:668
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff818077fa)
Location: include/linux/filter.h:668
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff81884be9)
Location: include/linux/filter.h:668
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff816fe497)
Location: include/linux/filter.h:673
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff8182d1f6)
Location: include/linux/filter.h:673
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff8188633f)
Location: include/linux/filter.h:673
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff81905db3)
Location: include/linux/filter.h:673
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff8173d554)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81876fd5)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff818d9cec)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff8195c882)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff8176100e)
Location: include/linux/filter.h:729
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81897775)
Location: include/linux/filter.h:729
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff819067f7)
Location: include/linux/filter.h:729
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff819918ac)
Location: include/linux/filter.h:729
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff8179ec8a)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff818e1b95)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff81967aa6)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff819fcaed)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff817c33d6)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81913d85)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff8199e536)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff81a3377d)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff8188e721)
Location: include/linux/filter.h:829
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff819e5ec5)
Location: include/linux/filter.h:829
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff81a7810a)
Location: include/linux/filter.h:829
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff81b28a99)
Location: include/linux/filter.h:829
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff8189d081)
Location: include/linux/filter.h:838
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff819e5998)
Location: include/linux/filter.h:838
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff81a80f04)
Location: include/linux/filter.h:838
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff81b36cd5)
Location: include/linux/filter.h:838
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff8187f8b1)
Location: include/linux/filter.h:881
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff819cbaa8)
Location: include/linux/filter.h:881
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff81a696bd)
Location: include/linux/filter.h:881
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff81b24886)
Location: include/linux/filter.h:881
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff81910a33)
Location: include/linux/filter.h:902
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81a7b168)
Location: include/linux/filter.h:902
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff81b22c79)
Location: include/linux/filter.h:902
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff81be98c6)
Location: include/linux/filter.h:902
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff81a6080a)
Location: include/linux/filter.h:896
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81bee7f3)
Location: include/linux/filter.h:896
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb_reason
```
```
In net/netlink/af_netlink.c (ffffffff81cab876)
Location: include/linux/filter.h:896
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff81d8238c)
Location: include/linux/filter.h:896
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff81becdc9)
Location: include/linux/filter.h:867
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81d9e2c3)
Location: include/linux/filter.h:867
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb_reason
```
```
In net/netlink/af_netlink.c (ffffffff81e68689)
Location: include/linux/filter.h:867
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff81f4f8c3)
Location: include/linux/filter.h:867
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff81c452ca)
Location: include/linux/filter.h:867
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81e0cb43)
Location: include/linux/filter.h:867
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb_reason
```
```
In net/netlink/af_netlink.c (ffffffff81ec44f9)
Location: include/linux/filter.h:867
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff81faf1b7)
Location: include/linux/filter.h:867
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff81cfabfd)
Location: include/linux/filter.h:901
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81ec94c3)
Location: include/linux/filter.h:901
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb_reason
```
```
In net/netlink/af_netlink.c (ffffffff81f878b9)
Location: include/linux/filter.h:901
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff8207c76b)
Location: include/linux/filter.h:901
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffff8000109dee4c)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffff800010bad254)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffff800010c4bb30)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffff800010cf3718)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (c0ac2a2c)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (c0cca52c)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (c0d5c3f8)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (c0dfa9bc)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (c000000000aa0770)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (c000000000c82684)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (c000000000d49ce0)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (c000000000e19770)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffe0006280ac)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffe00073f16a)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffe0007b9054)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffe0008400c6)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff81787ea6)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff818b3d85)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff8193e3a6)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff819d2e0d)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff817677f6)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff8186dcd5)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff818f7ea6)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff8198fbcd)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff817b8256)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81904d85)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff8198f536)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff81a3d88d)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In drivers/net/tun.c (ffffffff817d0540)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff81925e45)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff819b1e16)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/unix/af_unix.c (ffffffff81a4933d)
Location: include/linux/filter.h:794
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
