# Function: <code>__udp6_lib_demux_lookup</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff818aa206)
Location: net/ipv6/udp.c:903
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff8192cc79)
Location: net/ipv6/udp.c:906
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
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
In net/ipv6/udp.c (ffffffff81985364)
Location: net/ipv6/udp.c:883
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819bbade)
Location: net/ipv6/udp.c:963
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a2a71e)
Location: net/ipv6/udp.c:950
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a6126e)
Location: net/ipv6/udp.c:950
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *__udp6_lib_demux_lookup(struct net *net, __be16 loc_port, const struct in6_addr *loc_addr, __be16 rmt_port, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b5a4a0)
Location: net/ipv6/udp.c:955
Inline: False
Direct callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
**Symbols:**

```
ffffffff81b5a4a0-ffffffff81b5a574: __udp6_lib_demux_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *__udp6_lib_demux_lookup(struct net *net, __be16 loc_port, const struct in6_addr *loc_addr, __be16 rmt_port, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b68ba0)
Location: net/ipv6/udp.c:1009
Inline: False
Direct callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
**Symbols:**

```
ffffffff81b68ba0-ffffffff81b68c74: __udp6_lib_demux_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b56e5d)
Location: net/ipv6/udp.c:1022
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81c1d07d)
Location: net/ipv6/udp.c:1024
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81dbbbfb)
Location: net/ipv6/udp.c:1033
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81f8bd29)
Location: net/ipv6/udp.c:1063
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81fec4c9)
Location: net/ipv6/udp.c:1080
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff820ba0d9)
Location: net/ipv6/udp.c:1054
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffff800010d244d0)
Location: net/ipv6/udp.c:950
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (c0e2b32c)
Location: net/ipv6/udp.c:950
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (c000000000e56d64)
Location: net/ipv6/udp.c:950
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffe000868004)
Location: net/ipv6/udp.c:950
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a008fe)
Location: net/ipv6/udp.c:950
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819bd6be)
Location: net/ipv6/udp.c:950
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a6b37e)
Location: net/ipv6/udp.c:950
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a7798e)
Location: net/ipv6/udp.c:950
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
