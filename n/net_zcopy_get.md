# Function: <code>net_zcopy_get</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d415f)
Location: include/linux/skbuff.h:1453
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (ffffffff81a92871)
Location: include/linux/skbuff.h:1453
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ab540c)
Location: include/linux/skbuff.h:1453
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81b2abcb)
Location: include/linux/skbuff.h:1453
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
In net/core/skbuff.c (ffffffff81a83e7f)
Location: include/linux/skbuff.h:1466
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (ffffffff81b4dc75)
Location: include/linux/skbuff.h:1466
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81b72404)
Location: include/linux/skbuff.h:1466
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81bf0cb5)
Location: include/linux/skbuff.h:1466
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
In net/core/skbuff.c (ffffffff81bf983b)
Location: include/linux/skbuff.h:1815
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (ffffffff81cdb872)
Location: include/linux/skbuff.h:1815
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81d01b78)
Location: include/linux/skbuff.h:1815
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81d89c5b)
Location: include/linux/skbuff.h:1815
Inline: True
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
In net/core/skbuff.c (ffffffff81da868b)
Location: include/linux/skbuff.h:1665
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (ffffffff81e9c222)
Location: include/linux/skbuff.h:1665
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81eaec34)
Location: include/linux/skbuff.h:1665
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81ec6ce8)
Location: include/linux/skbuff.h:1665
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81f57c4e)
Location: include/linux/skbuff.h:1665
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
In net/core/skbuff.c (ffffffff81e1732b)
Location: include/linux/skbuff.h:1694
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (ffffffff81efacf4)
Location: include/linux/skbuff.h:1694
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81f254ef)
Location: include/linux/skbuff.h:1694
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81fb7741)
Location: include/linux/skbuff.h:1694
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
In net/core/skbuff.c (ffffffff81ed472b)
Location: include/linux/skbuff.h:1701
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/ipv4/ip_output.c (ffffffff81fbebee)
Location: include/linux/skbuff.h:1701
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9db1)
Location: include/linux/skbuff.h:1701
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff82083f81)
Location: include/linux/skbuff.h:1701
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
