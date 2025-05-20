# Function: <code>__skb_mark_checksum_bad</code>

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
In net/ipv4/tcp_offload.c (ffffffff81783b2a)
Location: include/linux/skbuff.h:3115
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8178b69d)
Location: include/linux/skbuff.h:3115
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff817a4f2f)
Location: include/linux/skbuff.h:3115
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818013b3)
Location: include/linux/skbuff.h:3115
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81801a21)
Location: include/linux/skbuff.h:3115
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
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
In net/ipv4/tcp_offload.c (ffffffff817f10e1)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff817f8e1d)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81812fec)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81866d81)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872bf3)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/ipv4/tcp_offload.c (ffffffff81821e71)
Location: include/linux/skbuff.h:3374
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81829ced)
Location: include/linux/skbuff.h:3374
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff818444fc)
Location: include/linux/skbuff.h:3374
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81899481)
Location: include/linux/skbuff.h:3374
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a7213)
Location: include/linux/skbuff.h:3374
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
</details>
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
