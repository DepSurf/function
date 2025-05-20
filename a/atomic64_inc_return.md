# Function: <code>atomic64_inc_return</code>

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
In arch/x86/mm/tlb.c (ffffffff8107daee)
Location: include/asm-generic/atomic-instrumented.h:190
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826f2171)
Location: include/asm-generic/atomic-instrumented.h:190
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8108ac74)
Location: include/asm-generic/atomic-instrumented.h:190
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff81146d8c)
Location: include/asm-generic/atomic-instrumented.h:190
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/events/core.c (ffffffff811d8dcc)
Location: include/asm-generic/atomic-instrumented.h:190
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/workingset.c (ffffffff81225845)
Location: include/asm-generic/atomic-instrumented.h:190
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8123f180)
Location: include/asm-generic/atomic-instrumented.h:190
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In fs/super.c (ffffffff8129c1e5)
Location: include/asm-generic/atomic-instrumented.h:190
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In drivers/firmware/efi/cper.c (ffffffff818483e5)
Location: include/asm-generic/atomic-instrumented.h:190
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock_diag.c (ffffffff818b8e82)
Location: include/asm-generic/atomic-instrumented.h:190
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/unix/garbage.c (ffffffff8195d6b9)
Location: include/asm-generic/atomic-instrumented.h:190
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_inflight
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81088328)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c1968)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096c67)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff8115ef4b)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/events/core.c (ffffffff812025e3)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/workingset.c (ffffffff81249fca)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff81265a0d)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In fs/super.c (ffffffff812cddb5)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffffffff8140ae87)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81410520)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81413e7f)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/firmware/efi/cper.c (ffffffff818b8895)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock_diag.c (ffffffff8192e11e)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/unix/scm.c (ffffffff819fdebb)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In arch/x86/mm/tlb.c (ffffffff81088fd8)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c7de1)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109d49b)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff8116abae)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/events/core.c (ffffffff8120f413)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/workingset.c (ffffffff81258419)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8127432c)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In fs/super.c (ffffffff812df7e5)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffffffff81424a59)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff8142a130)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8142df1f)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/firmware/efi/cper.c (ffffffff818eb295)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock_diag.c (ffffffff819603ae)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/unix/scm.c (ffffffff81a34aab)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In arch/x86/mm/tlb.c (ffffffff8108b6d8)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82ceac27)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810a42fb)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff8117c928)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/bpf/bpf_iter.c (ffffffff81215756)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff8123a60f)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff81246dad)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8126e8ed)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff812a5981)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812bbc5f)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff812e5357)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81308207)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/super.c (ffffffff81316595)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffffffff814740ca)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff8147a1e0)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8147e5d2)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/firmware/efi/cper.c (ffffffff819be985)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff819f9924)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_gen_cookie
```
```
In net/core/sock_diag.c (ffffffff81a3390e)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/unix/scm.c (ffffffff81b298eb)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In arch/x86/mm/tlb.c (ffffffff8108b728)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82fd8472)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109ff17)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff811797d8)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/bpf/bpf_iter.c (ffffffff81217420)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff81243a43)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff8125141a)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff812792e7)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff812b0dfb)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812c770f)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff812f0720)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81313fa9)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/super.c (ffffffff81321ab5)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffffffff8148ea1d)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81494ed3)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81499a1d)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/firmware/efi/cper.c (ffffffff819c0335)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/unix/scm.c (ffffffff81b3821b)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In arch/x86/mm/tlb.c (ffffffff8108c307)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff831e2e68)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810a0c2a)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff8117a338)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/bpf/bpf_iter.c (ffffffff8121a890)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff812489de)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff81255522)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8127e2d3)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff812b6448)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812ce088)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff812f6ae9)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8131a168)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/super.c (ffffffff81327b45)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffffffff8149444d)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81499f33)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8149ec4d)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/firmware/efi/cper.c (ffffffff819a4a45)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/unix/scm.c (ffffffff81b25ebb)
Location: include/asm-generic/atomic-instrumented.h:1058
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In arch/x86/mm/tlb.c (ffffffff8109bb30)
Location: include/linux/atomic/atomic-instrumented.h:764
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff832c680b)
Location: include/linux/atomic/atomic-instrumented.h:764
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810b209d)
Location: include/linux/atomic/atomic-instrumented.h:764
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff811a1c58)
Location: include/linux/atomic/atomic-instrumented.h:764
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/bpf/bpf_iter.c (ffffffff81251690)
Location: include/linux/atomic/atomic-instrumented.h:764
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff812837e2)
Location: include/linux/atomic/atomic-instrumented.h:764
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/rmap.c (ffffffff812f7c8c)
Location: include/linux/atomic/atomic-instrumented.h:764
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In fs/fuse/dir.c (ffffffff814ec16d)
Location: include/linux/atomic/atomic-instrumented.h:764
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff814f1953)
Location: include/linux/atomic/atomic-instrumented.h:764
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff814f6ead)
Location: include/linux/atomic/atomic-instrumented.h:764
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/genhd.c (ffffffff815e3ea7)
Location: include/linux/atomic/atomic-instrumented.h:764
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In drivers/firmware/efi/cper.c (ffffffff81a51d15)
Location: include/linux/atomic/atomic-instrumented.h:764
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
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
In arch/x86/mm/tlb.c (ffffffff810aefa7)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff834795a9)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810c89f4)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff811d264c)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/bpf/bpf_iter.c (ffffffff81299293)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff812d67f6)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/rmap.c (ffffffff8135dace)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In fs/fuse/dir.c (ffffffff8157aec4)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_entry_unlinked
```
```
In fs/fuse/file.c (ffffffff81581398)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81586d3d)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/genhd.c (ffffffff81693182)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In drivers/firmware/efi/cper.c (ffffffff81bc0d05)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
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
In arch/x86/mm/tlb.c (ffffffff810c9347)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea36f2)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810e5d51)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff812164f3)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f5023)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff8133f5cf)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/rmap.c (ffffffff813d894d)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In fs/fuse/dir.c (ffffffff816206c4)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_entry_unlinked
```
```
In fs/fuse/file.c (ffffffff816271e8)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_read_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8162cfcd)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/genhd.c (ffffffff8175291b)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In drivers/firmware/efi/cper.c (ffffffff81d645f5)
Location: include/linux/atomic/atomic-instrumented.h:814
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
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
In arch/x86/mm/tlb.c (ffffffff810cc9e5)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff836c7982)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810f14cd)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff8122be33)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/bpf/bpf_iter.c (ffffffff81322dc7)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff81370704)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/rmap.c (ffffffff8140ad57)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - mm/rmap.c:set_tlb_ubc_flush_pending
```
```
In fs/fuse/dir.c (ffffffff81658b14)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_entry_unlinked
```
```
In fs/fuse/file.c (ffffffff8165f5a8)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_read_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff816651fd)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/genhd.c (ffffffff8178eade)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In drivers/xen/grant-table.c (ffffffff81a6371a)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/firmware/efi/cper.c (ffffffff81dcf725)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
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
In arch/x86/mm/tlb.c (ffffffff810d507e)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff838f8582)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810fa8af)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff81243e63)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/bpf/bpf_iter.c (ffffffff81346cf7)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff81399a04)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/rmap.c (ffffffff81437487)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
```
```
In fs/namespace.c (ffffffff81511082)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fuse/dir.c (ffffffff81692854)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_entry_unlinked
```
```
In fs/fuse/file.c (ffffffff816993e8)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_read_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8169f4fd)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/genhd.c (ffffffff817d13cd)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In drivers/xen/grant-table.c (ffffffff81ab5f69)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c97598)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_file_alloc
```
```
In drivers/firmware/efi/cper.c (ffffffff81e88455)
Location: include/linux/atomic/atomic-instrumented.h:2014
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
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
In kernel/cgroup/pids.c (ffff8000101dece8)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/events/core.c (ffff8000102973c0)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_output_sample
```
```
In mm/workingset.c (ffff8000102f01f8)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/super.c (ffff8000103863b8)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffff800010508114)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffff80001050e12c)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffff8000105125a0)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/firmware/efi/cper.c (ffff800010b5e8b4)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock_diag.c (ffff800010c03c48)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/unix/scm.c (ffff800010cf527c)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In kernel/cgroup/pids.c (c0420774)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/events/core.c (c04c7548)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/fuse/dir.c (c06c4144)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (c06c973c)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (c06cd698)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In net/core/sock_diag.c (c0d1cfb8)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
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
In kernel/cgroup/pids.c (c00000000024ce10)
Location: include/linux/atomic-fallback.h:1451
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/events/core.c (c000000000346cb8)
Location: include/linux/atomic-fallback.h:1451
Inline: True
```
```
In mm/workingset.c (c0000000003b4ba8)
Location: include/linux/atomic-fallback.h:1451
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/super.c (c00000000047c7a4)
Location: include/linux/atomic-fallback.h:1451
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (c00000000064d970)
Location: include/linux/atomic-fallback.h:1451
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (c000000000655028)
Location: include/linux/atomic-fallback.h:1451
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (c00000000065a23c)
Location: include/linux/atomic-fallback.h:1451
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In net/core/sock_diag.c (c000000000ced650)
Location: include/linux/atomic-fallback.h:1451
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/unix/scm.c (c000000000e1b370)
Location: include/linux/atomic-fallback.h:1451
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In kernel/cgroup/pids.c (ffffffe00015609e)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/events/core.c (ffffffe0001ce742)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In mm/workingset.c (ffffffe000203c0c)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/super.c (ffffffe000258ce6)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffffffe000373e6c)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffe000378df6)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffe00037c5ea)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In net/core/sock_diag.c (ffffffe00078254a)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
```
```
In net/unix/scm.c (ffffffe000840dcc)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In arch/x86/mm/tlb.c (ffffffff81087f98)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828b2d79)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096dbb)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff811631ce)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/events/core.c (ffffffff81207a33)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/workingset.c (ffffffff81250a69)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8126c97c)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In fs/super.c (ffffffff812d7dc5)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffffffff8141d039)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81422710)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff814264ff)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In net/core/sock_diag.c (ffffffff8190037e)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/unix/scm.c (ffffffff819d413b)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In arch/x86/mm/tlb.c (ffffffff81076bf8)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828aaefa)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8108583b)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff8115641e)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/events/core.c (ffffffff811fab63)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/workingset.c (ffffffff812439e9)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8125e9da)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In fs/super.c (ffffffff812c8a45)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffffffff8140dab9)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81413190)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81416f7f)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/firmware/efi/cper.c (ffffffff81845995)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock_diag.c (ffffffff818ba1ae)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/unix/scm.c (ffffffff81990efb)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In arch/x86/mm/tlb.c (ffffffff81087f48)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c5c78)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096d6b)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff81160f9e)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/events/core.c (ffffffff81205803)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/workingset.c (ffffffff8124e809)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8126a71c)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In fs/super.c (ffffffff812d5bd5)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffffffff814191d9)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff8141e8b0)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8142269f)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/firmware/efi/cper.c (ffffffff818e00f5)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock_diag.c (ffffffff819513ae)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/unix/scm.c (ffffffff81a3ebbb)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In arch/x86/mm/tlb.c (ffffffff8108a19f)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c8e1e)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109ec0b)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff8116e3ee)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/events/core.c (ffffffff81214673)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/workingset.c (ffffffff8125e179)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff81279ec2)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In fs/super.c (ffffffff812e6be5)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffffffff8142ff49)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81435620)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff814394cf)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/firmware/efi/cper.c (ffffffff818fcb95)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock_diag.c (ffffffff81972d9e)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/unix/scm.c (ffffffff81a4a67b)
Location: include/linux/atomic-fallback.h:1392
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
```
</details>
</li>
</ul>

## Differences
