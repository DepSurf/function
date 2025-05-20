# Function: <code>managed_zone</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: include/linux/mmzone.h:837
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mmzone.h:837
Inline: True
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
In mm/page_alloc.c (0)
Location: include/linux/mmzone.h:811
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mmzone.h:811
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
In mm/page_alloc.c (0)
Location: include/linux/mmzone.h:831
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mmzone.h:831
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
In mm/page_alloc.c (0)
Location: include/linux/mmzone.h:834
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mmzone.h:834
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
In mm/page_alloc.c (0)
Location: include/linux/mmzone.h:833
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mmzone.h:833
Inline: True
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
In mm/page_alloc.c (ffffffff81206658)
Location: include/linux/mmzone.h:825
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonerefs_node
```
```
In mm/vmscan.c (ffffffff8121b875)
Location: include/linux/mmzone.h:825
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:lruvec_lru_size
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
In mm/vmscan.c (ffffffff8122b505)
Location: include/linux/mmzone.h:865
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/page_alloc.c (ffffffff8126c608)
Location: include/linux/mmzone.h:865
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonerefs_node
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
In mm/vmscan.c (ffffffff812393d5)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/page_alloc.c (ffffffff8127b418)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonerefs_node
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
In mm/vmscan.c (ffffffff8126a975)
Location: include/linux/mmzone.h:856
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
```
```
In mm/page_alloc.c (ffffffff812ad5b8)
Location: include/linux/mmzone.h:856
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonerefs_node
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
In mm/vmscan.c (ffffffff812753d5)
Location: include/linux/mmzone.h:894
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
```
```
In mm/page_alloc.c (ffffffff812b8f98)
Location: include/linux/mmzone.h:894
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonerefs_node
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
In mm/vmscan.c (ffffffff8127a6f5)
Location: include/linux/mmzone.h:953
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
```
```
In mm/page_alloc.c (ffffffff812be468)
Location: include/linux/mmzone.h:953
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonerefs_node
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
In mm/vmscan.c (ffffffff812b8755)
Location: include/linux/mmzone.h:992
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
```
```
In mm/page_alloc.c (ffffffff81300bab)
Location: include/linux/mmzone.h:992
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:warn_alloc
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
In mm/vmscan.c (ffffffff81314185)
Location: include/linux/mmzone.h:1014
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/page_alloc.c (ffffffff813691d4)
Location: include/linux/mmzone.h:1014
Inline: True
Inline callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:warn_alloc
```
```
In mm/migrate.c (ffffffff813b2d86)
Location: include/linux/mmzone.h:1014
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
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
In mm/vmscan.c (ffffffff81388245)
Location: include/linux/mmzone.h:1334
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:lru_gen_shrink_lruvec
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/page_alloc.c (ffffffff813e4f74)
Location: include/linux/mmzone.h:1334
Inline: True
Inline callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:warn_alloc
```
```
In mm/migrate.c (ffffffff814331eb)
Location: include/linux/mmzone.h:1334
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
```
```
In mm/huge_memory.c (ffffffff814428fc)
Location: include/linux/mmzone.h:1334
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
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
In mm/vmscan.c (ffffffff813ba525)
Location: include/linux/mmzone.h:1480
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/page_alloc.c (ffffffff81419ea4)
Location: include/linux/mmzone.h:1480
Inline: True
Inline callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:warn_alloc
```
```
In mm/migrate.c (ffffffff81468b04)
Location: include/linux/mmzone.h:1480
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
```
```
In mm/huge_memory.c (ffffffff81478227)
Location: include/linux/mmzone.h:1480
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
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
In mm/vmscan.c (ffffffff813e3645)
Location: include/linux/mmzone.h:1490
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:should_abort_scan
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/page_alloc.c (ffffffff81446934)
Location: include/linux/mmzone.h:1490
Inline: True
Inline callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:warn_alloc
```
```
In mm/migrate.c (ffffffff8149ac3b)
Location: include/linux/mmzone.h:1490
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
```
```
In mm/huge_memory.c (ffffffff814a7967)
Location: include/linux/mmzone.h:1490
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
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
In mm/vmscan.c (ffff8000102ca2b8)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/page_alloc.c (ffff8000103129c4)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonerefs_node
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
In mm/vmscan.c (c04f4104)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/page_alloc.c (c052d5d0)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
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
In mm/vmscan.c (c000000000386c10)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/page_alloc.c (c0000000003e399c)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonerefs_node
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
In mm/vmscan.c (ffffffe0001e93e4)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/page_alloc.c (ffffffe000219dac)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
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
In mm/vmscan.c (ffffffff81231a25)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/page_alloc.c (ffffffff81273a68)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonerefs_node
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
In mm/vmscan.c (ffffffff81224ae5)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/page_alloc.c (ffffffff812659d8)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonerefs_node
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
In mm/vmscan.c (ffffffff8122f7c5)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/page_alloc.c (ffffffff81271808)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonerefs_node
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
In mm/vmscan.c (ffffffff8123ebf5)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/page_alloc.c (ffffffff81281268)
Location: include/linux/mmzone.h:872
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonerefs_node
```
</details>
</li>
</ul>

## Differences
