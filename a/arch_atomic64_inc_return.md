# Function: <code>arch_atomic64_inc_return</code>

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
In arch/x86/mm/tlb.c (ffffffff8108b6d8)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82ceac27)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810a42fb)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff8117c928)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/bpf/bpf_iter.c (ffffffff81215756)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff8123a60f)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff81246dad)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8126e8ed)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff812a5981)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812bbc5f)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff812e5357)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81308207)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/super.c (ffffffff81316595)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffffffff814740ca)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff8147a1e0)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8147e5d2)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/firmware/efi/cper.c (ffffffff819be985)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff819f9924)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_gen_cookie
```
```
In net/core/sock_diag.c (ffffffff81a3390e)
Location: include/linux/atomic-arch-fallback.h:1391
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/unix/scm.c (ffffffff81b298eb)
Location: include/linux/atomic-arch-fallback.h:1391
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
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82fd8472)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109ff17)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff811797d8)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/bpf/bpf_iter.c (ffffffff81217420)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff81243a43)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff8125141a)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff812792e7)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff812b0dfb)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812c770f)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff812f0720)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81313fa9)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/super.c (ffffffff81321ab5)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffffffff8148ea1d)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81494ed3)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81499a1d)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/firmware/efi/cper.c (ffffffff819c0335)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/unix/scm.c (ffffffff81b3821b)
Location: include/linux/atomic-arch-fallback.h:1461
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
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff831e2e68)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810a0c2a)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff8117a338)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/bpf/bpf_iter.c (ffffffff8121a890)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff812489de)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff81255522)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8127e2d3)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff812b6448)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812ce088)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff812f6ae9)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8131a168)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/super.c (ffffffff81327b45)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffffffff8149444d)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81499f33)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8149ec4d)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/firmware/efi/cper.c (ffffffff819a4a45)
Location: include/linux/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/unix/scm.c (ffffffff81b25ebb)
Location: include/linux/atomic-arch-fallback.h:1461
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
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff832c680b)
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810b209d)
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff811a1c58)
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/bpf/bpf_iter.c (ffffffff81251690)
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff812837e2)
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff81290f63)
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff812f7e74)
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81313508)
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff81341145)
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81366e6c)
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/super.c (ffffffff81375115)
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffffffff814ec16d)
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff814f1953)
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff814f6ead)
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/genhd.c (ffffffff815e3ea7)
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In drivers/firmware/efi/cper.c (ffffffff81a51d15)
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/unix/scm.c (ffffffff81bebb0b)
Location: include/linux/atomic/atomic-arch-fallback.h:1461
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff834795a9)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810c89f4)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff811d264c)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/bpf/bpf_iter.c (ffffffff81299293)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff812d67f6)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff812e635e)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff8135dc19)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8137e9de)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate_device.c (ffffffff813b7f58)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
```
```
In mm/userfaultfd.c (ffffffff813e4352)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/super.c (ffffffff813f4405)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffffffff8157aec4)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_entry_unlinked
```
```
In fs/fuse/file.c (ffffffff81581398)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81586d3d)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/genhd.c (ffffffff81693182)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In drivers/firmware/efi/cper.c (ffffffff81bc0d05)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/unix/scm.c (ffffffff81d83feb)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea36f2)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810e5d51)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff812164f3)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f5023)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff8133f5cf)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/rmap.c (ffffffff813d894d)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In fs/super.c (ffffffff8147d4d5)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffffffff816206c4)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_entry_unlinked
```
```
In fs/fuse/file.c (ffffffff816271e8)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
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
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/genhd.c (ffffffff8175291b)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In drivers/firmware/efi/cper.c (ffffffff81d645f5)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/unix/scm.c (ffffffff81f5186b)
Location: include/linux/atomic/atomic-arch-fallback.h:1559
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
