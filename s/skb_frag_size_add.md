# Function: <code>skb_frag_size_add</code>

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
In net/core/skbuff.c (ffffffff81704dc1)
Location: include/linux/skbuff.h:249
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff8175d6a4)
Location: include/linux/skbuff.h:249
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817694d8)
Location: include/linux/skbuff.h:249
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff817c5d51)
Location: include/linux/skbuff.h:249
Inline: True
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
In net/core/skbuff.c (ffffffff817722e7)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/ipv4/ip_output.c (ffffffff817c8b63)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817d6350)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81832e63)
Location: include/linux/skbuff.h:335
Inline: True
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
In net/core/skbuff.c (ffffffff8179f3e7)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/ipv4/ip_output.c (ffffffff817f874a)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81806336)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff818648f4)
Location: include/linux/skbuff.h:335
Inline: True
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
In net/core/skbuff.c (ffffffff817b9248)
Location: include/linux/skbuff.h:338
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/ipv4/ip_output.c (ffffffff81818cde)
Location: include/linux/skbuff.h:338
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81826ef1)
Location: include/linux/skbuff.h:338
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81888106)
Location: include/linux/skbuff.h:338
Inline: True
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
In net/core/skbuff.c (ffffffff818320be)
Location: include/linux/skbuff.h:338
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/ipv4/ip_output.c (ffffffff81898d4f)
Location: include/linux/skbuff.h:338
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818a4e2b)
Location: include/linux/skbuff.h:338
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff8190a54d)
Location: include/linux/skbuff.h:338
Inline: True
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
In net/core/skbuff.c (ffffffff8187c25e)
Location: include/linux/skbuff.h:338
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/ipv4/ip_output.c (ffffffff818ecdf1)
Location: include/linux/skbuff.h:338
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818fa94a)
Location: include/linux/skbuff.h:338
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff819618fe)
Location: include/linux/skbuff.h:338
Inline: True
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
In net/core/skbuff.c (ffffffff8189ccfb)
Location: include/linux/skbuff.h:340
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/ipv4/ip_output.c (ffffffff8191a64a)
Location: include/linux/skbuff.h:340
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81928819)
Location: include/linux/skbuff.h:340
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81996255)
Location: include/linux/skbuff.h:340
Inline: True
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
In net/core/skbuff.c (ffffffff818e78a9)
Location: include/linux/skbuff.h:350
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/ipv4/ip_output.c (ffffffff8197c85b)
Location: include/linux/skbuff.h:350
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8198b782)
Location: include/linux/skbuff.h:350
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81a026c6)
Location: include/linux/skbuff.h:350
Inline: True
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
In net/core/skbuff.c (ffffffff81919c89)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/ipv4/ip_output.c (ffffffff819b31fb)
Location: include/linux/skbuff.h:345
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819c1fd8)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81a3929e)
Location: include/linux/skbuff.h:345
Inline: True
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
In net/core/skbuff.c (ffffffff819ec700)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/ipv4/ip_output.c (ffffffff81a9d1c2)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aad78d)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81b2e9a1)
Location: include/linux/skbuff.h:345
Inline: True
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
In net/core/skbuff.c (ffffffff819ec1b0)
Location: include/linux/skbuff.h:347
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/core/datagram.c (ffffffff819f4f11)
Location: include/linux/skbuff.h:347
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81aa7082)
Location: include/linux/skbuff.h:347
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ab4b04)
Location: include/linux/skbuff.h:347
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81b3d3f1)
Location: include/linux/skbuff.h:347
Inline: True
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
In net/core/skbuff.c (ffffffff819d26a6)
Location: include/linux/skbuff.h:348
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/core/datagram.c (ffffffff819db099)
Location: include/linux/skbuff.h:348
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81a92203)
Location: include/linux/skbuff.h:348
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81a9fcb0)
Location: include/linux/skbuff.h:348
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81b2a877)
Location: include/linux/skbuff.h:348
Inline: True
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
In net/core/skbuff.c (ffffffff81a82575)
Location: include/linux/skbuff.h:352
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/core/datagram.c (ffffffff81a8b745)
Location: include/linux/skbuff.h:352
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81b4d612)
Location: include/linux/skbuff.h:352
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81b5ba69)
Location: include/linux/skbuff.h:352
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81bf0978)
Location: include/linux/skbuff.h:352
Inline: True
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
In net/core/skbuff.c (ffffffff81bf6f24)
Location: include/linux/skbuff.h:563
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/core/datagram.c (ffffffff81c00d7e)
Location: include/linux/skbuff.h:563
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81c3f669)
Location: include/linux/skbuff.h:563
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
```
```
In net/ipv4/ip_output.c (ffffffff81cdadf1)
Location: include/linux/skbuff.h:563
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ceaa23)
Location: include/linux/skbuff.h:563
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81d89048)
Location: include/linux/skbuff.h:563
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81e1f0ad)
Location: include/linux/skbuff.h:563
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In net/core/skbuff.c (ffffffff81da5c86)
Location: include/linux/skbuff.h:386
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/core/datagram.c (ffffffff81db01ac)
Location: include/linux/skbuff.h:386
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81df3b79)
Location: include/linux/skbuff.h:386
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
```
```
In net/ipv4/ip_output.c (ffffffff81e9b61b)
Location: include/linux/skbuff.h:386
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81eaebda)
Location: include/linux/skbuff.h:386
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81f56e7d)
Location: include/linux/skbuff.h:386
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81ff5c66)
Location: include/linux/skbuff.h:386
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In net/core/skbuff.c (ffffffff81e1493f)
Location: include/linux/skbuff.h:389
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/core/datagram.c (ffffffff81e2049c)
Location: include/linux/skbuff.h:389
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81e6356b)
Location: include/linux/skbuff.h:389
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
```
```
In net/ipv4/ip_output.c (ffffffff81efa201)
Location: include/linux/skbuff.h:389
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81f0cc96)
Location: include/linux/skbuff.h:389
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81f22932)
Location: include/linux/skbuff.h:389
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv6/ip6_output.c (ffffffff81fb68fc)
Location: include/linux/skbuff.h:389
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82071d63)
Location: include/linux/skbuff.h:389
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In net/core/skbuff.c (ffffffff81ed1f3f)
Location: include/linux/skbuff.h:388
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/core/datagram.c (ffffffff81ede376)
Location: include/linux/skbuff.h:388
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81f27c9f)
Location: include/linux/skbuff.h:388
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
```
```
In net/ipv4/ip_output.c (ffffffff81fbe12f)
Location: include/linux/skbuff.h:388
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81fd0d8e)
Location: include/linux/skbuff.h:388
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81fe6322)
Location: include/linux/skbuff.h:388
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv6/ip6_output.c (ffffffff820841e6)
Location: include/linux/skbuff.h:388
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82145f86)
Location: include/linux/skbuff.h:388
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In net/core/skbuff.c (ffff800010bb42c8)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/ipv4/ip_output.c (ffff800010c62bfc)
Location: include/linux/skbuff.h:345
Inline: True
```
```
In net/ipv4/tcp.c (ffff800010c74cec)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffff800010cf9264)
Location: include/linux/skbuff.h:345
Inline: True
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
In net/core/skbuff.c (c0cd1c3c)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/ipv4/ip_output.c (c0d7357c)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (c0d8347c)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (c0e00a00)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
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
In net/core/skbuff.c (c000000000c8a89c)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/ipv4/ip_output.c (c000000000d67848)
Location: include/linux/skbuff.h:345
Inline: True
```
```
In net/ipv4/tcp.c (c000000000d7c2bc)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (c000000000e20e68)
Location: include/linux/skbuff.h:345
Inline: True
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
In net/core/skbuff.c (ffffffe00074493c)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/ipv4/ip_output.c (ffffffe0007cb5d8)
Location: include/linux/skbuff.h:345
Inline: True
```
```
In net/ipv4/tcp.c (ffffffe0007d816c)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffe000845064)
Location: include/linux/skbuff.h:345
Inline: True
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
In net/core/skbuff.c (ffffffff818b9c89)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/ipv4/ip_output.c (ffffffff8195306b)
Location: include/linux/skbuff.h:345
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81961e48)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff819d892e)
Location: include/linux/skbuff.h:345
Inline: True
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
In net/core/skbuff.c (ffffffff81873bd9)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/ipv4/ip_output.c (ffffffff8190cb5b)
Location: include/linux/skbuff.h:345
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8191b938)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff819956ee)
Location: include/linux/skbuff.h:345
Inline: True
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
In net/core/skbuff.c (ffffffff8190ac89)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/ipv4/ip_output.c (ffffffff819bd83b)
Location: include/linux/skbuff.h:345
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819cc618)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81a433ae)
Location: include/linux/skbuff.h:345
Inline: True
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
In net/core/skbuff.c (ffffffff8192bd89)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_coalesce_rx_frag
```
```
In net/ipv4/ip_output.c (ffffffff819c714b)
Location: include/linux/skbuff.h:345
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819d61a8)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81a4f04e)
Location: include/linux/skbuff.h:345
Inline: True
```
</details>
</li>
</ul>

## Differences
