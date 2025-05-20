# Function: <code>__udp4_lib_mcast_demux_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8178a759)
Location: net/ipv4/udp.c:1877
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff817f7fa5)
Location: net/ipv4/udp.c:1847
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81828e45)
Location: net/ipv4/udp.c:2003
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8184a12b)
Location: net/ipv4/udp.c:2166
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (ffffffff818c9d0c)
Location: net/ipv4/udp.c:2171
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (ffffffff8191ff45)
Location: net/ipv4/udp.c:2257
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (ffffffff8194eba3)
Location: net/ipv4/udp.c:2359
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (ffffffff819b336b)
Location: net/ipv4/udp.c:2344
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (ffffffff819ea0ee)
Location: net/ipv4/udp.c:2380
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *__udp4_lib_mcast_demux_lookup(struct net *net, __be16 loc_port, __be32 loc_addr, __be16 rmt_port, __be32 rmt_addr, int dif, int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad2d20)
Location: net/ipv4/udp.c:2390
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81ad2d20-ffffffff81ad2e5e: __udp4_lib_mcast_demux_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *__udp4_lib_mcast_demux_lookup(struct net *net, __be16 loc_port, __be32 loc_addr, __be16 rmt_port, __be32 rmt_addr, int dif, int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81adf160)
Location: net/ipv4/udp.c:2443
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81adf160-ffffffff81adf29e: __udp4_lib_mcast_demux_lookup (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff81acf524)
Location: net/ipv4/udp.c:2494
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (ffffffff81b8df4d)
Location: net/ipv4/udp.c:2506
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (ffffffff81d1ef01)
Location: net/ipv4/udp.c:2521
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (ffffffff81ee601f)
Location: net/ipv4/udp.c:2523
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (ffffffff81f4581f)
Location: net/ipv4/udp.c:2495
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (ffffffff8200b96f)
Location: net/ipv4/udp.c:2472
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (ffff800010c9f8cc)
Location: net/ipv4/udp.c:2380
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (c0dacc18)
Location: net/ipv4/udp.c:2380
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (c000000000db24a8)
Location: net/ipv4/udp.c:2380
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (ffffffe0007fc402)
Location: net/ipv4/udp.c:2380
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (ffffffff81989f5e)
Location: net/ipv4/udp.c:2380
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (ffffffff81943a1e)
Location: net/ipv4/udp.c:2380
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (ffffffff819f472e)
Location: net/ipv4/udp.c:2380
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/udp.c (ffffffff819fe8ee)
Location: net/ipv4/udp.c:2380
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
