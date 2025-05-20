# Function: <code>skb_sk_is_prefetched</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81a97fdd)
Location: include/net/sock.h:2537
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8673)
Location: include/net/sock.h:2537
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81ad7589)
Location: include/net/sock.h:2537
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81b3129b)
Location: include/net/sock.h:2537
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81b5ac01)
Location: include/net/sock.h:2537
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a29f)
Location: include/net/sock.h:2537
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ip_input.c (ffffffff81aa1f3d)
Location: include/net/sock.h:2558
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4613)
Location: include/net/sock.h:2558
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81ae3bd9)
Location: include/net/sock.h:2558
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81b3fec0)
Location: include/net/sock.h:2558
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81b69395)
Location: include/net/sock.h:2558
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78d65)
Location: include/net/sock.h:2558
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ip_input.c (ffffffff81a8ce68)
Location: include/net/sock.h:2594
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf74c)
Location: include/net/sock.h:2594
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81acedc9)
Location: include/net/sock.h:2594
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81b2dce7)
Location: include/net/sock.h:2594
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81b57695)
Location: include/net/sock.h:2594
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67889)
Location: include/net/sock.h:2594
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/netfilter/nf_queue.c (ffffffff81b3f0ef)
Location: include/net/sock.h:2653
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_input.c (ffffffff81b47fb8)
Location: include/net/sock.h:2653
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d2ad)
Location: include/net/sock.h:2653
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81b8d7b9)
Location: include/net/sock.h:2653
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81bf3f7a)
Location: include/net/sock.h:2653
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81c1ecb1)
Location: include/net/sock.h:2653
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f56c)
Location: include/net/sock.h:2653
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/netfilter/nf_queue.c (ffffffff81ccb832)
Location: include/net/sock.h:2763
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_input.c (ffffffff81cd524f)
Location: include/net/sock.h:2763
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d18c)
Location: include/net/sock.h:2763
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81d1e91c)
Location: include/net/sock.h:2763
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81d8cc16)
Location: include/net/sock.h:2763
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81dbb50f)
Location: include/net/sock.h:2763
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc8fe)
Location: include/net/sock.h:2763
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/netfilter/nf_queue.c (ffffffff81e8b682)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_input.c (ffffffff81e9571f)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2c07)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81ee5a4a)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81f5ae26)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81f8b64f)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9da44)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/netfilter/nf_queue.c (ffffffff81ee96d2)
Location: include/net/sock.h:2797
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_input.c (ffffffff81ef3f27)
Location: include/net/sock.h:2797
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f318ee)
Location: include/net/sock.h:2797
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81f45239)
Location: include/net/sock.h:2797
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81fbabd6)
Location: include/net/sock.h:2797
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81febd33)
Location: include/net/sock.h:2797
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe4c6)
Location: include/net/sock.h:2797
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/netfilter/nf_queue.c (ffffffff81fad442)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_input.c (ffffffff81fb7eba)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff4d24)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__inet_lookup_skb
```
```
In net/ipv4/udp.c (ffffffff8200b2af)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff82088006)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff820b75ad)
Location: include/net/sock.h:2809
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c922a)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:__inet6_lookup_skb
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
