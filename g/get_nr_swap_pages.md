# Function: <code>get_nr_swap_pages</code>

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
In mm/vmscan.c (ffffffff811a03f0)
Location: include/linux/swap.h:425
Inline: True
Inline callers:
  - mm/vmscan.c:pfmemalloc_watermark_ok
  - mm/vmscan.c:zone_reclaimable
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_zone
```
```
In mm/mmap.c (ffffffff811c498a)
Location: include/linux/swap.h:425
Inline: True
Inline callers:
  - mm/mmap.c:__vm_enough_memory
```
```
In mm/swap_state.c (ffffffff811d26d7)
Location: include/linux/swap.h:425
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
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
In mm/vmscan.c (ffffffff811bb759)
Location: include/linux/swap.h:395
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/util.c (ffffffff811c4e91)
Location: include/linux/swap.h:395
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/madvise.c (ffffffff811ef4ea)
Location: include/linux/swap.h:395
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swap_state.c (ffffffff811f034b)
Location: include/linux/swap.h:395
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/memcontrol.c (ffffffff81224bdc)
Location: include/linux/swap.h:395
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff811cbe29)
Location: include/linux/swap.h:370
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/util.c (ffffffff811d4fa1)
Location: include/linux/swap.h:370
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/madvise.c (ffffffff811ffe6a)
Location: include/linux/swap.h:370
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swap_state.c (ffffffff81200cfb)
Location: include/linux/swap.h:370
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/memcontrol.c (ffffffff812371cc)
Location: include/linux/swap.h:370
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff811d4963)
Location: include/linux/swap.h:385
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/util.c (ffffffff811dddf1)
Location: include/linux/swap.h:385
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/swap_slots.c (ffffffff811ec9c3)
Location: include/linux/swap.h:385
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/swap_state.c (ffffffff8120ba25)
Location: include/linux/swap.h:385
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/memcontrol.c (ffffffff81242c8c)
Location: include/linux/swap.h:385
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff811e9eb3)
Location: include/linux/swap.h:455
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:pgdat_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/util.c (ffffffff811f3871)
Location: include/linux/swap.h:455
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/swap_slots.c (ffffffff81202d23)
Location: include/linux/swap.h:455
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/swap_state.c (ffffffff81225015)
Location: include/linux/swap.h:455
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/memcontrol.c (ffffffff81262acb)
Location: include/linux/swap.h:455
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff8120b57b)
Location: include/linux/swap.h:441
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/util.c (ffffffff81214b89)
Location: include/linux/swap.h:441
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/swap_state.c (ffffffff812475d5)
Location: include/linux/swap.h:441
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffffffff8124ec91)
Location: include/linux/swap.h:441
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/memcontrol.c (ffffffff81286c85)
Location: include/linux/swap.h:441
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff8121e272)
Location: include/linux/swap.h:441
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/util.c (ffffffff81227a69)
Location: include/linux/swap.h:441
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/swap_state.c (ffffffff8125ba45)
Location: include/linux/swap.h:441
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffffffff81263173)
Location: include/linux/swap.h:441
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/memcontrol.c (ffffffff8129bb95)
Location: include/linux/swap.h:441
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff8122d924)
Location: include/linux/swap.h:441
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (ffffffff81276bf5)
Location: include/linux/swap.h:441
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffffffff8127e0e3)
Location: include/linux/swap.h:441
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/memcontrol.c (ffffffff812b6d65)
Location: include/linux/swap.h:441
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff8123bb2d)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (ffffffff812866e5)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffffffff8128db33)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/memcontrol.c (ffffffff812c8c35)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff81268d1e)
Location: include/linux/swap.h:450
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (ffffffff812b8c75)
Location: include/linux/swap.h:450
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffffffff812c05f3)
Location: include/linux/swap.h:450
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/memcontrol.c (ffffffff812fe265)
Location: include/linux/swap.h:450
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff81273803)
Location: include/linux/swap.h:451
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (ffffffff812c4335)
Location: include/linux/swap.h:451
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffffffff812cc016)
Location: include/linux/swap.h:451
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/memcontrol.c (ffffffff8130a795)
Location: include/linux/swap.h:451
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff81278b38)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (ffffffff81bda687)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffffffff812d2bc6)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/memcontrol.c (ffffffff81310de5)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff812b68c2)
Location: include/linux/swap.h:484
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (ffffffff81cbe9c1)
Location: include/linux/swap.h:484
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffffffff813185a6)
Location: include/linux/swap.h:484
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/memcontrol.c (ffffffff8135c0c5)
Location: include/linux/swap.h:484
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff81311d68)
Location: include/linux/swap.h:472
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (ffffffff81e70b1c)
Location: include/linux/swap.h:472
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffffffff81383c66)
Location: include/linux/swap.h:472
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/memcontrol.c (ffffffff813d5a05)
Location: include/linux/swap.h:472
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff81385346)
Location: include/linux/swap.h:478
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (ffffffff813f8565)
Location: include/linux/swap.h:478
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffffffff814017af)
Location: include/linux/swap.h:478
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/memcontrol.c (ffffffff8145b465)
Location: include/linux/swap.h:478
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff813b857b)
Location: include/linux/swap.h:473
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (ffffffff8142b325)
Location: include/linux/swap.h:473
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffffffff8143468f)
Location: include/linux/swap.h:473
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/memcontrol.c (ffffffff814910d5)
Location: include/linux/swap.h:473
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_read_u64
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
In mm/vmscan.c (ffffffff813e1614)
Location: include/linux/swap.h:465
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (ffffffff81464b15)
Location: include/linux/swap.h:465
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffffffff8146da89)
Location: include/linux/swap.h:465
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/memcontrol.c (ffffffff814c0a45)
Location: include/linux/swap.h:465
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_read_u64
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
In mm/vmscan.c (ffff8000102ccc28)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (ffff800010320e6c)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffff800010329e48)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/memcontrol.c (ffff80001036bb00)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (c04f6a44)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (c05397bc)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (c05406d0)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/memcontrol.c (c055d170)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (c00000000038a474)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (c0000000003f62f4)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (c000000000400b50)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/memcontrol.c (c00000000045b790)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffe0001eb5ea)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (ffffffe000222366)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffffffe00022914c)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/memcontrol.c (ffffffe0002490f6)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff8123417d)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (ffffffff8127ed35)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffffffff81286113)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/memcontrol.c (ffffffff812c1215)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff812271ed)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (ffffffff81270b65)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffffffff81277f73)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/memcontrol.c (ffffffff812b2265)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff81231f1d)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (ffffffff8127cad5)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffffffff81283f23)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/memcontrol.c (ffffffff812bf025)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
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
In mm/vmscan.c (ffffffff8124137d)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/swap_state.c (ffffffff8128c6a5)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swap_slots.c (ffffffff81293c03)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/memcontrol.c (ffffffff812cfa95)
Location: include/linux/swap.h:443
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
```
</details>
</li>
</ul>

## Differences
