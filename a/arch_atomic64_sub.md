# Function: <code>arch_atomic64_sub</code>

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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811b5ab0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/events/core.c (ffffffff811df760)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8122a9b3)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffffffff8123f375)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8124ca11)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81255b7d)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff8125dcd5)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff81265475)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff8127627b)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8127bb96)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/page_counter.c (ffffffff8127e41e)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff8128d8e2)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/ext4/mballoc.c (ffffffff81362771)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In lib/genalloc.c (ffffffff814d5494)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
```
```
In drivers/usb/core/devio.c (ffffffff817684e2)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In net/core/sock.c (ffffffff81875670)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff8187a69d)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff818e90b9)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/inet_fragment.c (ffffffff81938fc3)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/ipv6/reassembly.c (ffffffff81991320)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/xdp/xdp_umem.c (ffffffff819ccb2d)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811c0a71)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811c5572)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff811efba0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/uprobes.c (ffffffff811f5391)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8123dd68)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffffffff81253a83)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81260f3b)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81269fcd)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff8127260b)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/ksm.c (ffffffff812750b4)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff8127a1a0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff8128af53)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8128fed8)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/page_counter.c (ffffffff81292b0e)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffffffff8129ed8d)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/zsmalloc.c (ffffffff812a2852)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/inode.c (ffffffff812cd1a4)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff812ff14f)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In fs/ext4/mballoc.c (ffffffff8137a981)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff814c0ad7)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In lib/genalloc.c (ffffffff814e9eec)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
```
```
In drivers/usb/core/devio.c (ffffffff8178cd32)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In net/core/sock.c (ffffffff81895f58)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff8189b27d)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819162c0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/inet_fragment.c (ffffffff81968b83)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/unix/af_unix.c (ffffffff8198e6e5)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81991e25)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
```
```
In net/ipv6/reassembly.c (ffffffff819c7a5e)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/xdp/xdp_umem.c (ffffffff81a05bcd)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d15b1)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d4e20)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff812073a8)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8124e448)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff81265cb1)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81269704)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff8127be8a)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81285100)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff8128dd3b)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff81295b15)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812a5af6)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812ab0c2)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/page_counter.c (ffffffff812ad4aa)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812bdacd)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff81331349)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/mballoc.c (ffffffff813a4aaa)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff814ef326)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In lib/genalloc.c (ffffffff81516b26)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff817cc139)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In net/core/sock.c (ffffffff818e0468)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff818e5afd)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819784dc)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf030)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81a7551d)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811ddb31)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811e1530)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff81214718)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8125c9b8)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff812745cf)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81278627)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff8128b96a)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81294ca0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff812a58f5)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812b6fb6)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812bca5b)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812beffa)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812cf9bd)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff81345016)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/mballoc.c (ffffffff813bd916)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff815087b6)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (ffffffff8150fdb8)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In lib/genalloc.c (ffffffff81537566)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff817fcda6)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In net/core/sock.c (ffffffff81912628)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff81917c4d)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819aee4c)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a05bd0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81aac35d)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811fa6d4)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff812004fb)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_memlock
```
```
In kernel/events/core.c (ffffffff812407b2)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8128c2a8)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff812a58a8)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812abf70)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff812be85a)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff812c8295)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff812da5b5)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812ec198)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812f11f3)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812f42dc)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff813063a4)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff81385a01)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/mballoc.c (ffffffff814098ce)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff81569ad0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In lib/genalloc.c (ffffffff8159be9f)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff818cbf51)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In net/core/sock.c (ffffffff819e5adc)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff819ed62d)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81a98e8f)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_reinit
```
```
In net/ipv4/inet_fragment.c (ffffffff81af52e0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81ba84df)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811f97b4)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/events/core.c (ffffffff8124ad4a)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8129721c)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff812b0d02)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812b7490)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff812ca43a)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff812d3e65)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff812e6e75)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812f722a)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812fc8fa)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812ffbcc)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff81312104)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff81396bfb)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_unaccount_mem
  - fs/io_uring.c:io_unaccount_mem
```
```
In fs/ext4/mballoc.c (ffffffff8141da5c)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff81584380)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In lib/genalloc.c (ffffffff815b78c7)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff818d71fc)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In net/core/sock.c (ffffffff819e55ac)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff819ed2ed)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa2dff)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_reinit
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02040)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81bb8245)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811fa657)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/events/core.c (ffffffff8124f12a)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8129d057)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff812b6354)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812bcd60)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff812d0f67)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff812dad72)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff812ee665)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812fd6c0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81303665)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff8130688c)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff81317ea4)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff81390d13)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_unmap
  - fs/io_uring.c:io_buffer_unmap
```
```
In fs/ext4/mballoc.c (ffffffff814241cd)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff8158b183)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In lib/genalloc.c (ffffffff815c2734)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff818ba2b9)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In net/core/sock.c (ffffffff819cb6bc)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff819d557a)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e1e4)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81aed950)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81ba7407)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8122bd67)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/events/core.c (ffffffff81289e5a)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff812de4a2)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff812f87fc)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812ff4da)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81316658)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81321d90)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff813368a5)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff813472f5)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8134d3cf)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff813506dc)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff81363c01)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff813de233)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_unmap
  - fs/io_uring.c:io_buffer_unmap
```
```
In fs/ext4/mballoc.c (ffffffff81477e2b)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff815f0183)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In lib/genalloc.c (ffffffff8162a685)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff81950161)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In net/core/sock.c (ffffffff81a7ad4c)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff81a85236)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81b493d4)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81badd10)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81c7516b)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8126d8e1)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/events/core.c (ffffffff812de7b7)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8133e570)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8135e9d6)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813665d2)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81381806)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8138eeea)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff813a81f5)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff813bd5a6)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813c3b5b)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In mm/page_counter.c (ffffffff813c89cc)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff813e0803)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/ext4/mballoc.c (ffffffff814fa34e)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff816a1261)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In io_uring/io_uring.c (ffffffff816c7c7f)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_buffer_unmap
  - io_uring/io_uring.c:io_buffer_unmap
```
```
In lib/genalloc.c (ffffffff816fbaa5)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In net/core/sock.c (ffffffff81beec5f)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/skbuff.c (ffffffff81bfb25a)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6a77)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81d40daf)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81e19197)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812c2d01)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/events/core.c (ffffffff81346971)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff813b55dc)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff813d989b)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813e21e2)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff813fff90)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8140d9d3)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff81429666)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff8143fd3e)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8144733a)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In mm/page_counter.c (ffffffff8144d0c2)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffffffff81462403)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:__free_raw_hwp_pages
```
```
In mm/zsmalloc.c (ffffffff81467cdb)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/ext4/mballoc.c (ffffffff81594b7e)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff81760074)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In io_uring/rsrc.c (ffffffff817a00bf)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_unmap
  - io_uring/rsrc.c:io_buffer_unmap
```
```
In io_uring/notif.c (ffffffff817a508e)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - io_uring/notif.c:io_notif_complete_tw_ext
```
```
In lib/genalloc.c (ffffffff817ee735)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/base/memory.c (ffffffff81b170d2)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_sub
```
```
In net/core/skbuff.c (ffffffff81da9f6a)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81e9706d)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81f09b2f)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81ff057d)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811d6e84)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812e9bf1)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/events/core.c (ffffffff81377a77)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff813eac97)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8140e121)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81417026)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81432e3f)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81440d87)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff8145e9ed)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff81475566)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8147ca11)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In mm/page_counter.c (ffffffff81482982)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffffffff81496ecd)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:__folio_free_raw_hwp
```
```
In mm/zsmalloc.c (ffffffff8149cd44)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/ext4/mballoc.c (ffffffff815cbb5b)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff8179f084)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In io_uring/rsrc.c (ffffffff817e11bf)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_unmap
  - io_uring/rsrc.c:io_buffer_unmap
```
```
In io_uring/notif.c (ffffffff817e605e)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - io_uring/notif.c:io_notif_complete_tw_ext
```
```
In lib/genalloc.c (ffffffff8182eb2c)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/base/memory.c (ffffffff81b65e42)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_sub
```
```
In net/core/skbuff.c (ffffffff81e18d0a)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef585e)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6963f)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff8206c72b)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811ed885)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_release_slots
```
```
In kernel/bpf/core.c (ffffffff81308141)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/events/core.c (ffffffff813a0d57)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff81417497)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8143a87a)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8143fc29)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/slub.c (ffffffff8145d0c2)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/swapfile.c (ffffffff8146c25f)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8147aeb7)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff814a4f5e)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814acd26)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff814b1d02)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffffffff814c6ccf)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:__folio_free_raw_hwp
```
```
In mm/zsmalloc.c (ffffffff814cc514)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/ext4/mballoc.c (ffffffff81601710)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_context
```
```
In block/blk-cgroup.c (ffffffff817e2b54)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In io_uring/rsrc.c (ffffffff81825adf)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_unmap
  - io_uring/rsrc.c:io_buffer_unmap
```
```
In io_uring/notif.c (ffffffff8182a27e)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - io_uring/notif.c:io_notif_complete_tw_ext
```
```
In lib/genalloc.c (ffffffff818806ec)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/base/memory.c (ffffffff81bb9cc2)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_sub
```
```
In net/core/skbuff.c (ffffffff81ed619a)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb980e)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff8202fcbf)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff82140529)
Location: arch/x86/include/asm/atomic64_64.h:30
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void arch_atomic64_sub(long int i, atomic64_t *v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021c88c)
Location: arch/arm64/include/asm/atomic.h:69
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
In kernel/bpf/core.c (ffff80001025e9e8)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffff800010264b88)
Location: arch/arm64/include/asm/atomic.h:69
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
In kernel/events/core.c (ffff80001029e76c)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
Direct callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/uprobes.c (ffff8000102a57bc)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffff8000102f558c)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffff800010309e78)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffff80001030ef0c)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffff800010326d48)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffff8000103339ec)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffff80001033cb80)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffff80001033ef3c)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffff800010346780)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffff800010357d10)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffff80001035dcac)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffff800010360c14)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffff80001036fe38)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffff80001037526c)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/inode.c (ffff8000103acd34)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffff8000103f033c)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In fs/io_uring.c (ffff80001040317c)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/mballoc.c (ffff8000104946b0)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/genhd.c (ffff8000105fabd4)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_dec_in_flight
```
```
In block/blk-cgroup.c (ffff80001060d268)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (ffff800010615d08)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In lib/genalloc.c (ffff8000106445ec)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffff800010a2e000)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/perf/arm_pmu.c (ffff800010b95020)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_update
```
```
In net/core/sock.c (ffff800010bacc90)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffff800010bb3834)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffff800010c5fa00)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffff800010cbe9c0)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/unix/af_unix.c (ffff800010cf0d84)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffff800010cf475c)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
```
```
In net/xdp/xdp_umem.c (ffff800010d80b90)
Location: arch/arm64/include/asm/atomic.h:69
Inline: True
```
**Symbols:**

```
ffff8000102950c0-ffff8000102950dc: arch_atomic64_sub (STB_LOCAL)
ffff80001036e2f0-ffff80001036e32c: arch_atomic64_sub.constprop.0 (STB_LOCAL)
ffff800010a2c2b8-ffff800010a2c2ec: arch_atomic64_sub.constprop.0 (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d6151)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d9b50)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff8120cd68)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff81255008)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8126cc1f)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81270c77)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81283f4a)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8128d280)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff8129ded5)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812af596)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b503b)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812b75da)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812c7f9d)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff8133d5f6)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/mballoc.c (ffffffff813b5ef6)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff81500d96)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (ffffffff81508398)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In lib/genalloc.c (ffffffff8152fb46)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff817b5186)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In net/core/sock.c (ffffffff818b2628)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff818b7c4d)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff8194ecbc)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5970)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81a4b6ed)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811c8f11)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811cc910)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff811ffb38)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff81248c55)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffffffff8125ec6c)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81262be7)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81275dda)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8127f06f)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff8128fa55)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812a0b87)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812a6069)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812a87aa)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812b8fdd)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff8132e2b6)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/mballoc.c (ffffffff813a6986)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff814f12a6)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (ffffffff814f8848)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In lib/genalloc.c (ffffffff8151fe26)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff817a6bb6)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In net/core/sock.c (ffffffff8186c578)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff81871b9d)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819087ac)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f430)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81a082dd)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d3f21)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d7920)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff8120ab08)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff81252da8)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8126a9bf)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8126ea17)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81281d5a)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8128b090)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff8129bce5)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812ad3a6)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b2e4b)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812b53ea)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812c5dad)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff8133b0c6)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/mballoc.c (ffffffff813b3756)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff814fce26)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (ffffffff81504428)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In lib/genalloc.c (ffffffff8152b886)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff817f1c26)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In net/core/sock.c (ffffffff81903628)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff81908c4d)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819b948c)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10210)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81ab759d)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811e2241)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811e5cc0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff812198f1)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff81262708)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8127a339)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8127e42d)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81291a66)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8129aeb0)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff812abbf5)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812bd727)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812c3286)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812c592a)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812d75fd)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff8134e276)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/mballoc.c (ffffffff813c8418)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff81515ed6)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (ffffffff8151d9d8)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In lib/genalloc.c (ffffffff8154561e)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff8180be66)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In net/core/sock.c (ffffffff81924608)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff81929cfd)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819c2d7c)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1aa60)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81ac39bd)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
