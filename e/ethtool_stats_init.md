# Function: <code>ethtool_stats_init</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/pause.c (ffffffff81a957b9)
Location: net/ethtool/pause.c:24
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_prepare_data
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
In net/ethtool/pause.c (ffffffff81a7f205)
Location: include/linux/ethtool.h:247
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_prepare_data
```
```
In net/ethtool/fec.c (0)
Location: include/linux/ethtool.h:247
Inline: True
Inline callers:
  - net/ethtool/fec.c:fec_prepare_data
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
In net/ethtool/pause.c (ffffffff81b39014)
Location: include/linux/ethtool.h:253
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_prepare_data
```
```
In net/ethtool/fec.c (0)
Location: include/linux/ethtool.h:253
Inline: True
Inline callers:
  - net/ethtool/fec.c:fec_prepare_data
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
In net/ethtool/pause.c (ffffffff81cc4df4)
Location: include/linux/ethtool.h:280
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_prepare_data
```
```
In net/ethtool/fec.c (ffffffff81cc7443)
Location: include/linux/ethtool.h:280
Inline: True
Inline callers:
  - net/ethtool/fec.c:fec_prepare_data
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
In net/ethtool/linkstate.c (ffffffff81e81581)
Location: include/linux/ethtool.h:294
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_prepare_data
```
```
In net/ethtool/pause.c (ffffffff81e842e4)
Location: include/linux/ethtool.h:294
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_prepare_data
```
```
In net/ethtool/fec.c (ffffffff81e86ae3)
Location: include/linux/ethtool.h:294
Inline: True
Inline callers:
  - net/ethtool/fec.c:fec_prepare_data
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
In net/ethtool/linkstate.c (ffffffff81eddc91)
Location: include/linux/ethtool.h:310
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_prepare_data
```
```
In net/ethtool/pause.c (ffffffff81ee0c11)
Location: include/linux/ethtool.h:310
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_prepare_data
```
```
In net/ethtool/fec.c (ffffffff81ee3843)
Location: include/linux/ethtool.h:310
Inline: True
Inline callers:
  - net/ethtool/fec.c:fec_prepare_data
```
```
In net/ethtool/mm.c (ffffffff81ee52d4)
Location: include/linux/ethtool.h:310
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_prepare_data
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
In net/ethtool/linkstate.c (ffffffff81fa1ac1)
Location: include/linux/ethtool.h:312
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_prepare_data
```
```
In net/ethtool/pause.c (ffffffff81fa4aab)
Location: include/linux/ethtool.h:312
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_prepare_data
```
```
In net/ethtool/fec.c (ffffffff81fa7623)
Location: include/linux/ethtool.h:312
Inline: True
Inline callers:
  - net/ethtool/fec.c:fec_prepare_data
```
```
In net/ethtool/mm.c (ffffffff81fa90b4)
Location: include/linux/ethtool.h:312
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_prepare_data
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
