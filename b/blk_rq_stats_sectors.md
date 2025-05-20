# Function: <code>blk_rq_stats_sectors</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ee6cb)
Location: include/linux/blkdev.h:952
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_stats_bkt
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
In block/blk-mq.c (ffffffff8154e33b)
Location: include/linux/blkdev.h:970
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/blk-iocost.c (ffffffff81571b1a)
Location: include/linux/blkdev.h:970
Inline: True
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
In block/blk-mq.c (ffffffff8156cc16)
Location: include/linux/blkdev.h:1018
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/blk-iocost.c (ffffffff8158cd25)
Location: include/linux/blkdev.h:1018
Inline: True
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
In block/blk-mq.c (ffffffff81574ab6)
Location: include/linux/blkdev.h:1001
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/blk-iocost.c (ffffffff81593a75)
Location: include/linux/blkdev.h:1001
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
In block/blk-mq.c (ffffffff815d8fd9)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/blk-iocost.c (ffffffff815faeb4)
Location: include/linux/blkdev.h:963
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
In block/blk-mq.c (ffffffff81686d63)
Location: include/linux/blk-mq.h:1033
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/blk-iocost.c (ffffffff816adeb0)
Location: include/linux/blk-mq.h:1033
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
In block/blk-mq.c (ffffffff81744a33)
Location: include/linux/blk-mq.h:1064
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/blk-iocost.c (ffffffff8176c7b0)
Location: include/linux/blk-mq.h:1064
Inline: True
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
In block/blk-iocost.c (ffffffff817aac7c)
Location: include/linux/blk-mq.h:1064
Inline: True
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
In block/blk-iocost.c (ffffffff817eea2c)
Location: include/linux/blk-mq.h:1061
Inline: True
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
In block/blk-mq.c (ffff8000105ed4c4)
Location: include/linux/blkdev.h:952
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_stats_bkt
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
In block/blk-mq.c (c079a048)
Location: include/linux/blkdev.h:952
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_stats_bkt
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
In block/blk-mq.c (c0000000007839d8)
Location: include/linux/blkdev.h:952
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_stats_bkt
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
In block/blk-mq.c (ffffffe00042e000)
Location: include/linux/blkdev.h:952
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_stats_bkt
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
In block/blk-mq.c (ffffffff814e6cab)
Location: include/linux/blkdev.h:952
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_stats_bkt
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
In block/blk-mq.c (ffffffff814d721b)
Location: include/linux/blkdev.h:952
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_stats_bkt
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
In block/blk-mq.c (ffffffff814e2d3b)
Location: include/linux/blkdev.h:952
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_stats_bkt
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
In block/blk-mq.c (ffffffff814fbbbb)
Location: include/linux/blkdev.h:952
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
</details>
</li>
</ul>

## Differences
