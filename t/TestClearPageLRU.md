# Function: <code>TestClearPageLRU</code>

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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81268bac)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff8127018f)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/compaction.c (ffffffff8128cbbd)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812a1a20)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff8126e94c)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff81275f82)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/compaction.c (ffffffff81291a13)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812a71db)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff812ab9ac)
Location: include/linux/page-flags.h:351
Inline: True
Inline callers:
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff812b2600)
Location: include/linux/page-flags.h:351
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/compaction.c (ffffffff812d12da)
Location: include/linux/page-flags.h:351
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812e86f5)
Location: include/linux/page-flags.h:351
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff813058b1)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff8130f3d2)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/compaction.c (ffffffff81330aa8)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8134a914)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_page
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
In mm/compaction.c (ffffffff813a7919)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff813c3504)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_page
```
</details>
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
