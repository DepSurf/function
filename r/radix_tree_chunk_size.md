# Function: <code>radix_tree_chunk_size</code>

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
In mm/filemap.c (ffffffff8118d0d0)
Location: include/linux/radix-tree.h:395
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_pages
```
```
In mm/shmem.c (ffffffff811a8886)
Location: include/linux/radix-tree.h:395
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
```
In mm/backing-dev.c (ffffffff811af877)
Location: include/linux/radix-tree.h:395
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In fs/fs-writeback.c (0)
Location: include/linux/radix-tree.h:395
Inline: True
```
```
In lib/radix-tree.c (ffffffff813ee863)
Location: include/linux/radix-tree.h:395
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
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
In mm/filemap.c (ffffffff811a17fd)
Location: include/linux/radix-tree.h:444
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/shmem.c (0)
Location: include/linux/radix-tree.h:444
Inline: True
```
```
In mm/backing-dev.c (ffffffff811c8c9f)
Location: include/linux/radix-tree.h:444
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8121ae03)
Location: include/linux/radix-tree.h:444
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (0)
Location: include/linux/radix-tree.h:444
Inline: True
```
```
In lib/radix-tree.c (ffffffff8143497d)
Location: include/linux/radix-tree.h:444
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
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
In mm/filemap.c (ffffffff811b1670)
Location: include/linux/radix-tree.h:442
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/page-writeback.c (0)
Location: include/linux/radix-tree.h:442
Inline: True
```
```
In mm/shmem.c (ffffffff811cfcb8)
Location: include/linux/radix-tree.h:442
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811d8dad)
Location: include/linux/radix-tree.h:442
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8122e1f2)
Location: include/linux/radix-tree.h:442
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (0)
Location: include/linux/radix-tree.h:442
Inline: True
```
```
In lib/radix-tree.c (ffffffff81450eae)
Location: include/linux/radix-tree.h:442
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
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
In mm/filemap.c (ffffffff811b78d3)
Location: include/linux/radix-tree.h:487
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/page-writeback.c (0)
Location: include/linux/radix-tree.h:487
Inline: True
```
```
In mm/shmem.c (ffffffff811d93f5)
Location: include/linux/radix-tree.h:487
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811e129f)
Location: include/linux/radix-tree.h:487
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8123a4bd)
Location: include/linux/radix-tree.h:487
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (0)
Location: include/linux/radix-tree.h:487
Inline: True
```
```
In lib/idr.c (ffffffff818ecfc8)
Location: include/linux/radix-tree.h:487
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff818f0ae5)
Location: include/linux/radix-tree.h:487
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
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
In mm/filemap.c (ffffffff811cbe55)
Location: include/linux/radix-tree.h:502
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (0)
Location: include/linux/radix-tree.h:502
Inline: True
```
```
In mm/shmem.c (ffffffff811ee6c5)
Location: include/linux/radix-tree.h:502
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811f72af)
Location: include/linux/radix-tree.h:502
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff812591dc)
Location: include/linux/radix-tree.h:502
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (0)
Location: include/linux/radix-tree.h:502
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:502
Inline: True
```
```
In lib/idr.c (ffffffff81972fe8)
Location: include/linux/radix-tree.h:502
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81976f32)
Location: include/linux/radix-tree.h:502
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
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
In mm/filemap.c (ffffffff811ecf8a)
Location: include/linux/radix-tree.h:491
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (0)
Location: include/linux/radix-tree.h:491
Inline: True
```
```
In mm/shmem.c (ffffffff81213b07)
Location: include/linux/radix-tree.h:491
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff812184dd)
Location: include/linux/radix-tree.h:491
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8127d603)
Location: include/linux/radix-tree.h:491
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memfd.c (ffffffff812941e5)
Location: include/linux/radix-tree.h:491
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/fs-writeback.c (0)
Location: include/linux/radix-tree.h:491
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:491
Inline: True
```
```
In lib/idr.c (ffffffff819cf579)
Location: include/linux/radix-tree.h:491
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff819d36d2)
Location: include/linux/radix-tree.h:491
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
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
In mm/backing-dev.c (ffffffff8122b427)
Location: include/linux/radix-tree.h:392
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:392
Inline: True
```
```
In lib/idr.c (ffffffff81a08480)
Location: include/linux/radix-tree.h:392
Inline: True
Inline callers:
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (0)
Location: include/linux/radix-tree.h:392
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
In mm/backing-dev.c (ffffffff8123b075)
Location: include/linux/radix-tree.h:379
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:379
Inline: True
```
```
In lib/idr.c (ffffffff81a77dc4)
Location: include/linux/radix-tree.h:379
Inline: True
Inline callers:
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (0)
Location: include/linux/radix-tree.h:379
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
In mm/backing-dev.c (ffffffff81249599)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:361
Inline: True
```
```
In lib/idr.c (ffffffff81aaf1b4)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (0)
Location: include/linux/radix-tree.h:361
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
In mm/backing-dev.c (ffffffff81277240)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_unregister
```
```
In lib/idr.c (ffffffff815e8ff8)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff815ee691)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:361
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
In mm/backing-dev.c (ffffffff81281b30)
Location: include/linux/radix-tree.h:362
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_unregister
```
```
In lib/idr.c (ffffffff8160e0a8)
Location: include/linux/radix-tree.h:362
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81612de1)
Location: include/linux/radix-tree.h:362
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:362
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
In mm/backing-dev.c (ffffffff81286f7b)
Location: include/linux/radix-tree.h:362
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In lib/idr.c (ffffffff815f17f8)
Location: include/linux/radix-tree.h:362
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff815f62c1)
Location: include/linux/radix-tree.h:362
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:362
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
In mm/backing-dev.c (ffffffff812c6537)
Location: include/linux/radix-tree.h:362
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In lib/idr.c (ffffffff8165e968)
Location: include/linux/radix-tree.h:362
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81663891)
Location: include/linux/radix-tree.h:362
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:362
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
In mm/backing-dev.c (ffffffff813231e7)
Location: include/linux/radix-tree.h:364
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In lib/idr.c (ffffffff817781e8)
Location: include/linux/radix-tree.h:364
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff8177da00)
Location: include/linux/radix-tree.h:364
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:364
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
In mm/backing-dev.c (ffffffff813979f7)
Location: include/linux/radix-tree.h:364
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:364
Inline: True
```
```
In lib/idr.c (ffffffff82020f48)
Location: include/linux/radix-tree.h:364
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff8203a150)
Location: include/linux/radix-tree.h:364
Inline: True
Inline callers:
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
In mm/backing-dev.c (ffffffff813ca987)
Location: include/linux/radix-tree.h:373
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:373
Inline: True
```
```
In lib/idr.c (ffffffff820a0f68)
Location: include/linux/radix-tree.h:373
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff820b85b0)
Location: include/linux/radix-tree.h:373
Inline: True
Inline callers:
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
In mm/backing-dev.c (ffffffff813f53f7)
Location: include/linux/radix-tree.h:373
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:373
Inline: True
```
```
In lib/idr.c (ffffffff82178f48)
Location: include/linux/radix-tree.h:373
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff82192ec0)
Location: include/linux/radix-tree.h:373
Inline: True
Inline callers:
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
In mm/backing-dev.c (ffff8000102decc8)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/pinctrl/core.c (ffff80001068d104)
Location: include/linux/radix-tree.h:361
Inline: True
```
```
In drivers/pinctrl/pinmux.c (ffff80001068fe7c)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:361
Inline: True
```
```
In lib/idr.c (ffff800010d88a00)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (0)
Location: include/linux/radix-tree.h:361
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
In mm/backing-dev.c (c0503c28)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/pinctrl/core.c (c082f1b0)
Location: include/linux/radix-tree.h:361
Inline: True
```
```
In drivers/pinctrl/pinmux.c (c0831c08)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:361
Inline: True
```
```
In lib/idr.c (c0e838b8)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (0)
Location: include/linux/radix-tree.h:361
Inline: True
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
In mm/backing-dev.c (c00000000039e5d8)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/pinctrl/core.c (c000000000825ea0)
Location: include/linux/radix-tree.h:361
Inline: True
```
```
In drivers/pinctrl/pinmux.c (c00000000082b600)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:361
Inline: True
```
```
In lib/idr.c (c000000000ec92a4)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (0)
Location: include/linux/radix-tree.h:361
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
In mm/backing-dev.c (ffffffe0001f6b42)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/pinctrl/core.c (ffffffe0004992e4)
Location: include/linux/radix-tree.h:361
Inline: True
```
```
In drivers/pinctrl/pinmux.c (ffffffe00049ba64)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:361
Inline: True
```
```
In lib/idr.c (ffffffe0008b294c)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (0)
Location: include/linux/radix-tree.h:361
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
In mm/backing-dev.c (ffffffff81241be9)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:361
Inline: True
```
```
In lib/idr.c (ffffffff81a4e004)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (0)
Location: include/linux/radix-tree.h:361
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
In mm/backing-dev.c (ffffffff81234bd9)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:361
Inline: True
```
```
In lib/idr.c (ffffffff81a0b0f4)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (0)
Location: include/linux/radix-tree.h:361
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
In mm/backing-dev.c (ffffffff8123f989)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:361
Inline: True
```
```
In lib/idr.c (ffffffff81aba3f4)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (0)
Location: include/linux/radix-tree.h:361
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
In mm/backing-dev.c (ffffffff8124f109)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:361
Inline: True
```
```
In lib/idr.c (ffffffff81ac6844)
Location: include/linux/radix-tree.h:361
Inline: True
Inline callers:
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (0)
Location: include/linux/radix-tree.h:361
Inline: True
```
</details>
</li>
</ul>

## Differences
