# Function: <code>__folio_set_locked</code>

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
In mm/filemap.c (ffffffff812f291f)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/filemap.c:filemap_add_folio
```
```
In mm/shmem.c (ffffffff81316e5c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_and_acct_folio
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
In mm/filemap.c (ffffffff8135ad5f)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/filemap.c:filemap_add_folio
```
```
In mm/shmem.c (ffffffff813903fe)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
```
```
In mm/memory.c (ffffffff813bc32f)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff813f974a)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8140c890)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_add_to_page_cache
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
In mm/filemap.c (ffffffff8138c77f)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/filemap.c:filemap_add_folio
```
```
In mm/shmem.c (ffffffff813c2d4b)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
```
```
In mm/memory.c (ffffffff813f0bfd)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff8142c4ec)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8143fce8)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_add_to_page_cache
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
In mm/filemap.c (ffffffff813b62df)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/filemap.c:filemap_add_folio
```
```
In mm/shmem.c (ffffffff813ed9c3)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
```
```
In mm/memory.c (ffffffff814206e9)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff81465c27)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81479b9e)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_add_to_page_cache
```
```
In mm/ksm.c (ffffffff814929cd)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
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
