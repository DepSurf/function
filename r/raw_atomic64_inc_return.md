# Function: <code>raw_atomic64_inc_return</code>

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
In arch/x86/mm/tlb.c (ffffffff810cc9e5)
Location: include/linux/atomic/atomic-arch-fallback.h:3116
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff836c7982)
Location: include/linux/atomic/atomic-arch-fallback.h:3116
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810f14cd)
Location: include/linux/atomic/atomic-arch-fallback.h:3116
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff8122be33)
Location: include/linux/atomic/atomic-arch-fallback.h:3116
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/bpf/bpf_iter.c (ffffffff81322dc7)
Location: include/linux/atomic/atomic-arch-fallback.h:3116
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff81370704)
Location: include/linux/atomic/atomic-arch-fallback.h:3116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/rmap.c (ffffffff8140ad57)
Location: include/linux/atomic/atomic-arch-fallback.h:3116
Inline: True
Inline callers:
  - mm/rmap.c:set_tlb_ubc_flush_pending
```
```
In fs/super.c (ffffffff814b2295)
Location: include/linux/atomic/atomic-arch-fallback.h:3116
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/fuse/dir.c (ffffffff81658b14)
Location: include/linux/atomic/atomic-arch-fallback.h:3116
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_entry_unlinked
```
```
In fs/fuse/file.c (ffffffff8165f5a8)
Location: include/linux/atomic/atomic-arch-fallback.h:3116
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
Location: include/linux/atomic/atomic-arch-fallback.h:3116
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/genhd.c (ffffffff8178eade)
Location: include/linux/atomic/atomic-arch-fallback.h:3116
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In drivers/xen/grant-table.c (ffffffff81a6371a)
Location: include/linux/atomic/atomic-arch-fallback.h:3116
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/firmware/efi/cper.c (ffffffff81dcf725)
Location: include/linux/atomic/atomic-arch-fallback.h:3116
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/unix/scm.c (ffffffff81fb11eb)
Location: include/linux/atomic/atomic-arch-fallback.h:3116
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
Location: include/linux/atomic/atomic-arch-fallback.h:3121
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff838f8582)
Location: include/linux/atomic/atomic-arch-fallback.h:3121
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810fa8af)
Location: include/linux/atomic/atomic-arch-fallback.h:3121
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (ffffffff81243e63)
Location: include/linux/atomic/atomic-arch-fallback.h:3121
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/bpf/bpf_iter.c (ffffffff81346cf7)
Location: include/linux/atomic/atomic-arch-fallback.h:3121
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff81399a04)
Location: include/linux/atomic/atomic-arch-fallback.h:3121
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/rmap.c (ffffffff81437487)
Location: include/linux/atomic/atomic-arch-fallback.h:3121
Inline: True
```
```
In mm/zswap.c (ffffffff8146f60b)
Location: include/linux/atomic/atomic-arch-fallback.h:3121
Inline: True
Inline callers:
  - mm/zswap.c:zswap_lru_add
```
```
In fs/super.c (ffffffff814e38f5)
Location: include/linux/atomic/atomic-arch-fallback.h:3121
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/namespace.c (ffffffff81511082)
Location: include/linux/atomic/atomic-arch-fallback.h:3121
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fuse/dir.c (ffffffff81692854)
Location: include/linux/atomic/atomic-arch-fallback.h:3121
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_entry_unlinked
```
```
In fs/fuse/file.c (ffffffff816993e8)
Location: include/linux/atomic/atomic-arch-fallback.h:3121
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
Location: include/linux/atomic/atomic-arch-fallback.h:3121
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/genhd.c (ffffffff817d13cd)
Location: include/linux/atomic/atomic-arch-fallback.h:3121
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In drivers/xen/grant-table.c (ffffffff81ab5f69)
Location: include/linux/atomic/atomic-arch-fallback.h:3121
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c97598)
Location: include/linux/atomic/atomic-arch-fallback.h:3121
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_file_alloc
```
```
In drivers/firmware/efi/cper.c (ffffffff81e88455)
Location: include/linux/atomic/atomic-arch-fallback.h:3121
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/unix/scm.c (ffffffff8207e8fb)
Location: include/linux/atomic/atomic-arch-fallback.h:3121
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
