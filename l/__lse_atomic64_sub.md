# Function: <code>__lse_atomic64_sub</code>

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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/trace/ring_buffer.c (ffff80001021c894)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/bpf/core.c (ffff80001025e9f0)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffff800010264b90)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffff80001029e800)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/uprobes.c (ffff8000102a57c4)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffff8000102f5594)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffff800010309e80)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffff80001030ef14)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffff800010326d50)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffff8000103339f4)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffff80001033cb88)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffff80001033ef44)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffff800010346788)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffff800010357d18)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffff80001035dcb4)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffff800010360c1c)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffff80001036fe40)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffff800010375274)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/inode.c (ffff8000103acd3c)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffff8000103f0344)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In fs/io_uring.c (ffff800010403184)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/mballoc.c (ffff8000104946b8)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/genhd.c (ffff8000105fabdc)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_dec_in_flight
```
```
In block/blk-cgroup.c (ffff80001060d270)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (ffff800010615d10)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In lib/genalloc.c (ffff8000106445f4)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffff800010a2e008)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
```
```
In drivers/perf/arm_pmu.c (ffff800010b95028)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_update
```
```
In net/core/sock.c (ffff800010bacc98)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffff800010bb3840)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffff800010c5fa08)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffff800010cbe9c8)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/unix/af_unix.c (ffff800010cf0d8c)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffff800010cf4764)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
```
```
In net/xdp/xdp_umem.c (ffff800010d80b9c)
Location: arch/arm64/include/asm/atomic_lse.h:264
Inline: True
```
</details>
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
