# Function: <code>arch_atomic_long_sub</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8122bd67)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/events/core.c (ffffffff81289e5a)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff812de4a2)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff812f87fc)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812ff4da)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81316658)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81321d90)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff813368a5)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff813472f5)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8134d3cf)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff813506dc)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff81363c01)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/io_uring.c (ffffffff813de233)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_unmap
```
```
In lib/genalloc.c (ffffffff8162a685)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In net/core/sock.c (ffffffff81a7ad4c)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (ffffffff81a85236)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81b493d4)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81badd10)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81c7516b)
Location: include/linux/atomic/atomic-long.h:105
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
Location: include/linux/atomic/atomic-long.h:105
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8126d8e1)
Location: include/linux/atomic/atomic-long.h:105
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
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff8133e570)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8135e9d6)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813665d2)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81381806)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8138eeea)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff813a81f5)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff813bd5a6)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813c3b5b)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In mm/page_counter.c (ffffffff813c89cc)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/zsmalloc.c (ffffffff813e0803)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In io_uring/io_uring.c (ffffffff816c7c7f)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_buffer_unmap
```
```
In lib/genalloc.c (ffffffff816fbaa5)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In net/core/sock.c (ffffffff81beec5f)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/skbuff.c (ffffffff81bfb25a)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6a77)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81d40daf)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81e19197)
Location: include/linux/atomic/atomic-long.h:105
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
Location: include/linux/atomic/atomic-long.h:105
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812c2d01)
Location: include/linux/atomic/atomic-long.h:105
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
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff813b55dc)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff813d989b)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813e21e2)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff813fff90)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8140d9d3)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff81429666)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff8143fd3e)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8144733a)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In mm/page_counter.c (ffffffff8144d0c2)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffffffff81462403)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:__free_raw_hwp_pages
```
```
In mm/zsmalloc.c (ffffffff81467cdb)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In io_uring/rsrc.c (ffffffff817a00bf)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_unmap
```
```
In io_uring/notif.c (ffffffff817a508e)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - io_uring/notif.c:io_notif_complete_tw_ext
```
```
In lib/genalloc.c (ffffffff817ee735)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/base/memory.c (ffffffff81b170d2)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_sub
```
```
In net/core/skbuff.c (ffffffff81da9f6a)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81e9706d)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81f09b2f)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff81ff057d)
Location: include/linux/atomic/atomic-long.h:105
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
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
