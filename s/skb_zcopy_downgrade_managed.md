# Function: <code>skb_zcopy_downgrade_managed</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff817958e5)
Location: include/linux/skbuff.h:1735
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter_iovec
```
```
In net/core/skbuff.c (ffffffff81da5bea)
Location: include/linux/skbuff.h:1735
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/ipv4/ip_output.c (ffffffff81e9b502)
Location: include/linux/skbuff.h:1735
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81eaee2e)
Location: include/linux/skbuff.h:1735
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81f56d69)
Location: include/linux/skbuff.h:1735
Inline: True
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
In io_uring/net.c (ffffffff817d64c5)
Location: include/linux/skbuff.h:1764
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter_iovec
```
```
In net/core/skbuff.c (ffffffff81e14873)
Location: include/linux/skbuff.h:1764
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/ipv4/ip_output.c (ffffffff81efa0bc)
Location: include/linux/skbuff.h:1764
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81f0d07d)
Location: include/linux/skbuff.h:1764
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81fb67c0)
Location: include/linux/skbuff.h:1764
Inline: True
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
In io_uring/net.c (ffffffff8181a375)
Location: include/linux/skbuff.h:1771
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter_iovec
```
```
In net/core/skbuff.c (ffffffff81ed1e73)
Location: include/linux/skbuff.h:1771
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/ipv4/ip_output.c (ffffffff81fbdfea)
Location: include/linux/skbuff.h:1771
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81fd117d)
Location: include/linux/skbuff.h:1771
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff820840aa)
Location: include/linux/skbuff.h:1771
Inline: True
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
