# Function: <code>skb_ext_copy</code>

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
In net/ipv4/ip_output.c (ffffffff81918fcf)
Location: include/linux/skbuff.h:3958
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff819958d0)
Location: include/linux/skbuff.h:3958
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
In net/ipv4/ip_output.c (ffffffff8197b0fb)
Location: include/linux/skbuff.h:4065
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81a01188)
Location: include/linux/skbuff.h:4065
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
In net/ipv4/ip_output.c (ffffffff819b1a6b)
Location: include/linux/skbuff.h:4137
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81a37d64)
Location: include/linux/skbuff.h:4137
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
In net/ipv4/ip_output.c (ffffffff81a9c2ab)
Location: include/linux/skbuff.h:4177
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81b2dd38)
Location: include/linux/skbuff.h:4177
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
In net/ipv4/ip_output.c (ffffffff81aa610b)
Location: include/linux/skbuff.h:4206
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_output.c (ffffffff81acafab)
Location: include/linux/skbuff.h:4206
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81b3c788)
Location: include/linux/skbuff.h:4206
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
In net/ipv4/ip_output.c (ffffffff81a912cb)
Location: include/linux/skbuff.h:4270
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_output.c (ffffffff81ab5f91)
Location: include/linux/skbuff.h:4270
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81b29be8)
Location: include/linux/skbuff.h:4270
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
In net/ipv4/ip_output.c (ffffffff81b4c681)
Location: include/linux/skbuff.h:4308
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_output.c (ffffffff81b72fe1)
Location: include/linux/skbuff.h:4308
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81bef7bc)
Location: include/linux/skbuff.h:4308
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
In net/ipv4/ip_output.c (ffffffff81cd9d07)
Location: include/linux/skbuff.h:4730
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_output.c (ffffffff81d026f8)
Location: include/linux/skbuff.h:4730
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81d882da)
Location: include/linux/skbuff.h:4730
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
In net/ipv4/ip_output.c (ffffffff81e9a497)
Location: include/linux/skbuff.h:4626
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_output.c (ffffffff81ec78d8)
Location: include/linux/skbuff.h:4626
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81f5608a)
Location: include/linux/skbuff.h:4626
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
In net/ipv4/ip_output.c (ffffffff81ef8df1)
Location: include/linux/skbuff.h:4658
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_output.c (ffffffff81f2678d)
Location: include/linux/skbuff.h:4658
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81fb5a56)
Location: include/linux/skbuff.h:4658
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
In net/ipv4/ip_output.c (ffffffff81fbcd11)
Location: include/linux/skbuff.h:4698
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_output.c (ffffffff81feb16d)
Location: include/linux/skbuff.h:4698
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff82083126)
Location: include/linux/skbuff.h:4698
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
In net/ipv4/ip_output.c (ffff800010c62430)
Location: include/linux/skbuff.h:4137
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffff800010cf84d8)
Location: include/linux/skbuff.h:4137
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
In net/ipv4/ip_output.c (c0d71c44)
Location: include/linux/skbuff.h:4137
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (c0dffc48)
Location: include/linux/skbuff.h:4137
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
In net/ipv4/ip_output.c (c000000000d656f8)
Location: include/linux/skbuff.h:4137
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (c000000000e204b8)
Location: include/linux/skbuff.h:4137
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
In net/ipv4/ip_output.c (ffffffe0007c9fb6)
Location: include/linux/skbuff.h:4137
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffe0008442a2)
Location: include/linux/skbuff.h:4137
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
In net/ipv4/ip_output.c (ffffffff819518db)
Location: include/linux/skbuff.h:4137
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff819d73f4)
Location: include/linux/skbuff.h:4137
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
In net/ipv4/ip_output.c (ffffffff8190b3cb)
Location: include/linux/skbuff.h:4137
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff819941b4)
Location: include/linux/skbuff.h:4137
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
In net/ipv4/ip_output.c (ffffffff819bc0ab)
Location: include/linux/skbuff.h:4137
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81a41e74)
Location: include/linux/skbuff.h:4137
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
In net/ipv4/ip_output.c (ffffffff819c59bb)
Location: include/linux/skbuff.h:4137
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81a4db04)
Location: include/linux/skbuff.h:4137
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
</details>
</li>
</ul>

## Differences
