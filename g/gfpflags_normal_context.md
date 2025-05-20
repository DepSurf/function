# Function: <code>gfpflags_normal_context</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
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
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/core/skmsg.c (ffffffff81968545)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff819b3b0c)
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819c1ca7)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81a39d3e)
Location: include/linux/gfp.h:345
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
Location: include/linux/gfp.h:352
Inline: True
Inline callers:
  - net/core/skbuff.c:linear_to_page
```
```
In net/core/skmsg.c (ffffffff81a3c0d5)
Location: include/linux/gfp.h:352
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81a9dc0b)
Location: include/linux/gfp.h:352
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81aad651)
Location: include/linux/gfp.h:352
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f56d)
Location: include/linux/gfp.h:352
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/mptcp/protocol.c (ffffffff81bacf2a)
Location: include/linux/gfp.h:352
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
Location: include/linux/gfp.h:354
Inline: True
Inline callers:
  - net/core/skbuff.c:linear_to_page
```
```
In net/core/skmsg.c (ffffffff81a3e795)
Location: include/linux/gfp.h:354
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81aa7adb)
Location: include/linux/gfp.h:354
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81ab49c8)
Location: include/linux/gfp.h:354
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81b3dfbd)
Location: include/linux/gfp.h:354
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/mptcp/protocol.c (ffffffff81bbf934)
Location: include/linux/gfp.h:354
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
Location: include/linux/gfp.h:368
Inline: True
```
```
In net/core/skmsg.c (ffffffff81a4c995)
Location: include/linux/gfp.h:368
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81a92ccb)
Location: include/linux/gfp.h:368
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81a9fb78)
Location: include/linux/gfp.h:368
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b46d)
Location: include/linux/gfp.h:368
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/mptcp/protocol.c (ffffffff81baf4fd)
Location: include/linux/gfp.h:368
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/core/skmsg.c (ffff800010c0f008)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffff800010c63488)
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/ipv4/tcp.c (ffff800010c74ba0)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffff800010cf9c48)
Location: include/linux/gfp.h:345
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
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/core/skmsg.c (c0d26a98)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (c0d73e74)
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/ipv4/tcp.c (c0d83314)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (c0e0148c)
Location: include/linux/gfp.h:345
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
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/core/skmsg.c (c000000000cfa1e8)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (c000000000d682a0)
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/ipv4/tcp.c (c000000000d7bf34)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (c000000000e21eb4)
Location: include/linux/gfp.h:345
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
In net/core/skbuff.c (ffffffe0007441a0)
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/core/skmsg.c (ffffffe00078b11e)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffe0007cbce8)
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/ipv4/tcp.c (ffffffe0007d7eb8)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffe0008458b6)
Location: include/linux/gfp.h:345
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
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/core/skmsg.c (ffffffff81908515)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff8195397c)
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81961b17)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff819d93ce)
Location: include/linux/gfp.h:345
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
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/core/skmsg.c (ffffffff818c2325)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff8190d46c)
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8191b607)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff8199618e)
Location: include/linux/gfp.h:345
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
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/core/skmsg.c (ffffffff81959545)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff819be14c)
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819cc2e7)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81a43e4e)
Location: include/linux/gfp.h:345
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
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/core/skmsg.c (ffffffff8197b715)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff819c7a5c)
Location: include/linux/gfp.h:345
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819d5e77)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81a4faee)
Location: include/linux/gfp.h:345
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
</details>
</li>
</ul>

## Differences
