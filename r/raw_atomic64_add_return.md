# Function: <code>raw_atomic64_add_return</code>

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
In arch/x86/kernel/ioport.c (ffffffff81051e0f)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/mm/tlb.c (ffffffff810cc9e5)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff836c7982)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810f14cd)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/ucount.c (ffffffff81137c82)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:inc_rlimit_ucounts
```
```
In kernel/locking/rwsem.c (ffffffff82154d1f)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/dma/swiotlb.c (ffffffff811d72e1)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
```
```
In kernel/futex/core.c (ffffffff8120817e)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff8122bded)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/misc.c (ffffffff81235869)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/trace/trace_clock.c (ffffffff81268190)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff812e992c)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/bpf/bpf_iter.c (ffffffff81322dc7)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff81370704)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff813999b1)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff813ac7b4)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/rmap.c (ffffffff8140ad57)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - mm/rmap.c:set_tlb_ubc_flush_pending
```
```
In mm/vmalloc.c (ffffffff81410e3e)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff8148296d)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff814b2295)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff814be670)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffffffff814e03c2)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fuse/dir.c (ffffffff81658b14)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_entry_unlinked
```
```
In fs/fuse/file.c (ffffffff8165f5a8)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
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
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/genhd.c (ffffffff8178eade)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In drivers/xen/grant-table.c (ffffffff81a6371a)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/tty/tty_ldsem.c (ffffffff81aa1185)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/iommu/amd/iommu.c (ffffffff81afec8c)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_flush_irt_and_complete
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbd180)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In drivers/firmware/efi/cper.c (ffffffff81dcf725)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff81e2491b)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81e75309)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
Inline: True
```
```
In net/unix/scm.c (ffffffff81fb11eb)
Location: include/linux/atomic/atomic-arch-fallback.h:2668
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
In arch/x86/kernel/ioport.c (ffffffff8105902f)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/mm/tlb.c (ffffffff810d507e)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff838f8582)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810fa8af)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/ucount.c (ffffffff81142e92)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:inc_rlimit_ucounts
```
```
In kernel/locking/rwsem.c (ffffffff82237b5f)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/dma/swiotlb.c (ffffffff811ec2a1)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_search_pool_area
```
```
In kernel/futex/core.c (ffffffff8121f032)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff81243e1d)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/misc.c (ffffffff8124f4b8)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/trace/trace_clock.c (ffffffff81282400)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff81307b7c)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/bpf/bpf_iter.c (ffffffff81346cf7)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff81399a04)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff813c37b1)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/shrinker.c (ffffffff813e4062)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - mm/shrinker.c:do_shrink_slab
  - mm/shrinker.c:do_shrink_slab
```
```
In mm/rmap.c (ffffffff81437487)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
```
```
In mm/vmalloc.c (ffffffff8143d62e)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/zswap.c (ffffffff8146f60b)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - mm/zswap.c:zswap_lru_add
```
```
In mm/page_counter.c (ffffffff814b1ced)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff814e38f5)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff814f0b0c)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffffffff81513683)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fuse/dir.c (ffffffff81692854)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_entry_unlinked
```
```
In fs/fuse/file.c (ffffffff816993e8)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
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
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/genhd.c (ffffffff817d13cd)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In drivers/xen/grant-table.c (ffffffff81ab5f69)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/tty/tty_ldsem.c (ffffffff81af3be5)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b523dc)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_flush_irt_and_complete
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c11870)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c97598)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_file_alloc
```
```
In drivers/firmware/efi/cper.c (ffffffff81e88455)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff81ee256b)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81f34ba9)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
Inline: True
```
```
In net/unix/scm.c (ffffffff8207e8fb)
Location: include/linux/atomic/atomic-arch-fallback.h:2673
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
