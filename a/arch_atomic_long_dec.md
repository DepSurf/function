# Function: <code>arch_atomic_long_dec</code>

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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81073468)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
```
```
In kernel/ucount.c (ffffffff810ea25b)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In mm/swapfile.c (ffffffff81315d66)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/sparse.c (ffffffff8132bcc5)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff813368a0)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/kfence/core.c (ffffffff8133c4cd)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
```
```
In mm/memory-failure.c (ffffffff81360cd9)
Location: include/linux/atomic/atomic-long.h:213
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
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/inode.c (ffffffff81394335)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In net/unix/af_unix.c (ffffffff81be6579)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81bead45)
Location: include/linux/atomic/atomic-long.h:213
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
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
```
```
In kernel/ucount.c (ffffffff81104ecc)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In mm/swapfile.c (ffffffff81381ec9)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff813a81f0)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/kfence/core.c (ffffffff813af71a)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
```
```
In mm/memory-failure.c (ffffffff813dd76f)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/memory-failure.c:clear_hwpoisoned_pages
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/inode.c (ffffffff8141607d)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In net/unix/af_unix.c (ffffffff81d7efd5)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81d82ff5)
Location: include/linux/atomic/atomic-long.h:213
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
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
```
```
In kernel/ucount.c (ffffffff8112a825)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In mm/swapfile.c (ffffffff81400689)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff81429661)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/kfence/core.c (ffffffff8142fcaa)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
```
```
In fs/inode.c (ffffffff814a10dd)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In net/unix/af_unix.c (ffffffff81f4c32e)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81f50645)
Location: include/linux/atomic/atomic-long.h:213
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
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
