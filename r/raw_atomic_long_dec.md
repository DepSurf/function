# Function: <code>raw_atomic_long_dec</code>

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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810963dc)
Location: include/linux/atomic/atomic-long.h:675
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
```
```
In kernel/ucount.c (ffffffff811378a5)
Location: include/linux/atomic/atomic-long.h:675
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In mm/swapfile.c (ffffffff81433529)
Location: include/linux/atomic/atomic-long.h:675
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff8145e9e8)
Location: include/linux/atomic/atomic-long.h:675
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/kfence/core.c (ffffffff814655f9)
Location: include/linux/atomic/atomic-long.h:675
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
```
```
In fs/inode.c (ffffffff814d63ed)
Location: include/linux/atomic/atomic-long.h:675
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In net/unix/af_unix.c (ffffffff81fac116)
Location: include/linux/atomic/atomic-long.h:675
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff81faffb5)
Location: include/linux/atomic/atomic-long.h:675
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
Location: include/linux/atomic/atomic-long.h:675
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
```
```
In kernel/ucount.c (ffffffff81142ab5)
Location: include/linux/atomic/atomic-long.h:675
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In mm/slub.c (ffffffff8145d0bd)
Location: include/linux/atomic/atomic-long.h:675
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
```
In mm/swapfile.c (ffffffff8146c919)
Location: include/linux/atomic/atomic-long.h:675
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/kfence/core.c (ffffffff81494959)
Location: include/linux/atomic/atomic-long.h:675
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
```
```
In fs/inode.c (ffffffff815087bd)
Location: include/linux/atomic/atomic-long.h:675
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In net/unix/af_unix.c (ffffffff82079536)
Location: include/linux/atomic/atomic-long.h:675
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (ffffffff8207d615)
Location: include/linux/atomic/atomic-long.h:675
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
```
```
In net/packet/af_packet.c (ffffffff820f4e70)
Location: include/linux/atomic/atomic-long.h:675
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
