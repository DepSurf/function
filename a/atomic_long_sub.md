# Function: <code>atomic_long_sub</code>

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
Location: include/asm-generic/atomic-long.h:125
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
Location: include/asm-generic/atomic-long.h:125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/rmap.c (ffffffff811cb4e2)
Location: include/asm-generic/atomic-long.h:125
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff811d5d6a)
Location: include/asm-generic/atomic-long.h:125
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/hugetlb.c (ffffffff811dda02)
Location: include/asm-generic/atomic-long.h:125
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff811e38a4)
Location: include/asm-generic/atomic-long.h:125
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff811e9235)
Location: include/asm-generic/atomic-long.h:125
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/page_counter.c (ffffffff811f93ac)
Location: include/asm-generic/atomic-long.h:125
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffffffff81201d51)
Location: include/asm-generic/atomic-long.h:125
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
Location: include/asm-generic/atomic-long.h:125
Inline: True
```
```
In net/core/sock.c (ffffffff8170289b)
Location: include/asm-generic/atomic-long.h:125
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
Location: include/asm-generic/atomic-long.h:181
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
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/rmap.c (ffffffff811e848f)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff811f3e31)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/hugetlb.c (ffffffff811fbc74)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff812022ea)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff81208d18)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/page_counter.c (ffffffff8121cf2c)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffffffff812279ce)
Location: include/asm-generic/atomic-long.h:181
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
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In net/core/sock.c (ffffffff81767f9f)
Location: include/asm-generic/atomic-long.h:181
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
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/events/core.c (ffffffff811a44b7)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/rmap.c (ffffffff811f9a4a)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81204961)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/hugetlb.c (ffffffff8120c76f)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff8121412a)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff8121ad98)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/page_counter.c (ffffffff8122f52c)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffffffff81239f58)
Location: include/asm-generic/atomic-long.h:181
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
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In net/core/sock.c (ffffffff81794fa0)
Location: include/asm-generic/atomic-long.h:181
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
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/events/core.c (ffffffff811abbe7)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/rmap.c (ffffffff81204641)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8121000d)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff812180f3)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff8121f51e)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff812267d8)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/page_counter.c (ffffffff8123ad6c)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812495a3)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In net/core/sock.c (ffffffff817b3713)
Location: include/asm-generic/atomic-long.h:181
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
Location: include/asm-generic/atomic-long.h:182
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811a11e2)
Location: include/asm-generic/atomic-long.h:182
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/events/core.c (ffffffff811bf55a)
Location: include/asm-generic/atomic-long.h:182
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff81209bac)
Location: include/asm-generic/atomic-long.h:182
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffffffff8121d4a3)
Location: include/asm-generic/atomic-long.h:182
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8122b7ad)
Location: include/asm-generic/atomic-long.h:182
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81232b1b)
Location: include/asm-generic/atomic-long.h:182
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff8123a756)
Location: include/asm-generic/atomic-long.h:182
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff81241818)
Location: include/asm-generic/atomic-long.h:182
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff81251d16)
Location: include/asm-generic/atomic-long.h:182
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81257966)
Location: include/asm-generic/atomic-long.h:182
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/page_counter.c (ffffffff8125a5fc)
Location: include/asm-generic/atomic-long.h:182
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812699cc)
Location: include/asm-generic/atomic-long.h:182
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In lib/genalloc.c (ffffffff814a02fb)
Location: include/asm-generic/atomic-long.h:182
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
```
```
In net/core/sock.c (ffffffff8182bb04)
Location: include/asm-generic/atomic-long.h:182
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff81833d70)
Location: include/asm-generic/atomic-long.h:182
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
Location: include/asm-generic/atomic-long.h:199
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811b5ab0)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/events/core.c (ffffffff811df760)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8122a9b3)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffffffff8123f375)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8124ca11)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81255b7d)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff8125dcd5)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff81265475)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff8127627b)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8127bb96)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/page_counter.c (ffffffff8127e41e)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff8128d8e2)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In lib/genalloc.c (ffffffff814d5494)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
```
```
In net/core/sock.c (ffffffff81875670)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff8187a69d)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff818e90b9)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/inet_fragment.c (ffffffff81938fc3)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/ipv6/reassembly.c (ffffffff81991320)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/xdp/xdp_umem.c (ffffffff819ccb2d)
Location: include/asm-generic/atomic-long.h:199
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
Location: include/asm-generic/atomic-long.h:199
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811c0a71)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811c5572)
Location: include/asm-generic/atomic-long.h:199
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
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8123dd68)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffffffff81253a83)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81260f3b)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81269fcd)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff8127260b)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff8127a1a6)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff8128af53)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8128fed8)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/page_counter.c (ffffffff81292b0e)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812a2852)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In lib/genalloc.c (ffffffff814e9eec)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
```
```
In net/core/sock.c (ffffffff81895f58)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff8189b27d)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819162c0)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/inet_fragment.c (ffffffff81968b83)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/ipv6/reassembly.c (ffffffff819c7a5e)
Location: include/asm-generic/atomic-long.h:199
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/xdp/xdp_umem.c (ffffffff81a05bcd)
Location: include/asm-generic/atomic-long.h:199
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
Location: include/asm-generic/atomic-long.h:104
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d15b1)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d4e20)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff812073a8)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8124e448)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff81265cb1)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81269704)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff8127be8a)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81285100)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse.c (ffffffff8128dd3b)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff81295b15)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812a5af6)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812ab0c2)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/page_counter.c (ffffffff812ad4aa)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812bdacd)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff81331349)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In lib/genalloc.c (ffffffff81516b26)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In net/core/sock.c (ffffffff818e0468)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff818e5afd)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819784dc)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf030)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81a7551d)
Location: include/asm-generic/atomic-long.h:104
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
Location: include/asm-generic/atomic-long.h:104
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811ddb31)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811e1530)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff81214718)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8125c9b8)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff812745cf)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81278627)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff8128b96a)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81294ca0)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff812a58f5)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812b6fb6)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812bca5b)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812beffa)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812cf9bd)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff81345016)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In lib/genalloc.c (ffffffff81537566)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In net/core/sock.c (ffffffff81912628)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff81917c4d)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819aee4c)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a05bd0)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81aac35d)
Location: include/asm-generic/atomic-long.h:104
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
Location: include/asm-generic/atomic-long.h:105
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811fa6d4)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff812004fb)
Location: include/asm-generic/atomic-long.h:105
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
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8128c2a8)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff812a58a8)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812abf70)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff812be85a)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff812c8295)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff812da5b5)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812ec198)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812f11f3)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812f42dc)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff813063a4)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff81385a01)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In lib/genalloc.c (ffffffff8159be9f)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In net/core/sock.c (ffffffff819e5adc)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff819ed62d)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81a98e8f)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_reinit
```
```
In net/ipv4/inet_fragment.c (ffffffff81af52e0)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81ba84df)
Location: include/asm-generic/atomic-long.h:105
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
Location: include/asm-generic/atomic-long.h:105
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811f97b4)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/events/core.c (ffffffff8124ad4a)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8129721c)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff812b0d02)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812b7490)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff812ca43a)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff812d3e65)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff812e6e75)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812f722a)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812fc8fa)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812ffbcc)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff81312104)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff81396bfb)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_unaccount_mem
```
```
In lib/genalloc.c (ffffffff815b78c7)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In net/core/sock.c (ffffffff819e55ac)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff819ed2ed)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa2dff)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_reinit
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02040)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81bb8245)
Location: include/asm-generic/atomic-long.h:105
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
Location: include/asm-generic/atomic-long.h:105
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811fa657)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/events/core.c (ffffffff8124f12a)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8129d057)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff812b6354)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812bcd60)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff812d0f67)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff812dad72)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff812ee665)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812fd6c0)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81303665)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff8130688c)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff81317ea4)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff81390d13)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_unmap
```
```
In lib/genalloc.c (ffffffff815c2734)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In net/core/sock.c (ffffffff819cb6bc)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff819d557a)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e1e4)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81aed950)
Location: include/asm-generic/atomic-long.h:105
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81ba7407)
Location: include/asm-generic/atomic-long.h:105
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
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8122bd67)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/events/core.c (ffffffff81289e5a)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff812de4a2)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff812f87fc)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812ff4da)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81316658)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81321d90)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff813368a5)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff813472f5)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8134d3cf)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff813506dc)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff81363c01)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff813de233)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_unmap
```
```
In lib/genalloc.c (ffffffff8162a685)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In net/core/sock.c (ffffffff81a7ad4c)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff81a85236)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81b493d4)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81badd10)
Location: include/linux/atomic/atomic-instrumented.h:1272
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81c7516b)
Location: include/linux/atomic/atomic-instrumented.h:1272
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
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8126d8e1)
Location: include/linux/atomic/atomic-instrumented.h:1359
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
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8133e570)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8135e9d6)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813665d2)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81381806)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8138eeea)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff813a81f5)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff813bd5a6)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813c3b5b)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In mm/page_counter.c (ffffffff813c89cc)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff813e0803)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In io_uring/io_uring.c (ffffffff816c7c7f)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_buffer_unmap
```
```
In lib/genalloc.c (ffffffff816fbaa5)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In net/core/sock.c (ffffffff81beec5f)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/skbuff.c (ffffffff81bfb25a)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6a77)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81d40daf)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81e19197)
Location: include/linux/atomic/atomic-instrumented.h:1359
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
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812c2d01)
Location: include/linux/atomic/atomic-instrumented.h:1359
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
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff813b55dc)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff813d989b)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813e21e2)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff813fff90)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8140d9d3)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff81429666)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff8143fd3e)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8144733a)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In mm/page_counter.c (ffffffff8144d0c2)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffffffff81462403)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:__free_raw_hwp_pages
```
```
In mm/zsmalloc.c (ffffffff81467cdb)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In io_uring/rsrc.c (ffffffff817a00bf)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_unmap
```
```
In io_uring/notif.c (ffffffff817a508e)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - io_uring/notif.c:io_notif_complete_tw_ext
```
```
In lib/genalloc.c (ffffffff817ee735)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/base/memory.c (ffffffff81b170d2)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_sub
```
```
In net/core/skbuff.c (ffffffff81da9f6a)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81e9706d)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81f09b2f)
Location: include/linux/atomic/atomic-instrumented.h:1359
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81ff057d)
Location: include/linux/atomic/atomic-instrumented.h:1359
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
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811d6e84)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812e9bf1)
Location: include/linux/atomic/atomic-instrumented.h:3396
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
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff813eac97)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8140e121)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81417026)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81432e3f)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81440d87)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff8145e9ed)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff81475566)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8147ca11)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In mm/page_counter.c (ffffffff81482982)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffffffff81496ecd)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:__folio_free_raw_hwp
```
```
In mm/zsmalloc.c (ffffffff8149cd44)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In io_uring/rsrc.c (ffffffff817e11bf)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_unmap
```
```
In io_uring/notif.c (ffffffff817e605e)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - io_uring/notif.c:io_notif_complete_tw_ext
```
```
In lib/genalloc.c (ffffffff8182eb2c)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/base/memory.c (ffffffff81b65e42)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_sub
```
```
In net/core/skbuff.c (ffffffff81e18d0a)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef585e)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6963f)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff8206c72b)
Location: include/linux/atomic/atomic-instrumented.h:3396
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
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811ed885)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_release_slots
```
```
In kernel/bpf/core.c (ffffffff81308141)
Location: include/linux/atomic/atomic-instrumented.h:3396
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
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff81417497)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8143a87a)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8143fc29)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/slub.c (ffffffff8145d0c2)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/swapfile.c (ffffffff8146c25f)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8147aeb7)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff814a4f5e)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814acd26)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff814b1d02)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffffffff814c6ccf)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:__folio_free_raw_hwp
```
```
In mm/zsmalloc.c (ffffffff814cc514)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In io_uring/rsrc.c (ffffffff81825adf)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_unmap
```
```
In io_uring/notif.c (ffffffff8182a27e)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - io_uring/notif.c:io_notif_complete_tw_ext
```
```
In lib/genalloc.c (ffffffff818806ec)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/base/memory.c (ffffffff81bb9cc2)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_sub
```
```
In net/core/skbuff.c (ffffffff81ed619a)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb980e)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff8202fcbf)
Location: include/linux/atomic/atomic-instrumented.h:3396
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff82140529)
Location: include/linux/atomic/atomic-instrumented.h:3396
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021af70)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
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
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffff800010264b88)
Location: include/asm-generic/atomic-long.h:104
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
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffff8000102f558c)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffff800010309f58)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffff80001030ef0c)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffff800010326d48)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffff8000103339ec)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffff8000103467ac)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffff800010357d10)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffff80001035dcac)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffff800010360c14)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffff8000103745e4)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffff80001040317c)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In lib/genalloc.c (ffff8000106445ec)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/perf/arm_pmu.c (ffff800010b95020)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_update
```
```
In net/core/sock.c (ffff800010bacc90)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffff800010bb3834)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffff800010c5fa00)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffff800010cbe9c0)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffff800010d80b90)
Location: include/asm-generic/atomic-long.h:104
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
In arch/arm/mm/pgd.c (c031f9c8)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - arch/arm/mm/pgd.c:pgd_free
```
```
In kernel/trace/ring_buffer.c (c0459748)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/bpf/core.c (c0491fb8)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (c0492dc4)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_uncharge_memlock
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (c04ceaa0)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (c0517610)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/vmalloc.c (c052a76c)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (c053e464)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/slub.c (c054b34c)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/page_counter.c (c0553358)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (c0561108)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (c05d687c)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In lib/genalloc.c (c07eaf04)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In net/core/sock.c (c0cc8860)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (c0cce98c)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (c0d6eadc)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (c0dca30c)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (c0e7b15c)
Location: include/asm-generic/atomic-long.h:598
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_unaccount_pages
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
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
```
```
In kernel/bpf/core.c (c0000000003038c0)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (c0000000003096fc)
Location: include/asm-generic/atomic-long.h:104
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
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (c0000000003bc7a0)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (c0000000003d9c18)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (c0000000003dfe88)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (c0000000003fd8a4)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (c00000000040c840)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (c0000000004247d0)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (c00000000043c14c)
Location: include/asm-generic/atomic-long.h:104
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
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (c00000000044bdac)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (c0000000004673f8)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (c00000000050fd28)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In lib/genalloc.c (c0000000007ef9ec)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In net/core/sock.c (c000000000c7fa44)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (c000000000c87d80)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (c000000000d61fe8)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (c000000000dd9254)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (c000000000ec0860)
Location: include/asm-generic/atomic-long.h:104
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
In kernel/trace/ring_buffer.c (ffffffe0001795f2)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
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
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffe0001a08cc)
Location: include/asm-generic/atomic-long.h:104
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
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffe000206b2a)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (0)
Location: include/asm-generic/atomic-long.h:104
Inline: True
```
```
In mm/vmalloc.c (ffffffe000217726)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
```
```
In mm/swapfile.c (ffffffe000226da0)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffe00022fb4c)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffe00023d3bc)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
```
```
In mm/page_counter.c (ffffffe000240416)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffe00024d5d0)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffe0002b0adc)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In lib/genalloc.c (ffffffe000470a7e)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In net/core/sock.c (ffffffe00073d5ca)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffe000745b82)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c7804)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffe000814b64)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad9fc)
Location: include/asm-generic/atomic-long.h:104
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
Location: include/asm-generic/atomic-long.h:104
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d6151)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d9b50)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff8120cd68)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff81255008)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8126cc1f)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81270c77)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81283f4a)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8128d280)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff8129ded5)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812af596)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b503b)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812b75da)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812c7f9d)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff8133d5f6)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In lib/genalloc.c (ffffffff8152fb46)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In net/core/sock.c (ffffffff818b2628)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff818b7c4d)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff8194ecbc)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5970)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81a4b6ed)
Location: include/asm-generic/atomic-long.h:104
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
Location: include/asm-generic/atomic-long.h:104
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811c8f11)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811cc910)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff811ffb38)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff81248c55)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffffffff8125ec6c)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81262be7)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81275dda)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8127f06f)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff8128fa55)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812a0b87)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812a6069)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812a87aa)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812b8fdd)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff8132e2b6)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In lib/genalloc.c (ffffffff8151fe26)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In net/core/sock.c (ffffffff8186c578)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff81871b9d)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819087ac)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f430)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81a082dd)
Location: include/asm-generic/atomic-long.h:104
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
Location: include/asm-generic/atomic-long.h:104
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d3f21)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d7920)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff8120ab08)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff81252da8)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8126a9bf)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8126ea17)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81281d5a)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8128b090)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff8129bce5)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812ad3a6)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b2e4b)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812b53ea)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812c5dad)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff8133b0c6)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In lib/genalloc.c (ffffffff8152b886)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In net/core/sock.c (ffffffff81903628)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff81908c4d)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819b948c)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10210)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81ab759d)
Location: include/asm-generic/atomic-long.h:104
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
Location: include/asm-generic/atomic-long.h:104
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811e2241)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811e5cc0)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff812198f1)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff81262708)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8127a339)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8127e42d)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81291a66)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8129aeb0)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff812abbf5)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812bd727)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812c3286)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812c592a)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff812d75fd)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff8134e276)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In lib/genalloc.c (ffffffff8154561e)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In net/core/sock.c (ffffffff81924608)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff81929cfd)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_unaccount_pinned_pages
```
```
In net/ipv4/ip_fragment.c (ffffffff819c2d7c)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1aa60)
Location: include/asm-generic/atomic-long.h:104
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81ac39bd)
Location: include/asm-generic/atomic-long.h:104
Inline: True
```
</details>
</li>
</ul>

## Differences
