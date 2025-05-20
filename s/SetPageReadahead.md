# Function: <code>SetPageReadahead</code>

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
In mm/readahead.c (ffffffff8119beea)
Location: include/linux/page-flags.h:247
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap_state.c (ffffffff811d2d6f)
Location: include/linux/page-flags.h:247
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/readahead.c (ffffffff811b109f)
Location: include/linux/page-flags.h:303
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap_state.c (ffffffff811f0b89)
Location: include/linux/page-flags.h:303
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/readahead.c (ffffffff811c167d)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap_state.c (ffffffff81201589)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/readahead.c (ffffffff811c993a)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap_state.c (ffffffff8120c450)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/readahead.c (ffffffff811de7bd)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap_state.c (ffffffff812261fb)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swapin_readahead
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
In mm/readahead.c (ffffffff811fffc0)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap_state.c (ffffffff81248778)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/readahead.c (ffffffff8121288d)
Location: include/linux/page-flags.h:333
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap_state.c (ffffffff8125cd4e)
Location: include/linux/page-flags.h:333
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/readahead.c (ffffffff81222280)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap_state.c (ffffffff81277efa)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/readahead.c (ffffffff8122fd30)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap_state.c (ffffffff812879ea)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/readahead.c (ffffffff8125cec5)
Location: include/linux/page-flags.h:374
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_readahead_unbounded
```
```
In mm/swap_state.c (ffffffff812b99b2)
Location: include/linux/page-flags.h:374
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/migrate.c (ffffffff812e2df9)
Location: include/linux/page-flags.h:374
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/readahead.c (ffffffff81267225)
Location: include/linux/page-flags.h:382
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/swap_state.c (ffffffff812c5418)
Location: include/linux/page-flags.h:382
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/migrate.c (ffffffff812ee23b)
Location: include/linux/page-flags.h:382
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/readahead.c (ffffffff8126be86)
Location: include/linux/page-flags.h:382
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/swap_state.c (ffffffff812cc0d2)
Location: include/linux/page-flags.h:382
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/migrate.c (ffffffff812f3d2b)
Location: include/linux/page-flags.h:382
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/readahead.c (ffffffff812a8b60)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/swap_state.c (ffffffff813112bf)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/migrate.c (ffffffff8133e6d7)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/swap_state.c (ffffffff8137c238)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/swap_state.c (ffffffff813f99d8)
Location: include/linux/page-flags.h:525
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
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
In mm/swap_state.c (ffffffff8142ca05)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
```
</details>
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
In mm/readahead.c (ffff8000102bf634)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap_state.c (ffff8000103224dc)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/readahead.c (c04eb0d8)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap_state.c (c053aaf4)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/readahead.c (c000000000378268)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap_state.c (c0000000003f8094)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/readahead.c (ffffffe0001e174e)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap_state.c (ffffffe0002233da)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/readahead.c (ffffffff81228380)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap_state.c (ffffffff8127ff82)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/readahead.c (ffffffff8121b4c0)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap_state.c (ffffffff81271d3a)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/readahead.c (ffffffff81226120)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap_state.c (ffffffff8127ddda)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/readahead.c (ffffffff81235420)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap_state.c (ffffffff8128d98a)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
```
</details>
</li>
</ul>

## Differences
