# Function: <code>sock_zerocopy_get</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81837e63)
Location: include/linux/skbuff.h:473
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187eef1)
Location: include/linux/skbuff.h:476
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
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
In net/core/skbuff.c (ffffffff8189fce1)
Location: include/linux/skbuff.h:478
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (ffffffff8191ab5f)
Location: include/linux/skbuff.h:478
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81996817)
Location: include/linux/skbuff.h:478
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
In net/core/skbuff.c (ffffffff818ea702)
Location: include/linux/skbuff.h:497
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (ffffffff8197ca63)
Location: include/linux/skbuff.h:497
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8199b311)
Location: include/linux/skbuff.h:497
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81a02e57)
Location: include/linux/skbuff.h:497
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
In net/core/skbuff.c (ffffffff8191c872)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (ffffffff819b3403)
Location: include/linux/skbuff.h:492
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819d1d51)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81a39a2c)
Location: include/linux/skbuff.h:492
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
In net/core/skbuff.c (ffffffff819eeac1)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (ffffffff81a9d7d1)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81abec2d)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81b2ece6)
Location: include/linux/skbuff.h:492
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
In net/core/skbuff.c (ffffffff819ee761)
Location: include/linux/skbuff.h:494
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (ffffffff81aa768d)
Location: include/linux/skbuff.h:494
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81aca58d)
Location: include/linux/skbuff.h:494
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81b3d736)
Location: include/linux/skbuff.h:494
Inline: True
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
In net/core/skbuff.c (ffff800010bb6e4c)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (ffff800010c62df4)
Location: include/linux/skbuff.h:492
Inline: True
```
```
In net/ipv4/tcp_output.c (ffff800010c84900)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffff800010cf94d0)
Location: include/linux/skbuff.h:492
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
In net/core/skbuff.c (c0cd3c94)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (c0d73b14)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (c0d93bf4)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (c0e010c4)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
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
In net/core/skbuff.c (c000000000c8e890)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (c000000000d67e34)
Location: include/linux/skbuff.h:492
Inline: True
```
```
In net/ipv4/tcp_output.c (c000000000d907c0)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (c000000000e21750)
Location: include/linux/skbuff.h:492
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
In net/core/skbuff.c (ffffffe000746a7e)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (ffffffe0007cbaac)
Location: include/linux/skbuff.h:492
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffe0007e6334)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffe000845624)
Location: include/linux/skbuff.h:492
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
In net/core/skbuff.c (ffffffff818bc872)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (ffffffff81953273)
Location: include/linux/skbuff.h:492
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81971bc1)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff819d90bc)
Location: include/linux/skbuff.h:492
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
In net/core/skbuff.c (ffffffff818767b2)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (ffffffff8190cd63)
Location: include/linux/skbuff.h:492
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8192b691)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81995e7c)
Location: include/linux/skbuff.h:492
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
In net/core/skbuff.c (ffffffff8190d872)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (ffffffff819bda43)
Location: include/linux/skbuff.h:492
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819dc391)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81a43b3c)
Location: include/linux/skbuff.h:492
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
In net/core/skbuff.c (ffffffff8192e9a2)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (ffffffff819c7353)
Location: include/linux/skbuff.h:492
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819e6011)
Location: include/linux/skbuff.h:492
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81a4f7dc)
Location: include/linux/skbuff.h:492
Inline: True
```
</details>
</li>
</ul>

## Differences
