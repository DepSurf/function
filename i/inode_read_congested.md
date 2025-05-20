# Function: <code>inode_read_congested</code>

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
In mm/readahead.c (ffffffff8119c286)
Location: include/linux/backing-dev.h:480
Inline: True
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
In mm/readahead.c (ffffffff811b1486)
Location: include/linux/backing-dev.h:481
Inline: True
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
In mm/readahead.c (ffffffff811c1ab6)
Location: include/linux/backing-dev.h:481
Inline: True
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
In mm/readahead.c (ffffffff811c9d57)
Location: include/linux/backing-dev.h:456
Inline: True
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
In mm/readahead.c (ffffffff811dec27)
Location: include/linux/backing-dev.h:461
Inline: True
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
In mm/readahead.c (ffffffff81200396)
Location: include/linux/backing-dev.h:464
Inline: True
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
In mm/readahead.c (ffffffff81212c96)
Location: include/linux/backing-dev.h:464
Inline: True
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
In mm/readahead.c (ffffffff8122267c)
Location: include/linux/backing-dev.h:465
Inline: True
```
```
In mm/swap_state.c (ffffffff81277835)
Location: include/linux/backing-dev.h:465
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/readahead.c (ffffffff8123012c)
Location: include/linux/backing-dev.h:471
Inline: True
```
```
In mm/swap_state.c (ffffffff81287325)
Location: include/linux/backing-dev.h:471
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/readahead.c (ffffffff8125d36c)
Location: include/linux/backing-dev.h:467
Inline: True
```
```
In mm/swap_state.c (ffffffff812b9b49)
Location: include/linux/backing-dev.h:467
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/readahead.c (ffffffff812676fd)
Location: include/linux/backing-dev.h:395
Inline: True
```
```
In mm/swap_state.c (ffffffff812c55b7)
Location: include/linux/backing-dev.h:395
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/readahead.c (ffffffff8126c30a)
Location: include/linux/backing-dev.h:395
Inline: True
```
```
In mm/swap_state.c (ffffffff812cc264)
Location: include/linux/backing-dev.h:395
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/readahead.c (ffffffff812a901a)
Location: include/linux/backing-dev.h:414
Inline: True
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffff8000102bf9a8)
Location: include/linux/backing-dev.h:471
Inline: True
```
```
In mm/swap_state.c (ffff800010321e84)
Location: include/linux/backing-dev.h:471
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/readahead.c (c04eb440)
Location: include/linux/backing-dev.h:471
Inline: True
```
```
In mm/swap_state.c (c053a554)
Location: include/linux/backing-dev.h:471
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/readahead.c (c00000000037886c)
Location: include/linux/backing-dev.h:471
Inline: True
```
```
In mm/swap_state.c (c0000000003f7790)
Location: include/linux/backing-dev.h:471
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/readahead.c (ffffffe0001e19ea)
Location: include/linux/backing-dev.h:471
Inline: True
```
```
In mm/swap_state.c (ffffffe000222f2c)
Location: include/linux/backing-dev.h:471
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/readahead.c (ffffffff8122877c)
Location: include/linux/backing-dev.h:471
Inline: True
```
```
In mm/swap_state.c (ffffffff8127f92e)
Location: include/linux/backing-dev.h:471
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/readahead.c (ffffffff8121b8bc)
Location: include/linux/backing-dev.h:471
Inline: True
```
```
In mm/swap_state.c (ffffffff81271795)
Location: include/linux/backing-dev.h:471
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/readahead.c (ffffffff8122651c)
Location: include/linux/backing-dev.h:471
Inline: True
```
```
In mm/swap_state.c (ffffffff8127d715)
Location: include/linux/backing-dev.h:471
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/readahead.c (ffffffff81235843)
Location: include/linux/backing-dev.h:471
Inline: True
```
```
In mm/swap_state.c (ffffffff8128d2c5)
Location: include/linux/backing-dev.h:471
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
</details>
</li>
</ul>

## Differences
