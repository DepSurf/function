# Function: <code>prb_calc_retire_blk_tmo</code>

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
In net/packet/af_packet.c (ffffffff81805707)
Location: net/packet/af_packet.c:555
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffff818762da)
Location: net/packet/af_packet.c:556
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffff818aa7db)
Location: net/packet/af_packet.c:555
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffff818d12e8)
Location: net/packet/af_packet.c:563
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffff8195620b)
Location: net/packet/af_packet.c:550
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffff819b1655)
Location: net/packet/af_packet.c:526
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffff819e8a3e)
Location: net/packet/af_packet.c:527
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffff81a58d7d)
Location: net/packet/af_packet.c:519
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffff81a8eeca)
Location: net/packet/af_packet.c:519
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b860a8)
Location: net/packet/af_packet.c:526
Inline: True
Inline callers:
  - net/packet/af_packet.c:init_prb_bdqc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b959c3)
Location: net/packet/af_packet.c:530
Inline: True
Inline callers:
  - net/packet/af_packet.c:init_prb_bdqc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b844c0)
Location: net/packet/af_packet.c:531
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81b844c0-ffffffff81b8457b: prb_calc_retire_blk_tmo.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81c50950)
Location: net/packet/af_packet.c:532
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81c50950-ffffffff81c50a0b: prb_calc_retire_blk_tmo.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81df1570)
Location: net/packet/af_packet.c:568
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81df1570-ffffffff81df1649: prb_calc_retire_blk_tmo.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81fc5500)
Location: net/packet/af_packet.c:568
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81fc5500-ffffffff81fc55d9: prb_calc_retire_blk_tmo.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff82026110)
Location: net/packet/af_packet.c:570
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff82026110-ffffffff820261e9: prb_calc_retire_blk_tmo.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff820f5b20)
Location: net/packet/af_packet.c:570
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff820f5b20-ffffffff820f5bf9: prb_calc_retire_blk_tmo.constprop.0 (STB_LOCAL)
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
In net/packet/af_packet.c (ffff800010d5c0e8)
Location: net/packet/af_packet.c:519
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (c0e5c118)
Location: net/packet/af_packet.c:519
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (c000000000e97ad4)
Location: net/packet/af_packet.c:519
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffe0008922fa)
Location: net/packet/af_packet.c:519
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffff81a2e55a)
Location: net/packet/af_packet.c:519
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffff819eb74a)
Location: net/packet/af_packet.c:519
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffff81a9a10a)
Location: net/packet/af_packet.c:519
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffff81aa6e39)
Location: net/packet/af_packet.c:519
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
</details>
</li>
</ul>

## Differences
