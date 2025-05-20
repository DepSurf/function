# Function: <code>radix_tree_iter_retry</code>

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
In lib/radix-tree.c (ffffffff813ee760)
Location: include/linux/radix-tree.h:382
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
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
In mm/filemap.c (ffffffff811a1864)
Location: include/linux/radix-tree.h:408
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/shmem.c (ffffffff811bf970)
Location: include/linux/radix-tree.h:408
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8121c8cb)
Location: include/linux/radix-tree.h:408
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In lib/radix-tree.c (ffffffff81434b09)
Location: include/linux/radix-tree.h:408
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In mm/filemap.c (ffffffff811b172b)
Location: include/linux/radix-tree.h:409
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/shmem.c (ffffffff811cfd3c)
Location: include/linux/radix-tree.h:409
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8122e310)
Location: include/linux/radix-tree.h:409
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In lib/radix-tree.c (ffffffff81450ffd)
Location: include/linux/radix-tree.h:409
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In mm/filemap.c (ffffffff811b7a03)
Location: include/linux/radix-tree.h:454
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/shmem.c (ffffffff811d972a)
Location: include/linux/radix-tree.h:454
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8123a688)
Location: include/linux/radix-tree.h:454
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In lib/radix-tree.c (ffffffff818f0c37)
Location: include/linux/radix-tree.h:454
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In mm/filemap.c (ffffffff811cbfef)
Location: include/linux/radix-tree.h:469
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
```
```
In mm/shmem.c (ffffffff811ee9e8)
Location: include/linux/radix-tree.h:469
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812595a6)
Location: include/linux/radix-tree.h:469
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:469
Inline: True
```
```
In lib/radix-tree.c (ffffffff81977087)
Location: include/linux/radix-tree.h:469
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In mm/filemap.c (ffffffff811ed162)
Location: include/linux/radix-tree.h:458
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
```
```
In mm/shmem.c (ffffffff81213b4c)
Location: include/linux/radix-tree.h:458
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8127d5f2)
Location: include/linux/radix-tree.h:458
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memfd.c (ffffffff812941d0)
Location: include/linux/radix-tree.h:458
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:458
Inline: True
```
```
In lib/radix-tree.c (ffffffff819d3824)
Location: include/linux/radix-tree.h:458
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:359
Inline: True
```
```
In lib/radix-tree.c (ffffffff81a0c847)
Location: include/linux/radix-tree.h:359
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:346
Inline: True
```
```
In lib/idr.c (ffffffff81a77ed5)
Location: include/linux/radix-tree.h:346
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next
```
```
In lib/radix-tree.c (ffffffff81a7c27e)
Location: include/linux/radix-tree.h:346
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:328
Inline: True
```
```
In lib/idr.c (ffffffff81aaf2bc)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff81ab35ae)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In lib/idr.c (ffffffff815e8fec)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff815ee7af)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:328
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
In lib/idr.c (ffffffff8160e09c)
Location: include/linux/radix-tree.h:329
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff81612eff)
Location: include/linux/radix-tree.h:329
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:329
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
In lib/idr.c (ffffffff815f17ec)
Location: include/linux/radix-tree.h:329
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff815f63e6)
Location: include/linux/radix-tree.h:329
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:329
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
In lib/idr.c (ffffffff8165e95c)
Location: include/linux/radix-tree.h:329
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff816639ba)
Location: include/linux/radix-tree.h:329
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:329
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
In lib/idr.c (ffffffff817781d4)
Location: include/linux/radix-tree.h:331
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff8177db66)
Location: include/linux/radix-tree.h:331
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:331
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:331
Inline: True
```
```
In lib/idr.c (ffffffff82020f34)
Location: include/linux/radix-tree.h:331
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff8203a2c6)
Location: include/linux/radix-tree.h:331
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:340
Inline: True
```
```
In lib/idr.c (ffffffff820a0f54)
Location: include/linux/radix-tree.h:340
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff820b8726)
Location: include/linux/radix-tree.h:340
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:340
Inline: True
```
```
In lib/idr.c (ffffffff82178f34)
Location: include/linux/radix-tree.h:340
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff82193036)
Location: include/linux/radix-tree.h:340
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e1bc)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/idr.c (ffff800010d88b30)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffff800010d8dc84)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In drivers/hwspinlock/hwspinlock_core.c (c0c61e30)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/idr.c (c0e83a48)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (c0e8831c)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5ac90)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/idr.c (c000000000ec9454)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (c000000000ed04b4)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072c738)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/idr.c (ffffffe0008b2a10)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffe0008b64c0)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:328
Inline: True
```
```
In lib/idr.c (ffffffff81a4e10c)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff81a523fe)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:328
Inline: True
```
```
In lib/idr.c (ffffffff81a0b1fc)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff81a0f4fe)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:328
Inline: True
```
```
In lib/idr.c (ffffffff81aba4fc)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff81abe7ee)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:328
Inline: True
```
```
In lib/idr.c (ffffffff81ac694c)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff81acac8e)
Location: include/linux/radix-tree.h:328
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
</ul>

## Differences
