# Function: <code>raw_atomic_inc_not_zero</code>

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
In arch/x86/events/core.c (ffffffff81008399)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff8213e241)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810931ce)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810969ca)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
```
```
In kernel/cred.c (ffffffff81133751)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/sched/core.c (ffffffff811442c5)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/module/main.c (ffffffff811db4d7)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - kernel/module/main.c:try_module_get
```
```
In kernel/events/core.c (ffffffff8136775a)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:get_pmu_ctx
```
```
In kernel/events/uprobes.c (ffffffff8137fd57)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/vmscan.c (ffffffff813a9271)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_mm
```
```
In mm/rmap.c (ffffffff8140f4ae)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/swapfile.c (ffffffff814329b3)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff81473aed)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In fs/super.c (ffffffff814b34e4)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff815262ef)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/mbcache.c (ffffffff8154c98f)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
```
```
In fs/proc/task_mmu.c (ffffffff81564ffc)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff81569591)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff8156ae0a)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff815831ef)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/fuse/file.c (ffffffff8165b37e)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff81786e4d)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In io_uring/timeout.c (ffffffff817d9dd1)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81aba3f5)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b2a0a4)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In drivers/base/power/runtime.c (ffffffff81b4df31)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82005d43)
Location: include/linux/atomic/atomic-arch-fallback.h:2452
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In arch/x86/events/core.c (ffffffff8100dab9)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff82220231)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a63e)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109df3a)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
```
```
In kernel/sched/core.c (ffffffff8114f7e5)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/module/main.c (ffffffff811f1187)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - kernel/module/main.c:try_module_get
```
```
In kernel/events/core.c (ffffffff81394b09)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:get_pmu_ctx
```
```
In kernel/events/uprobes.c (ffffffff813a8fa2)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/vmscan.c (ffffffff813dd0bc)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
```
```
In mm/rmap.c (ffffffff8143be78)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/swapfile.c (ffffffff8146bdd3)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/huge_memory.c (ffffffff814a2ffd)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In fs/super.c (ffffffff814e478c)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - fs/super.c:get_bdev_super
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff8155953a)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_poison
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/mbcache.c (ffffffff815827bf)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
```
```
In fs/proc/task_mmu.c (ffffffff8159c3fc)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff815a1bb1)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff815a37ea)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff815bbe3f)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/fuse/file.c (ffffffff8169504e)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff817c952d)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In io_uring/timeout.c (ffffffff8181dfe1)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0d135)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b81274)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In drivers/base/power/runtime.c (ffffffff81ba64b1)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d4b95)
Location: include/linux/atomic/atomic-arch-fallback.h:2461
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
