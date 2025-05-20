# Function: <code>count_memcg_events</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811ca724)
Location: include/linux/memcontrol.h:627
Inline: True
```
```
In mm/vmscan.c (ffffffff811d3d00)
Location: include/linux/memcontrol.h:627
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/swap.c (ffffffff811df659)
Location: include/linux/memcontrol.h:630
Inline: True
```
```
In mm/vmscan.c (ffffffff811e9250)
Location: include/linux/memcontrol.h:630
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff811efc20)
Location: include/linux/memcontrol.h:696
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/swap.c (ffffffff81200e06)
Location: include/linux/memcontrol.h:696
Inline: True
```
```
In mm/vmscan.c (ffffffff8120a775)
Location: include/linux/memcontrol.h:696
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81211272)
Location: include/linux/memcontrol.h:696
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff812302be)
Location: include/linux/memcontrol.h:696
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (ffffffff812f9ad7)
Location: include/linux/memcontrol.h:696
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
In mm/filemap.c (ffffffff81201e7b)
Location: include/linux/memcontrol.h:736
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/swap.c (ffffffff8121377b)
Location: include/linux/memcontrol.h:736
Inline: True
```
```
In mm/vmscan.c (ffffffff8121d465)
Location: include/linux/memcontrol.h:736
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812231bb)
Location: include/linux/memcontrol.h:736
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff81242c6e)
Location: include/linux/memcontrol.h:736
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (ffffffff8130da8c)
Location: include/linux/memcontrol.h:736
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
In mm/filemap.c (ffffffff81217ca3)
Location: include/linux/memcontrol.h:716
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/swap.c (ffffffff812231ba)
Location: include/linux/memcontrol.h:716
Inline: True
```
```
In mm/vmscan.c (ffffffff8122bdc7)
Location: include/linux/memcontrol.h:716
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812331de)
Location: include/linux/memcontrol.h:716
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffff81254b0f)
Location: include/linux/memcontrol.h:716
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff812a6d3f)
Location: include/linux/memcontrol.h:716
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812aaf73)
Location: include/linux/memcontrol.h:716
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81335cb5)
Location: include/linux/memcontrol.h:716
Inline: True
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
In mm/filemap.c (ffffffff81225577)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/swap.c (ffffffff81230c6a)
Location: include/linux/memcontrol.h:753
Inline: True
```
```
In mm/vmscan.c (ffffffff81239c8d)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812413ff)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffff8126306f)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff812b81ea)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bc90e)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813498b5)
Location: include/linux/memcontrol.h:753
Inline: True
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
In mm/filemap.c (ffffffff81253554)
Location: include/linux/memcontrol.h:731
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/vmscan.c (ffffffff81266414)
Location: include/linux/memcontrol.h:731
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8126dc5a)
Location: include/linux/memcontrol.h:731
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffff81294e4f)
Location: include/linux/memcontrol.h:731
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff812e968d)
Location: include/linux/memcontrol.h:731
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f143c)
Location: include/linux/memcontrol.h:731
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8138eb20)
Location: include/linux/memcontrol.h:731
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
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
In mm/filemap.c (ffffffff8125883e)
Location: include/linux/memcontrol.h:1000
Inline: True
```
```
In mm/vmscan.c (ffffffff81270e19)
Location: include/linux/memcontrol.h:1000
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812764ae)
Location: include/linux/memcontrol.h:1000
Inline: True
```
```
In mm/memory.c (ffffffff8129f6d3)
Location: include/linux/memcontrol.h:1000
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff812f4b2d)
Location: include/linux/memcontrol.h:1000
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812fde31)
Location: include/linux/memcontrol.h:1000
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8139df3e)
Location: include/linux/memcontrol.h:1000
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
In mm/filemap.c (ffffffff8125ce9e)
Location: include/linux/memcontrol.h:1041
Inline: True
```
```
In mm/vmscan.c (ffffffff812751f5)
Location: include/linux/memcontrol.h:1041
Inline: True
```
```
In mm/shmem.c (ffffffff8127d0de)
Location: include/linux/memcontrol.h:1041
Inline: True
```
```
In mm/memory.c (ffffffff812a46d3)
Location: include/linux/memcontrol.h:1041
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff812fb0ae)
Location: include/linux/memcontrol.h:1041
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81304714)
Location: include/linux/memcontrol.h:1041
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813a6c7e)
Location: include/linux/memcontrol.h:1041
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
In mm/filemap.c (ffffffff8129964b)
Location: include/linux/memcontrol.h:1033
Inline: True
```
```
In mm/vmscan.c (ffffffff812b2545)
Location: include/linux/memcontrol.h:1033
Inline: True
```
```
In mm/shmem.c (ffffffff812bb22b)
Location: include/linux/memcontrol.h:1033
Inline: True
```
```
In mm/memory.c (ffffffff812e5983)
Location: include/linux/memcontrol.h:1033
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff81344f17)
Location: include/linux/memcontrol.h:1033
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134e449)
Location: include/linux/memcontrol.h:1033
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813f6b3b)
Location: include/linux/memcontrol.h:1033
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff812ef630)
Location: include/linux/memcontrol.h:1057
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/vmscan.c (ffffffff8130bb00)
Location: include/linux/memcontrol.h:1057
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81315d50)
Location: include/linux/memcontrol.h:1057
Inline: True
Direct callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/memory.c (ffffffff8133ce80)
Location: include/linux/memcontrol.h:1057
Inline: True
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/zswap.c (ffffffff81384770)
Location: include/linux/memcontrol.h:1057
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (ffffffff813b9320)
Location: include/linux/memcontrol.h:1057
Inline: True
Direct callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c3710)
Location: include/linux/memcontrol.h:1057
Inline: True
Direct callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81467800)
Location: include/linux/memcontrol.h:1057
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff812ef630-ffffffff812ef670: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff8130bb00-ffffffff8130bb36: count_memcg_events (STB_LOCAL)
ffffffff81315d50-ffffffff81315d90: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff8133ce80-ffffffff8133cebb: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff81384770-ffffffff813847ab: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff813b9320-ffffffff813b9360: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff813c3710-ffffffff813c3750: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff81467800-ffffffff81467840: count_memcg_events.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff8135a020)
Location: include/linux/memcontrol.h:1057
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/vmscan.c (ffffffff81376360)
Location: include/linux/memcontrol.h:1057
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff81389e60)
Location: include/linux/memcontrol.h:1057
Inline: True
Direct callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/memory.c (ffffffff813b4a90)
Location: include/linux/memcontrol.h:1057
Inline: True
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/zswap.c (ffffffff81402380)
Location: include/linux/memcontrol.h:1057
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (ffffffff8143b5d0)
Location: include/linux/memcontrol.h:1057
Inline: True
Direct callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814460f0)
Location: include/linux/memcontrol.h:1057
Inline: True
Direct callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In fs/dax.c (ffffffff814f7ea0)
Location: include/linux/memcontrol.h:1057
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff8135a020-ffffffff8135a06b: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff81376360-ffffffff813763b3: count_memcg_events (STB_LOCAL)
ffffffff81389e60-ffffffff81389eab: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff813b4a90-ffffffff813b4adf: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff81402380-ffffffff814023cf: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff8143b5d0-ffffffff8143b61b: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff814460f0-ffffffff8144613b: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff814f7ea0-ffffffff814f7eeb: count_memcg_events.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff8138ba70)
Location: include/linux/memcontrol.h:1073
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/vmscan.c (ffffffff813a5c70)
Location: include/linux/memcontrol.h:1073
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff813bc040)
Location: include/linux/memcontrol.h:1073
Inline: True
Direct callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/memory.c (ffffffff813e96f0)
Location: include/linux/memcontrol.h:1073
Inline: True
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/zswap.c (ffffffff81435240)
Location: include/linux/memcontrol.h:1073
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (ffffffff81470f40)
Location: include/linux/memcontrol.h:1073
Inline: True
Direct callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147b7d0)
Location: include/linux/memcontrol.h:1073
Inline: True
Direct callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In fs/dax.c (ffffffff8152f0a0)
Location: include/linux/memcontrol.h:1073
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff8138ba70-ffffffff8138babb: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff813a5c70-ffffffff813a5cc3: count_memcg_events (STB_LOCAL)
ffffffff813bc040-ffffffff813bc08b: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff813e96f0-ffffffff813e973f: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff81435240-ffffffff8143528f: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff81470f40-ffffffff81470f8b: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff8147b7d0-ffffffff8147b81b: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff8152f0a0-ffffffff8152f0eb: count_memcg_events.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff813b55e0)
Location: include/linux/memcontrol.h:1090
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/vmscan.c (ffffffff813cf7e0)
Location: include/linux/memcontrol.h:1090
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff813e6c30)
Location: include/linux/memcontrol.h:1090
Inline: True
Direct callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/memory.c (ffffffff81414670)
Location: include/linux/memcontrol.h:1090
Inline: True
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/page_io.c (ffffffff81463030)
Location: include/linux/memcontrol.h:1090
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:swap_writepage_fs
```
```
In mm/zswap.c (ffffffff8146e2e0)
Location: include/linux/memcontrol.h:1090
Inline: True
Direct callers:
  - mm/zswap.c:zswap_load
  - mm/zswap.c:zswap_store
  - mm/zswap.c:shrink_memcg_cb
```
```
In mm/huge_memory.c (ffffffff814a0600)
Location: include/linux/memcontrol.h:1090
Inline: True
Direct callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814aaab0)
Location: include/linux/memcontrol.h:1090
Inline: True
Direct callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In fs/dax.c (ffffffff81563f80)
Location: include/linux/memcontrol.h:1090
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff813b55e0-ffffffff813b562b: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff813cf7e0-ffffffff813cf833: count_memcg_events (STB_LOCAL)
ffffffff813e6c30-ffffffff813e6c7b: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff81414670-ffffffff814146bf: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff81463030-ffffffff8146307b: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff8146e2e0-ffffffff8146e32f: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff814a0600-ffffffff814a064b: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff814aaab0-ffffffff814aaafb: count_memcg_events.constprop.0 (STB_LOCAL)
ffffffff81563f80-ffffffff81563fcb: count_memcg_events.constprop.0 (STB_LOCAL)
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
In mm/filemap.c (ffff8000102b274c)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/swap.c (ffff8000102c1640)
Location: include/linux/memcontrol.h:753
Inline: True
```
```
In mm/vmscan.c (ffff8000102cac48)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffff8000102d3b4c)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffff8000102fa34c)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffff80001035882c)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035db58)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffff80001040a358)
Location: include/linux/memcontrol.h:753
Inline: True
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
In mm/filemap.c (c04df9cc)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/swap.c (c04ebecc)
Location: include/linux/memcontrol.h:753
Inline: True
```
```
In mm/vmscan.c (c04f4a94)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (c04fbab8)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (c051bca4)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
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
In mm/filemap.c (c000000000368d2c)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/swap.c (c000000000379a28)
Location: include/linux/memcontrol.h:753
Inline: True
```
```
In mm/vmscan.c (c000000000387990)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (c000000000392918)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (c0000000003c44c4)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (c0000000004415bc)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (c000000000449188)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (c000000000516514)
Location: include/linux/memcontrol.h:753
Inline: True
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
In mm/filemap.c (ffffffe0001d8084)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/swap.c (ffffffe0001e2394)
Location: include/linux/memcontrol.h:753
Inline: True
```
```
In mm/vmscan.c (ffffffe0001e9c38)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffe0001ef884)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffe000209b0e)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (ffffffe0002b3f32)
Location: include/linux/memcontrol.h:753
Inline: True
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
In mm/filemap.c (ffffffff8121dbc7)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/swap.c (ffffffff812292ba)
Location: include/linux/memcontrol.h:753
Inline: True
```
```
In mm/vmscan.c (ffffffff812322dd)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81239a4f)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffff8125b6bf)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff812b07ca)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b4eee)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81341e95)
Location: include/linux/memcontrol.h:753
Inline: True
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
In mm/filemap.c (ffffffff81210d91)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/swap.c (ffffffff8121c3fa)
Location: include/linux/memcontrol.h:753
Inline: True
```
```
In mm/vmscan.c (ffffffff8122539d)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8122ca7f)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffff8124dc9f)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff812a1a5c)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a5f30)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81332862)
Location: include/linux/memcontrol.h:753
Inline: True
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
In mm/filemap.c (ffffffff8121b967)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/swap.c (ffffffff8122705a)
Location: include/linux/memcontrol.h:753
Inline: True
```
```
In mm/vmscan.c (ffffffff8123007d)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812377ef)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffff8125945f)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff812ae5da)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b2cfe)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8133f965)
Location: include/linux/memcontrol.h:753
Inline: True
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
In mm/filemap.c (ffffffff8122a9c3)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/swap.c (ffffffff8123638a)
Location: include/linux/memcontrol.h:753
Inline: True
```
```
In mm/vmscan.c (ffffffff8123f4c6)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81246d35)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffff81268e64)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff812be937)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c313b)
Location: include/linux/memcontrol.h:753
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81353336)
Location: include/linux/memcontrol.h:753
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
