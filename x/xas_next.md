# Function: <code>xas_next</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fedeb)
Location: include/linux/xarray.h:1608
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/shmem.c (ffffffff81221607)
Location: include/linux/xarray.h:1608
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8125be74)
Location: include/linux/xarray.h:1608
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812825c6)
Location: include/linux/xarray.h:1608
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff8128f98f)
Location: include/linux/xarray.h:1608
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/filemap.c (ffffffff81214fb8)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/shmem.c (ffffffff81230e43)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81277037)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8129e580)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812aaa2f)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/filemap.c (ffffffff81222dfa)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/shmem.c (ffffffff8123f04b)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81286b17)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812ade24)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812bbfd3)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/filemap.c (ffffffff8125070d)
Location: include/linux/xarray.h:1776
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/shmem.c (ffffffff8126c90d)
Location: include/linux/xarray.h:1776
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff812b9097)
Location: include/linux/xarray.h:1776
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812e495a)
Location: include/linux/xarray.h:1776
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812f14f6)
Location: include/linux/xarray.h:1776
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/filemap.c (ffffffff8125a5fd)
Location: include/linux/xarray.h:1810
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/shmem.c (ffffffff81277354)
Location: include/linux/xarray.h:1810
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff812c4849)
Location: include/linux/xarray.h:1810
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812ef354)
Location: include/linux/xarray.h:1810
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812fda4e)
Location: include/linux/xarray.h:1810
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/filemap.c (ffffffff8125f8c5)
Location: include/linux/xarray.h:1812
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/shmem.c (ffffffff8127c3bc)
Location: include/linux/xarray.h:1812
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff812cb4e6)
Location: include/linux/xarray.h:1812
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812f5fc4)
Location: include/linux/xarray.h:1812
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff813047c9)
Location: include/linux/xarray.h:1812
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In lib/iov_iter.c (ffffffff815ab30b)
Location: include/linux/xarray.h:1812
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
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
In mm/filemap.c (ffffffff8129b2ed)
Location: include/linux/xarray.h:1812
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/shmem.c (ffffffff812ba5c9)
Location: include/linux/xarray.h:1812
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81310577)
Location: include/linux/xarray.h:1812
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff813405a8)
Location: include/linux/xarray.h:1812
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff8134e4ff)
Location: include/linux/xarray.h:1812
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In lib/iov_iter.c (ffffffff81614c93)
Location: include/linux/xarray.h:1812
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
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
In mm/filemap.c (ffffffff812f2b2e)
Location: include/linux/xarray.h:1839
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/swap_state.c (ffffffff8137b2a2)
Location: include/linux/xarray.h:1839
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff813c4c2b)
Location: include/linux/xarray.h:1839
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In lib/iov_iter.c (ffffffff816e193c)
Location: include/linux/xarray.h:1839
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
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
In mm/filemap.c (ffffffff8135cefe)
Location: include/linux/xarray.h:1854
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/swap_state.c (ffffffff813f8b84)
Location: include/linux/xarray.h:1854
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff81449480)
Location: include/linux/xarray.h:1854
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In lib/iov_iter.c (ffffffff817d25d5)
Location: include/linux/xarray.h:1854
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
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
In mm/filemap.c (ffffffff8138ef3a)
Location: include/linux/xarray.h:1855
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/swap_state.c (ffffffff8142b96d)
Location: include/linux/xarray.h:1855
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff8147fda9)
Location: include/linux/xarray.h:1855
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In lib/iov_iter.c (ffffffff81810cd5)
Location: include/linux/xarray.h:1855
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
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
In mm/filemap.c (ffffffff813b85ea)
Location: include/linux/xarray.h:1873
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/swap_state.c (ffffffff814650c7)
Location: include/linux/xarray.h:1873
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff814969a3)
Location: include/linux/xarray.h:1873
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/khugepaged.c (ffffffff814adeb2)
Location: include/linux/xarray.h:1873
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In lib/iov_iter.c (ffffffff81857102)
Location: include/linux/xarray.h:1873
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
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
In mm/filemap.c (ffff8000102b078c)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/shmem.c (ffff8000102d16f0)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffff80001032136c)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffff80001034fe10)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffff80001035d2f0)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/filemap.c (c04dd338)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/shmem.c (c04f8adc)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (c0539c38)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (0)
Location: include/linux/xarray.h:1737
Inline: False
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
In mm/filemap.c (c000000000365cd0)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/shmem.c (c00000000038f14c)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (c0000000003f68cc)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (c0000000004332b4)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (c000000000448654)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/filemap.c (ffffffe0001d631e)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/shmem.c (ffffffe0001edb42)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffe000222730)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (0)
Location: include/linux/xarray.h:1737
Inline: False
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
In mm/filemap.c (ffffffff8121b44a)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/shmem.c (ffffffff8123769b)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127f167)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812a6404)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812b45b3)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/filemap.c (ffffffff8120e63a)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/shmem.c (ffffffff8122a52b)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81270f87)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff81297eb4)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812a5630)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/filemap.c (ffffffff812191ea)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/shmem.c (ffffffff8123543b)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127cf07)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812a4214)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812b23c3)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/filemap.c (ffffffff8122832c)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
```
```
In mm/shmem.c (ffffffff8124554b)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8128cac7)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812b3984)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812c27ca)
Location: include/linux/xarray.h:1737
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
</details>
</li>
</ul>

## Differences
