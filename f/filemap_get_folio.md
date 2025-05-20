# Function: <code>filemap_get_folio</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f403e)
Location: include/linux/pagemap.h:528
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8131712a)
Location: include/linux/pagemap.h:528
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
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
In mm/filemap.c (ffffffff8135e32f)
Location: include/linux/pagemap.h:525
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8138da32)
Location: include/linux/pagemap.h:525
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/swap_state.c (ffffffff813f9609)
Location: include/linux/pagemap.h:525
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/swapfile.c (ffffffff813ffca0)
Location: include/linux/pagemap.h:525
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
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
In mm/filemap.c (ffffffff8139109f)
Location: include/linux/pagemap.h:532
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff813c1bc2)
Location: include/linux/pagemap.h:532
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/swap_state.c (ffffffff8142c354)
Location: include/linux/pagemap.h:532
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/swapfile.c (ffffffff81432b42)
Location: include/linux/pagemap.h:532
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff81445127)
Location: include/linux/pagemap.h:532
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/huge_memory.c (ffffffff814780c6)
Location: include/linux/pagemap.h:532
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
```
```
In fs/hugetlbfs/inode.c (ffffffff8162f59b)
Location: include/linux/pagemap.h:532
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/filemap.c (ffffffff813bae3f)
Location: include/linux/pagemap.h:650
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff813ec93f)
Location: include/linux/pagemap.h:650
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/swap_state.c (ffffffff81465abb)
Location: include/linux/pagemap.h:650
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/swapfile.c (ffffffff8146bf61)
Location: include/linux/pagemap.h:650
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff8147b570)
Location: include/linux/pagemap.h:650
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
```
```
In mm/huge_memory.c (ffffffff814a7813)
Location: include/linux/pagemap.h:650
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
```
```
In fs/hugetlbfs/inode.c (ffffffff81668ab6)
Location: include/linux/pagemap.h:650
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
</details>
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
