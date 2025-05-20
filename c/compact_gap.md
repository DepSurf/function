# Function: <code>compact_gap</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811ccc6d)
Location: include/linux/compaction.h:67
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffff811df47a)
Location: include/linux/compaction.h:67
Inline: True
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
In mm/vmscan.c (ffffffff811d58d3)
Location: include/linux/compaction.h:67
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffff811e912f)
Location: include/linux/compaction.h:67
Inline: True
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
In mm/vmscan.c (ffffffff811eadfb)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffff811ff48f)
Location: include/linux/compaction.h:68
Inline: True
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
In mm/vmscan.c (ffffffff8120c525)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffff81220724)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (ffffffff8121f2b0)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffff81233773)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (ffffffff8122ea84)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffff81243b2c)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (ffffffff8123cc14)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffff81251fec)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (ffffffff812699db)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_zones
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffff812809fc)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (ffffffff812744cb)
Location: include/linux/compaction.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_zones
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffff8128aacc)
Location: include/linux/compaction.h:65
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (ffffffff8127979e)
Location: include/linux/compaction.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffff81290129)
Location: include/linux/compaction.h:65
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (ffffffff812b78f5)
Location: include/linux/compaction.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffff812cfbd5)
Location: include/linux/compaction.h:65
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (ffffffff813124e9)
Location: include/linux/compaction.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffff8132e61a)
Location: include/linux/compaction.h:65
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (ffffffff81385ad7)
Location: include/linux/compaction.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffff813a4dda)
Location: include/linux/compaction.h:65
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (ffffffff813b8d50)
Location: include/linux/compaction.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:try_to_shrink_lruvec
```
```
In mm/compaction.c (ffffffff813d835c)
Location: include/linux/compaction.h:65
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (ffffffff813e1d50)
Location: include/linux/compaction.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:should_abort_scan
```
```
In mm/compaction.c (ffffffff8140203c)
Location: include/linux/compaction.h:65
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (ffff8000102cde90)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffff8000102e8af0)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (c04f7d4c)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (c050d80c)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (c00000000038bac0)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (c0000000003abddc)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (ffffffe0001ec18e)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffe0001fe812)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (ffffffff81235264)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffff8124a63c)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (ffffffff812282d4)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffff8123d5ec)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (ffffffff81233004)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffff812483dc)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
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
In mm/vmscan.c (ffffffff81242514)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
```
```
In mm/compaction.c (ffffffff81257c0c)
Location: include/linux/compaction.h:68
Inline: True
Inline callers:
  - mm/compaction.c:__compaction_suitable
```
</details>
</li>
</ul>

## Differences
