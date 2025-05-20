# Function: <code>folio_test_hwpoison</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff814075b4)
Location: include/linux/page-flags.h:576
Inline: True
Inline callers:
  - mm/hugetlb.c:__update_and_free_page
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
In mm/shmem.c (ffffffff813c07bb)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_splice_read
```
```
In mm/hugetlb.c (ffffffff81440250)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
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
In mm/shmem.c (ffffffff813eb44b)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_splice_read
```
```
In mm/hugetlb.c (ffffffff8147a047)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/memory-failure.c (ffffffff814c8229)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/memory-failure.c:is_raw_hwpoison_page_in_hugepage
```
```
In fs/hugetlbfs/inode.c (ffffffff81668fcb)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
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
