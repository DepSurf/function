# Function: <code>atomic64_sub</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81172981)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:__prog_put_common
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff81182bce)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/rmap.c (ffffffff811cb4e2)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff811d5d6a)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/hugetlb.c (ffffffff811dda02)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff811e38a4)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff811e9235)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/page_counter.c (ffffffff811f93ac)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffffffff81201d51)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff81205698)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff812d2e00)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In net/core/sock.c (ffffffff8170289b)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81181afc)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/events/core.c (ffffffff81194a57)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/rmap.c (ffffffff811e848f)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff811f3e31)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/hugetlb.c (ffffffff811fbc74)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff812022ea)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff81208d18)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/page_counter.c (ffffffff8121cf2c)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffffffff812279ce)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff8122aa24)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/ext4/mballoc.c (ffffffff81302528)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In net/core/sock.c (ffffffff81767f9f)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118de49)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/events/core.c (ffffffff811a44b7)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/rmap.c (ffffffff811f9a4a)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81204961)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/hugetlb.c (ffffffff8120c76f)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff8121412a)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff8121ad98)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/page_counter.c (ffffffff8122f52c)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffffffff81239f58)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff8123cf74)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/ext4/mballoc.c (ffffffff813185a8)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In net/core/sock.c (ffffffff81794fa0)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81193aa5)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/events/core.c (ffffffff811abbe7)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/rmap.c (ffffffff81204641)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8121000d)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff812180f3)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff8121f51e)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff812267d8)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/page_counter.c (ffffffff8123ad6c)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812495a3)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/ext4/mballoc.c (ffffffff8130f5ef)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In drivers/usb/core/devio.c (ffffffff816bdd52)
Location: arch/x86/include/asm/atomic64_64.h:57
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
In net/core/sock.c (ffffffff817b3713)
Location: arch/x86/include/asm/atomic64_64.h:57
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

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
In kernel/bpf/syscall.c (ffffffff811a11e2)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/events/core.c (ffffffff811bf55a)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff81209bac)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffffffff8121d4a3)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8122b7ad)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81232b1b)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff8123a756)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff81241818)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff81251d16)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81257966)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/page_counter.c (ffffffff8125a5fc)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812699cc)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/ext4/mballoc.c (ffffffff81334569)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In lib/genalloc.c (ffffffff814a02fb)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
```
```
In drivers/usb/core/devio.c (ffffffff81729722)
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
In net/core/sock.c (ffffffff8182bb04)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff81833d70)
Location: arch/x86/include/asm/atomic64_64.h:58
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
</details>
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
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811b5ab0)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/events/core.c (ffffffff811df760)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8122a9b3)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffffffff8123f375)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8124ca11)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81255b7d)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff8125dcd5)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff81265475)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff8127627b)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8127bb96)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/page_counter.c (ffffffff8127e41e)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff8128d8e2)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/ext4/mballoc.c (ffffffff81362771)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In lib/genalloc.c (ffffffff814d5494)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
```
```
In drivers/usb/core/devio.c (ffffffff817684e2)
Location: include/asm-generic/atomic-instrumented.h:142
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
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff8187a69d)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff818e90b9)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/inet_fragment.c (ffffffff81938fc3)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/ipv6/reassembly.c (ffffffff81991320)
Location: include/asm-generic/atomic-instrumented.h:142
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/xdp/xdp_umem.c (ffffffff819ccb2d)
Location: include/asm-generic/atomic-instrumented.h:142
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
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811c0a71)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811c5572)
Location: include/asm-generic/atomic-instrumented.h:159
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
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/uprobes.c (ffffffff811f5391)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8123dd68)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffffffff81253a83)
Location: include/asm-generic/atomic-instrumented.h:159
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
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81269fcd)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff8127260b)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/ksm.c (ffffffff812750b4)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff8127a1a0)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff8128af53)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8128fed8)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/page_counter.c (ffffffff81292b0e)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffffffff8129ed8d)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/zsmalloc.c (ffffffff812a2852)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/inode.c (ffffffff812cd1a4)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff812ff14f)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In fs/ext4/mballoc.c (ffffffff8137a981)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff814c0ad7)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In lib/genalloc.c (ffffffff814e9eec)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
```
```
In drivers/usb/core/devio.c (ffffffff8178cd32)
Location: include/asm-generic/atomic-instrumented.h:159
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
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff8189b27d)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819162c0)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/inet_fragment.c (ffffffff81968b83)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/unix/af_unix.c (ffffffff8198e6e5)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81991e25)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
```
```
In net/ipv6/reassembly.c (ffffffff819c7a5e)
Location: include/asm-generic/atomic-instrumented.h:159
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/xdp/xdp_umem.c (ffffffff81a05bcd)
Location: include/asm-generic/atomic-instrumented.h:159
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d15b1)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d4e20)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff812073a8)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8124e448)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff81265cb1)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81269704)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff8127be8a)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81285100)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff8128dd3b)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff81295b15)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812a5af6)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812ab0c2)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/page_counter.c (ffffffff812ad4aa)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812bdacd)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff81331349)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff814ef326)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In lib/genalloc.c (ffffffff81516b26)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff817cc139)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff818e5afd)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819784dc)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf030)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81a7551d)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811ddb31)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811e1530)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff81214718)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8125c9b8)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff812745cf)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81278627)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff8128b96a)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81294ca0)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff812a58f5)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812b6fb6)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812bca5b)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812beffa)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812cf9bd)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff81345016)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff815087b6)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (ffffffff8150fdb8)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In lib/genalloc.c (ffffffff81537566)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff817fcda6)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff81917c4d)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819aee4c)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a05bd0)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81aac35d)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811fa6d4)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff812004fb)
Location: include/asm-generic/atomic-instrumented.h:959
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
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8128c2a8)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff812a58a8)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812abf70)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff812be85a)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff812c8295)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff812da5b5)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812ec198)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812f11f3)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812f42dc)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff813063a4)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff81385a01)
Location: include/asm-generic/atomic-instrumented.h:959
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
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff81569ad0)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In lib/genalloc.c (ffffffff8159be9f)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff818cbf51)
Location: include/asm-generic/atomic-instrumented.h:959
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
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff819ed62d)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81a98e8f)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_reinit
```
```
In net/ipv4/inet_fragment.c (ffffffff81af52e0)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81ba84df)
Location: include/asm-generic/atomic-instrumented.h:959
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
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811f97b4)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/events/core.c (ffffffff8124ad4a)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8129721c)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff812b0d02)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812b7490)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff812ca43a)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff812d3e65)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff812e6e75)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812f722a)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812fc8fa)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812ffbcc)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff81312104)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff81396bfb)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_unaccount_mem
  - fs/io_uring.c:io_unaccount_mem
```
```
In fs/ext4/mballoc.c (ffffffff8141da5c)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff81584380)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In lib/genalloc.c (ffffffff815b78c7)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff818d71fc)
Location: include/asm-generic/atomic-instrumented.h:959
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
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff819ed2ed)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa2dff)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_reinit
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02040)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81bb8245)
Location: include/asm-generic/atomic-instrumented.h:959
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
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811fa657)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/events/core.c (ffffffff8124f12a)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8129d057)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff812b6354)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812bcd60)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff812d0f67)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff812dad72)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff812ee665)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812fd6c0)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81303665)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff8130688c)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff81317ea4)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff81390d13)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_unmap
  - fs/io_uring.c:io_buffer_unmap
```
```
In fs/ext4/mballoc.c (ffffffff814241cd)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff8158b183)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In lib/genalloc.c (ffffffff815c2734)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff818ba2b9)
Location: include/asm-generic/atomic-instrumented.h:959
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
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff819d557a)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e1e4)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81aed950)
Location: include/asm-generic/atomic-instrumented.h:959
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81ba7407)
Location: include/asm-generic/atomic-instrumented.h:959
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
In kernel/events/core.c (ffffffff81289e81)
Location: include/linux/atomic/atomic-instrumented.h:694
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In fs/io_uring.c (ffffffff813de244)
Location: include/linux/atomic/atomic-instrumented.h:694
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_unmap
```
```
In fs/ext4/mballoc.c (ffffffff81477e2b)
Location: include/linux/atomic/atomic-instrumented.h:694
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff815f0183)
Location: include/linux/atomic/atomic-instrumented.h:694
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In drivers/usb/core/devio.c (ffffffff81950161)
Location: include/linux/atomic/atomic-instrumented.h:694
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
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
In kernel/events/core.c (ffffffff812de7db)
Location: include/linux/atomic/atomic-instrumented.h:740
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In fs/ext4/mballoc.c (ffffffff814fa34e)
Location: include/linux/atomic/atomic-instrumented.h:740
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff816a1261)
Location: include/linux/atomic/atomic-instrumented.h:740
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In io_uring/io_uring.c (ffffffff816c7c90)
Location: include/linux/atomic/atomic-instrumented.h:740
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_buffer_unmap
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
In kernel/events/core.c (ffffffff81346995)
Location: include/linux/atomic/atomic-instrumented.h:740
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In fs/ext4/mballoc.c (ffffffff81594b7e)
Location: include/linux/atomic/atomic-instrumented.h:740
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff81760074)
Location: include/linux/atomic/atomic-instrumented.h:740
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In io_uring/rsrc.c (ffffffff817a00d0)
Location: include/linux/atomic/atomic-instrumented.h:740
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_unmap
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
In kernel/events/core.c (ffffffff81377a9b)
Location: include/linux/atomic/atomic-instrumented.h:1832
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In fs/ext4/mballoc.c (ffffffff815cbb5b)
Location: include/linux/atomic/atomic-instrumented.h:1832
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff8179f084)
Location: include/linux/atomic/atomic-instrumented.h:1832
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In io_uring/rsrc.c (ffffffff817e11d0)
Location: include/linux/atomic/atomic-instrumented.h:1832
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_unmap
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
In kernel/events/core.c (ffffffff813a0d7b)
Location: include/linux/atomic/atomic-instrumented.h:1832
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In fs/ext4/mballoc.c (ffffffff81601710)
Location: include/linux/atomic/atomic-instrumented.h:1832
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_context
```
```
In block/blk-cgroup.c (ffffffff817e2b54)
Location: include/linux/atomic/atomic-instrumented.h:1832
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In io_uring/rsrc.c (ffffffff81825af0)
Location: include/linux/atomic/atomic-instrumented.h:1832
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_unmap
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
In kernel/trace/ring_buffer.c (ffff80001021c88c)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffff800010264b88)
Location: include/asm-generic/atomic-instrumented.h:958
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
In kernel/events/core.c (ffff80001029f178)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/uprobes.c (ffff8000102a57bc)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffff8000102f558c)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffff800010309e78)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffff800010326d48)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffff8000103339ec)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffff80001033cb80)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffff80001033ef3c)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffff800010346780)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffff800010357d10)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffff80001035dcac)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffff800010360c14)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffff80001036fe38)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffff80001037526c)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/inode.c (ffff8000103acd34)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffff8000103f033c)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In fs/io_uring.c (ffff80001040317c)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/genhd.c (ffff8000105fabd4)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_dec_in_flight
```
```
In block/blk-cgroup.c (ffff80001060d268)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (ffff800010615d08)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In lib/genalloc.c (ffff8000106445ec)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffff800010a2e000)
Location: include/asm-generic/atomic-instrumented.h:958
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
In drivers/perf/arm_pmu.c (ffff800010b95020)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_update
```
```
In net/core/sock.c (ffff800010bacc90)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffff800010bb3834)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffff800010c5fa00)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffff800010cbe9c0)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/unix/af_unix.c (ffff800010cf0d84)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffff800010cf475c)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
```
```
In net/xdp/xdp_umem.c (ffff800010d80b90)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
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
In kernel/events/core.c (c04cdf90)
Location: arch/arm/include/asm/atomic.h:377
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In fs/ext4/mballoc.c (c0655eb8)
Location: arch/arm/include/asm/atomic.h:377
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (c07b6214)
Location: arch/arm/include/asm/atomic.h:377
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (c07bea34)
Location: arch/arm/include/asm/atomic.h:377
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/usb/core/devio.c (c0b03dac)
Location: arch/arm/include/asm/atomic.h:377
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
In drivers/perf/arm_pmu.c (c0c7e6a0)
Location: arch/arm/include/asm/atomic.h:377
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_update
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
In arch/powerpc/mm/hugetlbpage.c (c0000000000a5e48)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
```
```
In kernel/bpf/core.c (c0000000003038c0)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (c0000000003096fc)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (c00000000034f828)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (c0000000003bc7a0)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (c0000000003d9c18)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (c0000000003dfe88)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (c0000000003fd8a4)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (c00000000040c840)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (c0000000004247d0)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (c00000000043c14c)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (c000000000449358)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (c00000000044bdac)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (c0000000004673f8)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (c00000000050fd28)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/mballoc.c (c0000000005bd9f8)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (c0000000007a7bc8)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (c0000000007b2540)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In lib/genalloc.c (c0000000007ef9ec)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (c000000000aee57c)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
```
```
In net/core/sock.c (c000000000c7fa44)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (c000000000c87d80)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (c000000000d61fe8)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (c000000000dd9254)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (c000000000ec0860)
Location: arch/powerpc/include/asm/atomic.h:371
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_unaccount_pages
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
In kernel/trace/ring_buffer.c (ffffffe00017a316)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
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
In kernel/bpf/core.c (ffffffe00019ccb2)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffe0001a08cc)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (ffffffe0001ce752)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffe000206b2a)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffffffe000213dfe)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffe000217726)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
```
```
In mm/swapfile.c (ffffffe000226da0)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffe00022fb4c)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffe000234b12)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffe00023d3a2)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
```
```
In mm/page_counter.c (ffffffe000240416)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffe00024dfa4)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/inode.c (ffffffe000270d2c)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffe0002a3d60)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In fs/io_uring.c (ffffffe0002b0adc)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/mballoc.c (ffffffe000319190)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/genhd.c (ffffffe000436ee6)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_dec_in_flight
```
```
In block/blk-cgroup.c (ffffffe000444428)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (ffffffe00044af1e)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In lib/genalloc.c (ffffffe000470a7e)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffe00064f382)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
```
```
In net/core/sock.c (ffffffe00073d5ca)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffe000745b82)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c7804)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffe000814b64)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/unix/af_unix.c (ffffffe00083d102)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffe0008405b4)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad9fc)
Location: arch/riscv/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d6151)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d9b50)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff8120cd68)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff81255008)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8126cc1f)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81270c77)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81283f4a)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8128d280)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff8129ded5)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812af596)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b503b)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812b75da)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812c7f9d)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff8133d5f6)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff81500d96)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (ffffffff81508398)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In lib/genalloc.c (ffffffff8152fb46)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff817b5186)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff818b7c4d)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff8194ecbc)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5970)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81a4b6ed)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811c8f11)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811cc910)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff811ffb38)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff81248c55)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffffffff8125ec6c)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81262be7)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81275dda)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8127f06f)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff8128fa55)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812a0b87)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812a6069)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812a87aa)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812b8fdd)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff8132e2b6)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff814f12a6)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (ffffffff814f8848)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In lib/genalloc.c (ffffffff8151fe26)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff817a6bb6)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff81871b9d)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819087ac)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f430)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81a082dd)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d3f21)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d7920)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff8120ab08)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff81252da8)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8126a9bf)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8126ea17)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81281d5a)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8128b090)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff8129bce5)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812ad3a6)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b2e4b)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812b53ea)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812c5dad)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff8133b0c6)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff814fce26)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (ffffffff81504428)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In lib/genalloc.c (ffffffff8152b886)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff817f1c26)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff81908c4d)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819b948c)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10210)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81ab759d)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811e2241)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811e5cc0)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff812198f1)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff81262708)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8127a339)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8127e42d)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81291a66)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8129aeb0)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff812abbf5)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812bd727)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812c3286)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812c592a)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812d75fd)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff8134e276)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff81515ed6)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (ffffffff8151d9d8)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In lib/genalloc.c (ffffffff8154561e)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/usb/core/devio.c (ffffffff8180be66)
Location: include/asm-generic/atomic-instrumented.h:958
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
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff81929cfd)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819c2d7c)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1aa60)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81ac39bd)
Location: include/asm-generic/atomic-instrumented.h:958
Inline: True
```
</details>
</li>
</ul>

## Differences
