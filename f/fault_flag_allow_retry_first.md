# Function: <code>fault_flag_allow_retry_first</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125348a)
Location: include/linux/mm.h:463
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/shmem.c (ffffffff81271138)
Location: include/linux/mm.h:463
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff8128bb16)
Location: include/linux/mm.h:463
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
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
In mm/filemap.c (ffffffff8125e093)
Location: include/linux/mm.h:488
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/shmem.c (ffffffff8127a61c)
Location: include/linux/mm.h:488
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff81296ace)
Location: include/linux/mm.h:488
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
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
In mm/filemap.c (ffffffff81260d55)
Location: include/linux/mm.h:507
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/shmem.c (ffffffff8127f75c)
Location: include/linux/mm.h:507
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff8129c66a)
Location: include/linux/mm.h:507
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
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
In mm/filemap.c (ffffffff8129d7b8)
Location: include/linux/mm.h:503
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/shmem.c (ffffffff812bda13)
Location: include/linux/mm.h:503
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff812dd2e6)
Location: include/linux/mm.h:503
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
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
In mm/filemap.c (ffffffff812f486d)
Location: include/linux/mm.h:450
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__folio_lock_or_retry
```
```
In mm/shmem.c (ffffffff8131977e)
Location: include/linux/mm.h:450
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff8133cfd4)
Location: include/linux/mm.h:450
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
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
In mm/filemap.c (ffffffff8135e9ac)
Location: include/linux/mm.h:460
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:__folio_lock_or_retry
```
```
In mm/shmem.c (ffffffff8138d733)
Location: include/linux/mm.h:460
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff813b4bb1)
Location: include/linux/mm.h:460
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
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
In mm/filemap.c (ffffffff81391741)
Location: include/linux/mm.h:460
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:__folio_lock_or_retry
```
```
In mm/shmem.c (ffffffff813c00eb)
Location: include/linux/mm.h:460
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff813e9bb1)
Location: include/linux/mm.h:460
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
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
In mm/filemap.c (ffffffff813bb4af)
Location: include/linux/mm.h:477
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:__folio_lock_or_retry
```
```
In mm/shmem.c (ffffffff813e7717)
Location: include/linux/mm.h:477
Inline: True
Inline callers:
  - mm/shmem.c:shmem_falloc_wait
```
```
In mm/memory.c (ffffffff81414d16)
Location: include/linux/mm.h:477
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
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
