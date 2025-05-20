# Function: <code>arch_atomic64_dec</code>

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
In kernel/events/uprobes.c (ffffffff811e4d29)
Location: arch/x86/include/asm/atomic64_64.h:98
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/rmap.c (ffffffff8123f0ed)
Location: arch/x86/include/asm/atomic64_64.h:98
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8124a419)
Location: arch/x86/include/asm/atomic64_64.h:98
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/ksm.c (ffffffff81260954)
Location: arch/x86/include/asm/atomic64_64.h:98
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff81265470)
Location: arch/x86/include/asm/atomic64_64.h:98
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff81289e1b)
Location: arch/x86/include/asm/atomic64_64.h:98
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/inode.c (ffffffff812b8054)
Location: arch/x86/include/asm/atomic64_64.h:98
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff812eb675)
Location: arch/x86/include/asm/atomic64_64.h:98
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff81959b65)
Location: arch/x86/include/asm/atomic64_64.h:98
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff8195d2e5)
Location: arch/x86/include/asm/atomic64_64.h:98
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff81265960)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8127af72)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/ksm.c (ffffffff8128f968)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (ffffffff81295b10)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff812ba49b)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/zsmalloc.c (ffffffff812be50b)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff812ea35e)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff813202ca)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff819f9e35)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff819fd665)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff81274275)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8128aa52)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff8129da3b)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff8129f709)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (ffffffff812a58f0)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff812cbbcb)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff812fbcc5)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff8133307a)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff81a30ab5)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81a34255)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff812d16cf)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff812da5b0)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff813025ea)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff81334a65)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff8136d46a)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff81b24ce5)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81b29065)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff812dd1ef)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff812e6e70)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff8130e3cb)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff813403d5)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff8137ae6d)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff81b33875)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81b37995)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff812e4a45)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff812ee660)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff813149a4)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff81346905)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff813819e4)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff81b21437)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81b25635)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
```
```
In kernel/ucount.c (ffffffff810ea25b)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/bpf/syscall.c (ffffffff8122eb70)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:bpf_map_mmap_close
```
```
In mm/swapfile.c (ffffffff81315d66)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff8132bcc5)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff813368a0)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/kfence/core.c (ffffffff8133c4cd)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
```
```
In mm/memory-failure.c (ffffffff81360cd9)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff81394335)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In net/unix/af_unix.c (ffffffff81be6579)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81bead45)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
```
```
In kernel/ucount.c (ffffffff81104ecc)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/bpf/syscall.c (ffffffff812713d2)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:bpf_map_mmap_close
```
```
In mm/swapfile.c (ffffffff81381ec9)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff813a81f0)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/kfence/core.c (ffffffff813af71a)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
```
```
In mm/memory-failure.c (ffffffff813dd76f)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/memory-failure.c:clear_hwpoisoned_pages
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/inode.c (ffffffff8141607d)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In net/unix/af_unix.c (ffffffff81d7efd5)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81d82ff5)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
```
```
In kernel/ucount.c (ffffffff8112a825)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/bpf/syscall.c (ffffffff812c7251)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:bpf_map_mmap_close
```
```
In mm/swapfile.c (ffffffff81400689)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff81429661)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/kfence/core.c (ffffffff8142fcaa)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
```
```
In fs/inode.c (ffffffff814a10dd)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In net/unix/af_unix.c (ffffffff81f4c32e)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81f50645)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
```
```
In kernel/ucount.c (ffffffff811378a5)
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/bpf/syscall.c (ffffffff812ee81b)
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:bpf_map_mmap_close
```
```
In mm/swapfile.c (ffffffff81433529)
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff8145e9e8)
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/kfence/core.c (ffffffff814655f9)
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
```
```
In fs/inode.c (ffffffff814d63ed)
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In net/unix/af_unix.c (ffffffff81fac116)
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81faffb5)
Location: arch/x86/include/asm/atomic64_64.h:51
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
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
```
```
In kernel/ucount.c (ffffffff81142ab5)
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/bpf/core.c (ffffffff81308caf)
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_free_used_maps
```
```
In kernel/bpf/syscall.c (ffffffff8130d604)
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:bpf_map_mmap_close
```
```
In mm/slub.c (ffffffff8145d0bd)
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/swapfile.c (ffffffff8146c919)
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/kfence/core.c (ffffffff81494959)
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
```
```
In fs/inode.c (ffffffff815087bd)
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In net/unix/af_unix.c (ffffffff82079536)
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff8207d615)
Location: arch/x86/include/asm/atomic64_64.h:51
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
```
```
In net/packet/af_packet.c (ffffffff820f4e70)
Location: arch/x86/include/asm/atomic64_64.h:51
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812129e2)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff8126c8c5)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81283032)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff8129601b)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff81297ce9)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (ffffffff8129ded0)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff812c41ab)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff812f42a5)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff8132b65a)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff819d0145)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff819d38e5)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff8125e917)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81274fe8)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff81287c2b)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff8128989c)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (ffffffff8128fa50)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff812b51eb)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff812e4ed5)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff8131cfb4)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff8198cf05)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff819906a5)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff8126a665)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81280e42)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff81293e2b)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff81295af9)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (ffffffff8129bce0)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff812c1fbb)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff812f20b5)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff8132912a)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff81a3abc5)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81a3e365)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff8127a043)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81290b52)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff812a3c8b)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff812a58f3)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (ffffffff812abbf0)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memory-failure.c (ffffffff812d2a5b)
Location: arch/x86/include/asm/atomic64_64.h:100
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
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff81303685)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/eventpoll.c (ffffffff8133b858)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In net/unix/af_unix.c (ffffffff81a45e45)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81a49e25)
Location: arch/x86/include/asm/atomic64_64.h:100
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
```
</details>
</li>
</ul>

## Differences
