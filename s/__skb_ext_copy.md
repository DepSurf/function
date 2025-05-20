# Function: <code>__skb_ext_copy</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189c011)
Location: include/linux/skbuff.h:3945
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81918fdb)
Location: include/linux/skbuff.h:3945
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff819958d8)
Location: include/linux/skbuff.h:3945
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff818e68bf)
Location: include/linux/skbuff.h:4052
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff8197b103)
Location: include/linux/skbuff.h:4052
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81a01190)
Location: include/linux/skbuff.h:4052
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff81918a07)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff819b1a73)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81a37d6c)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff819ec84e)
Location: include/linux/skbuff.h:4164
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81a9c2ad)
Location: include/linux/skbuff.h:4164
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81b2dd3a)
Location: include/linux/skbuff.h:4164
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff819ec50e)
Location: include/linux/skbuff.h:4193
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81aa610d)
Location: include/linux/skbuff.h:4193
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_output.c (ffffffff81acafb6)
Location: include/linux/skbuff.h:4193
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81b3c78a)
Location: include/linux/skbuff.h:4193
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff819d29fe)
Location: include/linux/skbuff.h:4257
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81a912cd)
Location: include/linux/skbuff.h:4257
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_output.c (ffffffff81ab5f9c)
Location: include/linux/skbuff.h:4257
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81b29bea)
Location: include/linux/skbuff.h:4257
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff81a82672)
Location: include/linux/skbuff.h:4295
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81b4c683)
Location: include/linux/skbuff.h:4295
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_output.c (ffffffff81b72fec)
Location: include/linux/skbuff.h:4295
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81bef7be)
Location: include/linux/skbuff.h:4295
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff81bf7066)
Location: include/linux/skbuff.h:4717
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81cd9d0d)
Location: include/linux/skbuff.h:4717
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_output.c (ffffffff81d02703)
Location: include/linux/skbuff.h:4717
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81d882dc)
Location: include/linux/skbuff.h:4717
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff81da5fd6)
Location: include/linux/skbuff.h:4613
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81e9a49d)
Location: include/linux/skbuff.h:4613
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_output.c (ffffffff81ec78e3)
Location: include/linux/skbuff.h:4613
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81f5608c)
Location: include/linux/skbuff.h:4613
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff81e150c0)
Location: include/linux/skbuff.h:4645
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81ef8df7)
Location: include/linux/skbuff.h:4645
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_output.c (ffffffff81f26798)
Location: include/linux/skbuff.h:4645
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81fb5a58)
Location: include/linux/skbuff.h:4645
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff81ed2460)
Location: include/linux/skbuff.h:4685
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81fbcd17)
Location: include/linux/skbuff.h:4685
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_output.c (ffffffff81feb178)
Location: include/linux/skbuff.h:4685
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff82083128)
Location: include/linux/skbuff.h:4685
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffff800010bb47cc)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffff800010c62438)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffff800010cf84e0)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (c0cd0584)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (c0d71c48)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (c0dffc4c)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (c000000000c87ac4)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (c000000000d65700)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (c000000000e204c0)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffe00074252e)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffe0007c9fca)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffe0008442b6)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff818b8a07)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff819518e3)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff819d73fc)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff81872957)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff8190b3d3)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff819941bc)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff81909a07)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff819bc0b3)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81a41e7c)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff8192ab07)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff819c59c3)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81a4db0c)
Location: include/linux/skbuff.h:4124
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
</details>
</li>
</ul>

## Differences
