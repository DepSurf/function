# Function: <code>SetPageActive</code>

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
In mm/filemap.c (ffffffff8118df97)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8119cdf9)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff811a3034)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slub.c (ffffffff811e9a0c)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff811f1d3b)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/filemap.c (ffffffff811a1058)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff811b383e)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff811b9adb)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slub.c (ffffffff812086cc)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff812132e3)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_copy
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
In mm/filemap.c (ffffffff811b0c58)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff811c3ece)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff811ca18d)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slub.c (ffffffff8121a738)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8122564b)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_copy
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
In mm/filemap.c (ffffffff811b8188)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff811cc2be)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff811d284f)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slub.c (ffffffff81226140)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff81230f9e)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_copy
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
In mm/filemap.c (ffffffff811cc878)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff811e12ae)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff811e7d62)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slub.c (ffffffff812432d5)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8124edcb)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
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
In mm/filemap.c (ffffffff811ed659)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff812029e6)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff81209213)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slub.c (ffffffff81264bbd)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff81272c83)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
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
In mm/swap.c (ffffffff81215366)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff8121bef3)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/workingset.c (ffffffff81238fb2)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff8127934f)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff81287131)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
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
In mm/swap.c (ffffffff81224d87)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff8122bda7)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/workingset.c (ffffffff8124a141)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff81294491)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812a163c)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
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
In mm/swap.c (ffffffff81232b17)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff81239c6b)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/workingset.c (ffffffff81258591)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff812a41c0)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812b2a43)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
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
In mm/swap.c (ffffffff8125fff7)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff812663fb)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/workingset.c (ffffffff81286ca8)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff812d9d09)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812e7fba)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/swap.c (ffffffff81269701)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff81270dfe)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/workingset.c (ffffffff81290f5e)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff812e50b8)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812f356d)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/swap.c (ffffffff8126ec1e)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff812758f7)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/workingset.c (ffffffff812965a0)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff812ecc90)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812f9718)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/swap.c (ffffffff812abc6e)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff812b3565)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/workingset.c (ffffffff812d6d36)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff81334db2)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff8133e531)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/swap.c (ffff8000102c2ac0)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffff8000102cac18)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/workingset.c (ffff8000102f035c)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffff800010345ee4)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffff80001035342c)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
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
In mm/swap.c (c04edc4c)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (c04f4a6c)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/workingset.c (c0513a80)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (c0549c84)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (c0551510)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/swap.c (c00000000037cbe4)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (c000000000387958)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/workingset.c (c0000000003b4d6c)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (c0000000004227b0)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (c00000000043a24c)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
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
In mm/swap.c (ffffffe0001e3dee)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffe0001e9c04)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/workingset.c (ffffffe000203d76)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffe000238676)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffe00023e450)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/swap.c (ffffffff8122b167)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff812322bb)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/workingset.c (ffffffff81250be1)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff8129c7a0)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812ab023)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
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
In mm/swap.c (ffffffff8121e277)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff8122537b)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/workingset.c (ffffffff81243b49)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff8128e341)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff8129c93c)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
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
In mm/swap.c (ffffffff81228f07)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff8123005b)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/workingset.c (ffffffff8124e981)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff8129a5b0)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812a8e33)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
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
In mm/swap.c (ffffffff812382c7)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff8123f4a4)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/workingset.c (ffffffff8125e2f6)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff812aa490)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812b914d)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
```
</details>
</li>
</ul>

## Differences
