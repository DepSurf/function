# Function: <code>raw_atomic64_sub</code>

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
In arch/x86/mm/pgtable.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811d6e84)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812e9bf1)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
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
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff813eac97)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8140e121)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81417026)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swapfile.c (ffffffff81432e3f)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81440d87)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/slub.c (ffffffff8145e9ed)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff81475566)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8147ca11)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In mm/page_counter.c (ffffffff81482982)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffffffff81496ecd)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:__folio_free_raw_hwp
```
```
In mm/zsmalloc.c (ffffffff8149cd44)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/ext4/mballoc.c (ffffffff815cbb5b)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In block/blk-cgroup.c (ffffffff8179f084)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In io_uring/rsrc.c (ffffffff817e11bf)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_unmap
  - io_uring/rsrc.c:io_buffer_unmap
```
```
In io_uring/notif.c (ffffffff817e605e)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - io_uring/notif.c:io_notif_complete_tw_ext
```
```
In lib/genalloc.c (ffffffff8182eb2c)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/base/memory.c (ffffffff81b65e42)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_sub
```
```
In net/core/skbuff.c (ffffffff81e18d0a)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef585e)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6963f)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff8206c72b)
Location: include/linux/atomic/atomic-arch-fallback.h:2874
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
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811ed885)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_release_slots
```
```
In kernel/bpf/core.c (ffffffff81308141)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
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
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memory.c (ffffffff81417497)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/rmap.c (ffffffff8143a87a)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8143fc29)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/slub.c (ffffffff8145d0c2)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/swapfile.c (ffffffff8146c25f)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8147aeb7)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff814a4f5e)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814acd26)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff814b1d02)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
```
```
In mm/memory-failure.c (ffffffff814c6ccf)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:__folio_free_raw_hwp
```
```
In mm/zsmalloc.c (ffffffff814cc514)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/ext4/mballoc.c (ffffffff81601710)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_context
```
```
In block/blk-cgroup.c (ffffffff817e2b54)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In io_uring/rsrc.c (ffffffff81825adf)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_unmap
  - io_uring/rsrc.c:io_buffer_unmap
```
```
In io_uring/notif.c (ffffffff8182a27e)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - io_uring/notif.c:io_notif_complete_tw_ext
```
```
In lib/genalloc.c (ffffffff818806ec)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/base/memory.c (ffffffff81bb9cc2)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_sub
```
```
In net/core/skbuff.c (ffffffff81ed619a)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb980e)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff8202fcbf)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
```
In net/xdp/xdp_umem.c (ffffffff82140529)
Location: include/linux/atomic/atomic-arch-fallback.h:2879
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
