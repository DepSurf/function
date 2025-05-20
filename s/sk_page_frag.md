# Function: <code>sk_page_frag</code>

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
In net/core/skbuff.c (ffffffff8170841e)
Location: include/net/sock.h:2063
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8175de0c)
Location: include/net/sock.h:2063
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81769771)
Location: include/net/sock.h:2063
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff817c6789)
Location: include/net/sock.h:2063
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
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
In net/core/skbuff.c (ffffffff8176fa83)
Location: include/net/sock.h:2036
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817c929c)
Location: include/net/sock.h:2036
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817d60c9)
Location: include/net/sock.h:2036
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff8183388e)
Location: include/net/sock.h:2036
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
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
In net/core/skbuff.c (ffffffff8179cbdb)
Location: include/net/sock.h:2102
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817f8e3c)
Location: include/net/sock.h:2102
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818060e1)
Location: include/net/sock.h:2102
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff8186530e)
Location: include/net/sock.h:2102
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
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
In net/core/skbuff.c (ffffffff817b8cbb)
Location: include/net/sock.h:2126
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8181926c)
Location: include/net/sock.h:2126
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81826579)
Location: include/net/sock.h:2126
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81889b0d)
Location: include/net/sock.h:2126
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
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
In net/core/skbuff.c (ffffffff81831719)
Location: include/net/sock.h:2140
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff818992ac)
Location: include/net/sock.h:2140
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818a4792)
Location: include/net/sock.h:2140
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff8190acdd)
Location: include/net/sock.h:2140
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
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
In net/core/sock.c (ffffffff8187738d)
Location: include/net/sock.h:2143
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc_sg
```
```
In net/core/skbuff.c (ffffffff8187bc0a)
Location: include/net/sock.h:2143
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff818ed47c)
Location: include/net/sock.h:2143
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818fa5b3)
Location: include/net/sock.h:2143
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff819621b6)
Location: include/net/sock.h:2143
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
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
In net/core/skbuff.c (ffffffff8189cafa)
Location: include/net/sock.h:2233
Inline: True
```
```
In net/core/skmsg.c (ffffffff818e6045)
Location: include/net/sock.h:2233
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff8191aebc)
Location: include/net/sock.h:2233
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819284ea)
Location: include/net/sock.h:2233
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81996bf6)
Location: include/net/sock.h:2233
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
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
In net/core/skbuff.c (ffffffff818e7295)
Location: include/net/sock.h:2239
Inline: True
```
```
In net/core/skmsg.c (ffffffff81935785)
Location: include/net/sock.h:2239
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff8197d16c)
Location: include/net/sock.h:2239
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8198b44d)
Location: include/net/sock.h:2239
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81a0316e)
Location: include/net/sock.h:2239
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
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
In net/core/skbuff.c (ffffffff81919699)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/core/skmsg.c (ffffffff81968545)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff819b3b0c)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819c1ca7)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81a39d3e)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
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
In net/core/skbuff.c (ffffffff819ea115)
Location: include/net/sock.h:2310
Inline: True
Inline callers:
  - net/core/skbuff.c:linear_to_page
```
```
In net/core/skmsg.c (ffffffff81a3c0d5)
Location: include/net/sock.h:2310
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81a9dc0b)
Location: include/net/sock.h:2310
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81aad651)
Location: include/net/sock.h:2310
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f56d)
Location: include/net/sock.h:2310
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/mptcp/protocol.c (ffffffff81bacf2a)
Location: include/net/sock.h:2310
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/core/skbuff.c (ffffffff819e9e45)
Location: include/net/sock.h:2331
Inline: True
Inline callers:
  - net/core/skbuff.c:linear_to_page
```
```
In net/core/skmsg.c (ffffffff81a3e795)
Location: include/net/sock.h:2331
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81aa7adb)
Location: include/net/sock.h:2331
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81ab49c8)
Location: include/net/sock.h:2331
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81b3dfbd)
Location: include/net/sock.h:2331
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/mptcp/protocol.c (ffffffff81bbf934)
Location: include/net/sock.h:2331
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/core/skbuff.c (ffffffff819d2076)
Location: include/net/sock.h:2367
Inline: True
```
```
In net/core/skmsg.c (ffffffff81a4c995)
Location: include/net/sock.h:2367
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81a92ccb)
Location: include/net/sock.h:2367
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81a9fb78)
Location: include/net/sock.h:2367
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b46d)
Location: include/net/sock.h:2367
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/mptcp/protocol.c (ffffffff81baf4fd)
Location: include/net/sock.h:2367
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/core/skbuff.c (ffffffff81a81cf6)
Location: include/net/sock.h:2420
Inline: True
```
```
In net/core/skmsg.c (ffffffff81b052d5)
Location: include/net/sock.h:2420
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81b4e0cb)
Location: include/net/sock.h:2420
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81b5b931)
Location: include/net/sock.h:2420
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81bf159f)
Location: include/net/sock.h:2420
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/mptcp/protocol.c (ffffffff81c7d1e0)
Location: include/net/sock.h:2420
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/core/skbuff.c (ffffffff81bf6988)
Location: include/net/sock.h:2543
Inline: True
```
```
In net/core/skmsg.c (ffffffff81c8c615)
Location: include/net/sock.h:2543
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81cdb96b)
Location: include/net/sock.h:2543
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81cea8a4)
Location: include/net/sock.h:2543
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81d89dff)
Location: include/net/sock.h:2543
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/mptcp/protocol.c (ffffffff81e2281f)
Location: include/net/sock.h:2543
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/core/skbuff.c (ffffffff81da5198)
Location: include/net/sock.h:2590
Inline: True
```
```
In net/core/skmsg.c (ffffffff81e468a5)
Location: include/net/sock.h:2590
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81e9c30f)
Location: include/net/sock.h:2590
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81eae878)
Location: include/net/sock.h:2590
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81f57da8)
Location: include/net/sock.h:2590
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/mptcp/protocol.c (ffffffff81ffb53a)
Location: include/net/sock.h:2590
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/core/skbuff.c (ffffffff81e141cd)
Location: include/net/sock.h:2578
Inline: True
```
```
In net/core/skmsg.c (ffffffff81ea22f5)
Location: include/net/sock.h:2578
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81efaeef)
Location: include/net/sock.h:2578
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81f0caf3)
Location: include/net/sock.h:2578
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81f2511b)
Location: include/net/sock.h:2578
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81fb795d)
Location: include/net/sock.h:2578
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/mptcp/protocol.c (ffffffff820778c3)
Location: include/net/sock.h:2578
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/core/skbuff.c (ffffffff81ed158d)
Location: include/net/sock.h:2568
Inline: True
```
```
In net/core/skmsg.c (ffffffff81f648e5)
Location: include/net/sock.h:2568
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81fbedef)
Location: include/net/sock.h:2568
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81fd0be3)
Location: include/net/sock.h:2568
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81fe99fb)
Location: include/net/sock.h:2568
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff82084f8d)
Location: include/net/sock.h:2568
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/mptcp/protocol.c (ffffffff8214c922)
Location: include/net/sock.h:2568
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/core/skbuff.c (ffff800010bb3298)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/core/skmsg.c (ffff800010c0f008)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffff800010c63488)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/ipv4/tcp.c (ffff800010c74ba0)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffff800010cf9c48)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
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
In net/core/skbuff.c (c0cd17a8)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/core/skmsg.c (c0d26a98)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (c0d73e74)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/ipv4/tcp.c (c0d83314)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (c0e0148c)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
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
In net/core/skbuff.c (c000000000c89e4c)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/core/skmsg.c (c000000000cfa1e8)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (c000000000d682a0)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/ipv4/tcp.c (c000000000d7bf34)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (c000000000e21eb4)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
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
In net/core/skbuff.c (ffffffe00074418e)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/core/skmsg.c (ffffffe00078b11e)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffe0007cbce8)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/ipv4/tcp.c (ffffffe0007d7d5e)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffe0008458b6)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
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
In net/core/skbuff.c (ffffffff818b9699)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/core/skmsg.c (ffffffff81908515)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff8195397c)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81961b17)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff819d93ce)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
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
In net/core/skbuff.c (ffffffff818735e9)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/core/skmsg.c (ffffffff818c2325)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff8190d46c)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8191b607)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff8199618e)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
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
In net/core/skbuff.c (ffffffff8190a699)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/core/skmsg.c (ffffffff81959545)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff819be14c)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819cc2e7)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81a43e4e)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
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
In net/core/skbuff.c (ffffffff8192b799)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/core/skmsg.c (ffffffff8197b715)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff819c7a5c)
Location: include/net/sock.h:2258
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819d5e77)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81a4faee)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
</details>
</li>
</ul>

## Differences
