# Function: <code>udp_v6_check</code>

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
In net/ipv6/ip6_checksum.c (ffffffff81800143)
Location: include/net/ip6_checksum.h:93
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/udp_offload.c (ffffffff818015fa)
Location: include/net/ip6_checksum.h:93
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In net/ipv6/udp_offload.c (ffffffff81866961)
Location: include/net/ip6_checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6_checksum.c (ffffffff818717de)
Location: include/net/ip6_checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff81899061)
Location: include/net/ip6_checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6_checksum.c (ffffffff818a5d3e)
Location: include/net/ip6_checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff818bf283)
Location: include/net/ip6_checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6_checksum.c (ffffffff818cc79e)
Location: include/net/ip6_checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff819423d3)
Location: include/net/ip6_checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6_checksum.c (ffffffff8195154e)
Location: include/net/ip6_checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff8199b202)
Location: include/net/ip6_checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6_checksum.c (ffffffff819aaafd)
Location: include/net/ip6_checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff819d1b4a)
Location: include/net/ip6_checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e15ed)
Location: include/net/ip6_checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff81a408fa)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a503ac)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff81a7757a)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a86fcc)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff81b71810)
Location: include/net/ip6_checksum.h:97
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b8227c)
Location: include/net/ip6_checksum.h:97
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff81b804b0)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b9196c)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff81b6f0b2)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80bc0)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff81c37172)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4cbe0)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff81dd4d1d)
Location: include/net/ip6_checksum.h:74
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6_checksum.c (ffffffff81ded022)
Location: include/net/ip6_checksum.h:74
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff81fa63dd)
Location: include/net/ip6_checksum.h:74
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc0e22)
Location: include/net/ip6_checksum.h:74
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff82006c5d)
Location: include/net/ip6_checksum.h:74
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6_checksum.c (ffffffff82021db1)
Location: include/net/ip6_checksum.h:74
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff820d5abd)
Location: include/net/ip6_checksum.h:74
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f0ed1)
Location: include/net/ip6_checksum.h:74
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffff800010d40bfc)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6_checksum.c (ffff800010d536f0)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (c0e435d8)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6_checksum.c (c0e53fe8)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (c000000000e75318)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6_checksum.c (c000000000e8bed8)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffe00087c430)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b3fc)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff81a16c0a)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a2665c)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff819d39ca)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e341c)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff81a8168a)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9220c)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv6/udp_offload.c (ffffffff81a8df8a)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e2bc)
Location: include/net/ip6_checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
</details>
</li>
</ul>

## Differences
