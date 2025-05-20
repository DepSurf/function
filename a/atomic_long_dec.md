# Function: <code>atomic_long_dec</code>

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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/atomic-long.h:108
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8118780f)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811bcea3)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffffffff811cb246)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff811d4582)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:get_swap_page
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/hugetlb.c (ffffffff811dd646)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/slub.c (ffffffff811e9230)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff811f6a64)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81201dad)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/inode.c (ffffffff81226cea)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff81254ba1)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff817be0d0)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff817c20b9)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/atomic-long.h:108
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81199fcc)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811d7c61)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffffffff811e833c)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff811f23f8)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_page
```
```
In mm/hugetlb.c (ffffffff811fb918)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/slub.c (ffffffff81208d10)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812159ad)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8121b607)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff8122786d)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/inode.c (ffffffff8124f40a)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff8127d3d5)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff8182b064)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff8182f0c9)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/atomic-long.h:108
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff811a9700)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811e7953)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffffffff811f9790)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81202df3)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_page
```
```
In mm/hugetlb.c (ffffffff8120c412)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/slub.c (ffffffff8121ad90)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff81227f5e)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8122cc87)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff81239df7)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/inode.c (ffffffff8126243a)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff81290f65)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff8185ca94)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81860b49)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/atomic-long.h:108
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff811b0bde)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811f2aae)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/rmap.c (ffffffff81204411)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8120de96)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/hugetlb.c (ffffffff81217da9)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/slub.c (ffffffff812267d0)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/huge_memory.c (ffffffff812340e5)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8123925f)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff81245ab5)
Location: include/asm-generic/atomic-long.h:108
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
In fs/inode.c (ffffffff8126fc85)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff8129de55)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff81881085)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff818852a9)
Location: include/asm-generic/atomic-long.h:108
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In kernel/events/uprobes.c (ffffffff811c4764)
Location: include/asm-generic/atomic-long.h:109
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/rmap.c (ffffffff8121d1f0)
Location: include/asm-generic/atomic-long.h:109
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81229106)
Location: include/asm-generic/atomic-long.h:109
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff81241810)
Location: include/asm-generic/atomic-long.h:109
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff81265a68)
Location: include/asm-generic/atomic-long.h:109
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
In fs/inode.c (ffffffff812925a4)
Location: include/asm-generic/atomic-long.h:109
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff812c1045)
Location: include/asm-generic/atomic-long.h:109
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff81902215)
Location: include/asm-generic/atomic-long.h:109
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81906459)
Location: include/asm-generic/atomic-long.h:109
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In kernel/events/uprobes.c (ffffffff811e4d29)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/rmap.c (ffffffff8123f0ed)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8124a419)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/ksm.c (ffffffff81260954)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff81265470)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff81289e1b)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/inode.c (ffffffff812b8054)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff812eb675)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff81959b65)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff8195d2e5)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In kernel/events/uprobes.c (ffffffff811f5391)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff81253708)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8125ea59)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/ksm.c (ffffffff812750b4)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff8127a1a0)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff8129ed8d)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/inode.c (ffffffff812cd1a4)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff812ff14f)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff8198e6e5)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81991e25)
Location: include/asm-generic/atomic-long.h:126
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In kernel/events/uprobes.c (ffffffff8120d05b)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff81265960)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8127af72)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/ksm.c (ffffffff8128f968)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (ffffffff81295b10)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff812ba49b)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/zsmalloc.c (ffffffff812be50b)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff812ea35e)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff813202ca)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff819f9e35)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff819fd665)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In kernel/events/uprobes.c (ffffffff8121a392)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff81274275)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8128aa52)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff8129da3b)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff8129f709)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (ffffffff812a58f0)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff812cbbcb)
Location: include/asm-generic/atomic-long.h:212
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
In mm/zsmalloc.c (ffffffff812d03fb)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff812fbcc5)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff8133307a)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff81a30ab5)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81a34255)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In mm/swapfile.c (ffffffff812bd774)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff812d16cf)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff812da5b0)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff813025ea)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff813069ab)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff81334a65)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff8136d46a)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff81b24ce5)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81b29065)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In mm/swapfile.c (ffffffff812c92cd)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff812dd1ef)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff812e6e70)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff8130e3cb)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff813126eb)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff813403d5)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff8137ae6d)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff81b33875)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81b37995)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In mm/swapfile.c (ffffffff812cfe4d)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff812e4a45)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff812ee660)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff813149a4)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff81318c0b)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff81346905)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff813819e4)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff81b21437)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81b25635)
Location: include/asm-generic/atomic-long.h:213
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81073468)
Location: include/linux/atomic/atomic-instrumented.h:1398
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
```
```
In kernel/ucount.c (ffffffff810ea25b)
Location: include/linux/atomic/atomic-instrumented.h:1398
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In mm/swapfile.c (ffffffff81315d66)
Location: include/linux/atomic/atomic-instrumented.h:1398
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff8132bcc5)
Location: include/linux/atomic/atomic-instrumented.h:1398
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff813368a0)
Location: include/linux/atomic/atomic-instrumented.h:1398
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/kfence/core.c (ffffffff8133c4cd)
Location: include/linux/atomic/atomic-instrumented.h:1398
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
```
```
In mm/memory-failure.c (ffffffff81360cd9)
Location: include/linux/atomic/atomic-instrumented.h:1398
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff813651c8)
Location: include/linux/atomic/atomic-instrumented.h:1398
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff81394335)
Location: include/linux/atomic/atomic-instrumented.h:1398
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In net/unix/af_unix.c (ffffffff81be6579)
Location: include/linux/atomic/atomic-instrumented.h:1398
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81bead45)
Location: include/linux/atomic/atomic-instrumented.h:1398
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810808dc)
Location: include/linux/atomic/atomic-instrumented.h:1493
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
```
```
In kernel/ucount.c (ffffffff81104ecc)
Location: include/linux/atomic/atomic-instrumented.h:1493
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In mm/swapfile.c (ffffffff81381ec9)
Location: include/linux/atomic/atomic-instrumented.h:1493
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff813a81f0)
Location: include/linux/atomic/atomic-instrumented.h:1493
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/kfence/core.c (ffffffff813af71a)
Location: include/linux/atomic/atomic-instrumented.h:1493
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
```
```
In mm/memory-failure.c (ffffffff813dd76f)
Location: include/linux/atomic/atomic-instrumented.h:1493
Inline: True
Inline callers:
  - mm/memory-failure.c:clear_hwpoisoned_pages
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/inode.c (ffffffff8141607d)
Location: include/linux/atomic/atomic-instrumented.h:1493
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In net/unix/af_unix.c (ffffffff81d7efd5)
Location: include/linux/atomic/atomic-instrumented.h:1493
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81d82ff5)
Location: include/linux/atomic/atomic-instrumented.h:1493
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109347c)
Location: include/linux/atomic/atomic-instrumented.h:1493
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
```
```
In kernel/ucount.c (ffffffff8112a825)
Location: include/linux/atomic/atomic-instrumented.h:1493
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In mm/swapfile.c (ffffffff81400689)
Location: include/linux/atomic/atomic-instrumented.h:1493
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff81429661)
Location: include/linux/atomic/atomic-instrumented.h:1493
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/kfence/core.c (ffffffff8142fcaa)
Location: include/linux/atomic/atomic-instrumented.h:1493
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
```
```
In fs/inode.c (ffffffff814a10dd)
Location: include/linux/atomic/atomic-instrumented.h:1493
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In net/unix/af_unix.c (ffffffff81f4c32e)
Location: include/linux/atomic/atomic-instrumented.h:1493
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81f50645)
Location: include/linux/atomic/atomic-instrumented.h:1493
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810963dc)
Location: include/linux/atomic/atomic-instrumented.h:3718
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
```
```
In kernel/ucount.c (ffffffff811378a5)
Location: include/linux/atomic/atomic-instrumented.h:3718
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In mm/swapfile.c (ffffffff81433529)
Location: include/linux/atomic/atomic-instrumented.h:3718
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff8145e9e8)
Location: include/linux/atomic/atomic-instrumented.h:3718
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/kfence/core.c (ffffffff814655f9)
Location: include/linux/atomic/atomic-instrumented.h:3718
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
```
```
In fs/inode.c (ffffffff814d63ed)
Location: include/linux/atomic/atomic-instrumented.h:3718
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In net/unix/af_unix.c (ffffffff81fac116)
Location: include/linux/atomic/atomic-instrumented.h:3718
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81faffb5)
Location: include/linux/atomic/atomic-instrumented.h:3718
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109d94c)
Location: include/linux/atomic/atomic-instrumented.h:3718
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
```
```
In kernel/ucount.c (ffffffff81142ab5)
Location: include/linux/atomic/atomic-instrumented.h:3718
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In mm/slub.c (ffffffff8145d0bd)
Location: include/linux/atomic/atomic-instrumented.h:3718
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/swapfile.c (ffffffff8146c919)
Location: include/linux/atomic/atomic-instrumented.h:3718
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/kfence/core.c (ffffffff81494959)
Location: include/linux/atomic/atomic-instrumented.h:3718
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
```
```
In fs/inode.c (ffffffff815087bd)
Location: include/linux/atomic/atomic-instrumented.h:3718
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In net/unix/af_unix.c (ffffffff82079536)
Location: include/linux/atomic/atomic-instrumented.h:3718
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff8207d615)
Location: include/linux/atomic/atomic-instrumented.h:3718
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
```
```
In net/packet/af_packet.c (ffffffff820f4e70)
Location: include/linux/atomic/atomic-instrumented.h:3718
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
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
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/uprobes.c (ffff8000102a57bc)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffff800010309e78)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffff8000103260c8)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffff80001033cb80)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffff80001033ef3c)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffff800010346780)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffff80001036fe38)
Location: include/asm-generic/atomic-long.h:212
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
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffff8000103acd34)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffff8000103f033c)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In block/genhd.c (ffff8000105fabd4)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_dec_in_flight
```
```
In net/unix/af_unix.c (ffff800010cf0d84)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffff800010cf475c)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In kernel/trace/ring_buffer.c (c045b3bc)
Location: include/asm-generic/atomic-long.h:706
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/uprobes.c (c04d4b9c)
Location: include/asm-generic/atomic-long.h:706
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (c05266c4)
Location: include/asm-generic/atomic-long.h:706
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (c053d90c)
Location: include/asm-generic/atomic-long.h:706
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/ksm.c (c0544f94)
Location: include/asm-generic/atomic-long.h:706
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (c054b330)
Location: include/asm-generic/atomic-long.h:706
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/zsmalloc.c (c05613cc)
Location: include/asm-generic/atomic-long.h:706
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (c058c6a0)
Location: include/asm-generic/atomic-long.h:706
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (c05c76ec)
Location: include/asm-generic/atomic-long.h:706
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In block/genhd.c (c07a5d44)
Location: include/asm-generic/atomic-long.h:706
Inline: True
Inline callers:
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_dec_in_flight
```
```
In net/unix/af_unix.c (c0df7874)
Location: include/asm-generic/atomic-long.h:706
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (c0dfb4c0)
Location: include/asm-generic/atomic-long.h:706
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In kernel/events/uprobes.c (c000000000358554)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (c0000000003d9ae4)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (c0000000003fc618)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (c000000000417d20)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (c00000000041af30)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (c0000000004247bc)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (c000000000460bc4)
Location: include/asm-generic/atomic-long.h:212
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
In mm/zsmalloc.c (c000000000467868)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (c0000000004a657c)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (c0000000004f9a78)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (c000000000e1471c)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (c000000000e1a75c)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In mm/rmap.c (ffffffe000213dfe)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffe000226432)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/ksm.c (ffffffe000234b12)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffe00023d3a2)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
```
```
In mm/zsmalloc.c (ffffffe00024dfa4)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffe000270d2c)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffe0002a3d60)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In block/genhd.c (ffffffe000436ee6)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_dec_in_flight
```
```
In net/unix/af_unix.c (ffffffe00083d102)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffe0008405b4)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In kernel/events/uprobes.c (ffffffff812129e2)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff8126c8c5)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81283032)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff8129601b)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff81297ce9)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (ffffffff8129ded0)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff812c41ab)
Location: include/asm-generic/atomic-long.h:212
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
In mm/zsmalloc.c (ffffffff812c89db)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff812f42a5)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff8132b65a)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff819d0145)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff819d38e5)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In kernel/events/uprobes.c (ffffffff8120574a)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff8125e917)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81274fe8)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff81287c2b)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff8128989c)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (ffffffff8128fa50)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff812b51eb)
Location: include/asm-generic/atomic-long.h:212
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
In mm/zsmalloc.c (ffffffff812b9a1b)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff812e4ed5)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff8131cfb4)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff8198cf05)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff819906a5)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In kernel/events/uprobes.c (ffffffff81210782)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff8126a665)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81280e42)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff81293e2b)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff81295af9)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (ffffffff8129bce0)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff812c1fbb)
Location: include/asm-generic/atomic-long.h:212
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
In mm/zsmalloc.c (ffffffff812c67eb)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff812f20b5)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff8132912a)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff81a3abc5)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81a3e365)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
In kernel/events/uprobes.c (ffffffff8121f693)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff8127a043)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81290b52)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff812a3c8b)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff812a58f3)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (ffffffff812abbf0)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff812d2a5b)
Location: include/asm-generic/atomic-long.h:212
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
In mm/zsmalloc.c (ffffffff812d74f9)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff81303685)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff8133b858)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff81a45e45)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81a49e25)
Location: include/asm-generic/atomic-long.h:212
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
```
</details>
</li>
</ul>

## Differences
