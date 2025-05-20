# Function: <code>skb_zcopy_init</code>

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
In drivers/net/tun.c (ffffffff8187e587)
Location: include/linux/skbuff.h:1458
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff819d4181)
Location: include/linux/skbuff.h:1458
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff81a928a4)
Location: include/linux/skbuff.h:1458
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ab542d)
Location: include/linux/skbuff.h:1458
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81b2abfd)
Location: include/linux/skbuff.h:1458
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
In drivers/net/tun.c (ffffffff8190fd94)
Location: include/linux/skbuff.h:1471
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81a83ea1)
Location: include/linux/skbuff.h:1471
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff81b4dc9a)
Location: include/linux/skbuff.h:1471
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81b72425)
Location: include/linux/skbuff.h:1471
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81bf0cda)
Location: include/linux/skbuff.h:1471
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
In drivers/net/tun.c (ffffffff81a669de)
Location: include/linux/skbuff.h:1820
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81bf9857)
Location: include/linux/skbuff.h:1820
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff81cdb88f)
Location: include/linux/skbuff.h:1820
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81d01b91)
Location: include/linux/skbuff.h:1820
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81d89c7c)
Location: include/linux/skbuff.h:1820
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
In drivers/net/tun.c (ffffffff81bf2304)
Location: include/linux/skbuff.h:1670
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81da86a7)
Location: include/linux/skbuff.h:1670
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff81e9c242)
Location: include/linux/skbuff.h:1670
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ec6d01)
Location: include/linux/skbuff.h:1670
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81f57c6e)
Location: include/linux/skbuff.h:1670
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
In drivers/net/tun.c (ffffffff81c4afe6)
Location: include/linux/skbuff.h:1699
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81e17347)
Location: include/linux/skbuff.h:1699
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff81efad14)
Location: include/linux/skbuff.h:1699
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81f25510)
Location: include/linux/skbuff.h:1699
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81fb7761)
Location: include/linux/skbuff.h:1699
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
In drivers/net/tun.c (ffffffff81d0091c)
Location: include/linux/skbuff.h:1706
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81ed4747)
Location: include/linux/skbuff.h:1706
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff81fbec12)
Location: include/linux/skbuff.h:1706
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9dd2)
Location: include/linux/skbuff.h:1706
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff82083fa9)
Location: include/linux/skbuff.h:1706
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
