# Function: <code>raw_atomic_sub_and_test</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811bce28)
Location: include/linux/atomic/atomic-arch-fallback.h:2238
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811c5002)
Location: include/linux/atomic/atomic-arch-fallback.h:2238
Inline: True
```
```
In mm/filemap.c (ffffffff8138c6ec)
Location: include/linux/atomic/atomic-arch-fallback.h:2238
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/shmem.c (ffffffff813bd189)
Location: include/linux/atomic/atomic-arch-fallback.h:2238
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff813e2d7e)
Location: include/linux/atomic/atomic-arch-fallback.h:2238
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/page_alloc.c (ffffffff81422513)
Location: include/linux/atomic/atomic-arch-fallback.h:2238
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/khugepaged.c (ffffffff814804cb)
Location: include/linux/atomic/atomic-arch-fallback.h:2238
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff8152c8fd)
Location: include/linux/atomic/atomic-arch-fallback.h:2238
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/iomap/buffered-io.c (ffffffff8155465f)
Location: include/linux/atomic/atomic-arch-fallback.h:2238
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
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
In kernel/rcu/update.c (ffffffff811cd248)
Location: include/linux/atomic/atomic-arch-fallback.h:2247
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811d7fb2)
Location: include/linux/atomic/atomic-arch-fallback.h:2247
Inline: True
```
```
In mm/filemap.c (ffffffff813b624f)
Location: include/linux/atomic/atomic-arch-fallback.h:2247
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/shmem.c (ffffffff813e7ff9)
Location: include/linux/atomic/atomic-arch-fallback.h:2247
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff8140d5bb)
Location: include/linux/atomic/atomic-arch-fallback.h:2247
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/page_alloc.c (ffffffff8144f25c)
Location: include/linux/atomic/atomic-arch-fallback.h:2247
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/khugepaged.c (ffffffff814ae5db)
Location: include/linux/atomic/atomic-arch-fallback.h:2247
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff815617dd)
Location: include/linux/atomic/atomic-arch-fallback.h:2247
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/iomap/buffered-io.c (ffffffff8158a845)
Location: include/linux/atomic/atomic-arch-fallback.h:2247
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
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
