# Function: <code>maybe_unlock_mmap_for_io</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff81217e00)
Location: mm/filemap.c:2352
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
**Symbols:**

```
ffffffff81213c90-ffffffff81213cc2: maybe_unlock_mmap_for_io.isra.0.part.0 (STB_LOCAL)
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
In mm/filemap.c (ffffffff812256d1)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff81242406)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff8125c58f)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
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
In mm/filemap.c (ffffffff81253111)
Location: mm/internal.h:406
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
```
```
In mm/shmem.c (ffffffff81271138)
Location: mm/internal.h:406
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff8128bb13)
Location: mm/internal.h:406
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
In mm/filemap.c (ffffffff8125dd01)
Location: mm/internal.h:410
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
```
```
In mm/shmem.c (ffffffff8127a61c)
Location: mm/internal.h:410
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff81296acb)
Location: mm/internal.h:410
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
In mm/filemap.c (ffffffff81260ae8)
Location: mm/internal.h:435
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8127f75c)
Location: mm/internal.h:435
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff8129c667)
Location: mm/internal.h:435
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
In mm/filemap.c (ffffffff8129d493)
Location: mm/internal.h:432
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff812bda13)
Location: mm/internal.h:432
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff812dd2e3)
Location: mm/internal.h:432
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
In mm/filemap.c (ffffffff812f45de)
Location: mm/internal.h:607
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8131977e)
Location: mm/internal.h:607
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff8133cfd1)
Location: mm/internal.h:607
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
In mm/filemap.c (ffffffff8135e6c0)
Location: mm/internal.h:605
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
```
```
In mm/shmem.c (ffffffff8138d733)
Location: mm/internal.h:605
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff813b4bae)
Location: mm/internal.h:605
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
In mm/filemap.c (ffffffff81391466)
Location: mm/internal.h:676
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
```
```
In mm/shmem.c (ffffffff813c00eb)
Location: mm/internal.h:676
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff813e9bae)
Location: mm/internal.h:676
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
In mm/filemap.c (ffffffff813bb1c2)
Location: mm/internal.h:756
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
```
```
In mm/shmem.c (ffffffff813e7717)
Location: mm/internal.h:756
Inline: True
Inline callers:
  - mm/shmem.c:shmem_falloc_wait
```
```
In mm/memory.c (ffffffff81414d11)
Location: mm/internal.h:756
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b23e4)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffff8000102d6790)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffff8000102f4a88)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
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
In mm/filemap.c (c04df7d4)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (c04fca00)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (c051676c)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
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
In mm/filemap.c (c000000000368890)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (c000000000393ef4)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (c0000000003ba9d0)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
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
In mm/filemap.c (ffffffe0001d8160)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffe0001f056a)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffe000205c2e)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
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
In mm/filemap.c (ffffffff8121dd21)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8123aa56)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff81254bdf)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
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
In mm/filemap.c (ffffffff81210ed7)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8122da56)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff81247a1f)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
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
In mm/filemap.c (ffffffff8121bac1)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff812387f6)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff8125297f)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
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
In mm/filemap.c (ffffffff8122ab21)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff81247e34)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff8126234f)
Location: mm/internal.h:365
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
</details>
</li>
</ul>

## Differences
