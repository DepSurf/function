# Function: <code>arch_atomic_sub_and_test</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f9c57)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/memcontrol.c (ffffffff8127f925)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In fs/aio.c (ffffffff812f5c8c)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In mm/page_alloc.c (ffffffff8120c2fd)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff8130ad7c)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In mm/page_alloc.c (ffffffff81272564)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff8132cfd8)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In kernel/padata.c (ffffffff8121d564)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (ffffffff812813c4)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff8133fe28)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In kernel/rcu/tree.c (ffffffff811366f2)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In kernel/padata.c (ffffffff81249854)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/gup.c (ffffffff81287af8)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page
```
```
In mm/page_alloc.c (ffffffff812b389b)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff81379808)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In kernel/rcu/tree.c (ffffffff81131f5a)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
```
```
In kernel/padata.c (ffffffff812546e4)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (ffffffff812bf379)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff81387585)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/iomap/buffered-io.c (ffffffff813bc772)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/iomap/buffered-io.c:iomap_read_page_end_io
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
In kernel/rcu/tree.c (ffffffff811326ea)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
```
```
In kernel/padata.c (ffffffff81258c84)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (ffffffff812c441d)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In fs/aio.c (ffffffff8138e655)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/io_uring.c (ffffffff813971e0)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_timeout_cancel
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_disarm_next
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/iomap/buffered-io.c (ffffffff813c2de9)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
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
In kernel/rcu/tree.c (ffffffff81154467)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
```
```
In mm/page_alloc.c (ffffffff813082dd)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In fs/aio.c (ffffffff813dbec5)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/iomap/buffered-io.c (ffffffff814124a0)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
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
In kernel/rcu/update.c (ffffffff8117327e)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff8117a5df)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
```
```
In mm/filemap.c (ffffffff812f2815)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/gup.c (ffffffff8133706c)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_get_folio
```
```
In mm/page_alloc.c (ffffffff813705e9)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In fs/aio.c (ffffffff81465aed)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/iomap/buffered-io.c (ffffffff814885e2)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
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
In kernel/rcu/update.c (ffffffff811aaf08)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811b34a2)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
```
```
In mm/filemap.c (ffffffff8135acc8)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/shmem.c (ffffffff8138ac63)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff813ae52c)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/page_alloc.c (ffffffff813ed57b)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In fs/aio.c (ffffffff814f5b6d)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/iomap/buffered-io.c (ffffffff8151c453)
Location: arch/x86/include/asm/atomic.h:81
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
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
In kernel/rcu/update.c (ffffffff811bce28)
Location: arch/x86/include/asm/atomic.h:45
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811c5002)
Location: arch/x86/include/asm/atomic.h:45
Inline: True
```
```
In mm/filemap.c (ffffffff8138c6ec)
Location: arch/x86/include/asm/atomic.h:45
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/shmem.c (ffffffff813bd189)
Location: arch/x86/include/asm/atomic.h:45
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff813e2d7e)
Location: arch/x86/include/asm/atomic.h:45
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/page_alloc.c (ffffffff81422513)
Location: arch/x86/include/asm/atomic.h:45
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/khugepaged.c (ffffffff814804cb)
Location: arch/x86/include/asm/atomic.h:45
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff8152c8fd)
Location: arch/x86/include/asm/atomic.h:45
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/iomap/buffered-io.c (ffffffff8155465f)
Location: arch/x86/include/asm/atomic.h:45
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
Location: arch/x86/include/asm/atomic.h:45
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811d7fb2)
Location: arch/x86/include/asm/atomic.h:45
Inline: True
```
```
In mm/filemap.c (ffffffff813b624f)
Location: arch/x86/include/asm/atomic.h:45
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/shmem.c (ffffffff813e7ff9)
Location: arch/x86/include/asm/atomic.h:45
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff8140d5bb)
Location: arch/x86/include/asm/atomic.h:45
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/page_alloc.c (ffffffff8144f25c)
Location: arch/x86/include/asm/atomic.h:45
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/khugepaged.c (ffffffff814ae5db)
Location: arch/x86/include/asm/atomic.h:45
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff815617dd)
Location: arch/x86/include/asm/atomic.h:45
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/iomap/buffered-io.c (ffffffff8158a845)
Location: arch/x86/include/asm/atomic.h:45
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81215bb4)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (ffffffff81279a14)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff81338408)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In kernel/padata.c (ffffffff81208914)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (ffffffff8126b904)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff81329138)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In kernel/padata.c (ffffffff81213954)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (ffffffff812777b4)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff81335ed8)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In kernel/padata.c (ffffffff81222912)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (ffffffff812873a4)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff81348fa8)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
</details>
</li>
</ul>

## Differences
