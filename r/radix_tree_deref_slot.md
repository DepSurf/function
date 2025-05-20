# Function: <code>radix_tree_deref_slot</code>

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
In mm/filemap.c (ffffffff8118cf96)
Location: include/linux/radix-tree.h:194
Inline: True
Inline callers:
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_pages
```
```
In mm/shmem.c (ffffffff811a881a)
Location: include/linux/radix-tree.h:194
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
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
In mm/filemap.c (ffffffff811a1722)
Location: include/linux/radix-tree.h:197
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/shmem.c (ffffffff811bf63e)
Location: include/linux/radix-tree.h:197
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8121c6c0)
Location: include/linux/radix-tree.h:197
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/filemap.c (ffffffff811b1592)
Location: include/linux/radix-tree.h:231
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/shmem.c (ffffffff811cfced)
Location: include/linux/radix-tree.h:231
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8122e0e4)
Location: include/linux/radix-tree.h:231
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/filemap.c (ffffffff811b7832)
Location: include/linux/radix-tree.h:236
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/shmem.c (ffffffff811d9429)
Location: include/linux/radix-tree.h:236
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8123a3be)
Location: include/linux/radix-tree.h:236
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/filemap.c (ffffffff811cbdb2)
Location: include/linux/radix-tree.h:235
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/shmem.c (ffffffff811ee6ff)
Location: include/linux/radix-tree.h:235
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812590de)
Location: include/linux/radix-tree.h:235
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:235
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
In mm/filemap.c (ffffffff811ece82)
Location: include/linux/radix-tree.h:239
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/shmem.c (ffffffff81213b3d)
Location: include/linux/radix-tree.h:239
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8127d44d)
Location: include/linux/radix-tree.h:239
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memfd.c (ffffffff8129421f)
Location: include/linux/radix-tree.h:239
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:239
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:178
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:165
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:165
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:165
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:166
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:166
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:166
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:168
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:168
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:177
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:177
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
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e140)
Location: include/linux/radix-tree.h:165
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
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
In drivers/hwspinlock/hwspinlock_core.c (c0c61e18)
Location: include/linux/radix-tree.h:165
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
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
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5abe0)
Location: include/linux/radix-tree.h:165
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
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
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072c6ca)
Location: include/linux/radix-tree.h:165
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:165
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:165
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:165
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:165
Inline: True
```
</details>
</li>
</ul>

## Differences
