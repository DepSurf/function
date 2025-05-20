# Function: <code>prefetchw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void prefetchw(const void *x);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106b3d7)
Location: arch/x86/include/asm/processor.h:685
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In mm/page_alloc.c (ffffffff81208c99)
Location: arch/x86/include/asm/processor.h:685
Inline: False
Direct callers:
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/vmscan.c (ffffffff811a2744)
Location: arch/x86/include/asm/processor.h:685
Inline: True
```
```
In fs/inode.c (ffffffff8122903a)
Location: arch/x86/include/asm/processor.h:685
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff8124e759)
Location: arch/x86/include/asm/processor.h:685
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff812e2efe)
Location: arch/x86/include/asm/processor.h:685
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff817069c7)
Location: arch/x86/include/asm/processor.h:685
Inline: True
Inline callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8176d126)
Location: arch/x86/include/asm/processor.h:685
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81208c99-ffffffff81208ca2: prefetchw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void prefetchw(const void *x);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106b1eb)
Location: arch/x86/include/asm/processor.h:696
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff810cf503)
Location: arch/x86/include/asm/processor.h:696
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In mm/page_alloc.c (ffffffff8122e988)
Location: arch/x86/include/asm/processor.h:696
Inline: False
Direct callers:
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/vmscan.c (ffffffff811b8b76)
Location: arch/x86/include/asm/processor.h:696
Inline: True
```
```
In fs/inode.c (ffffffff8125173a)
Location: arch/x86/include/asm/processor.h:696
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff81276ed5)
Location: arch/x86/include/asm/processor.h:696
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff81312ddd)
Location: arch/x86/include/asm/processor.h:696
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff81773b14)
Location: arch/x86/include/asm/processor.h:696
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff817dda33)
Location: arch/x86/include/asm/processor.h:696
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff8122e988-ffffffff8122e991: prefetchw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void prefetchw(const void *x);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106edfb)
Location: arch/x86/include/asm/processor.h:771
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff810d5ef3)
Location: arch/x86/include/asm/processor.h:771
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In mm/page_alloc.c (ffffffff81240ed4)
Location: arch/x86/include/asm/processor.h:771
Inline: False
Direct callers:
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/vmscan.c (ffffffff811c91a6)
Location: arch/x86/include/asm/processor.h:771
Inline: True
```
```
In fs/inode.c (ffffffff8126483a)
Location: arch/x86/include/asm/processor.h:771
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff8128ab98)
Location: arch/x86/include/asm/processor.h:771
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff81328d8d)
Location: arch/x86/include/asm/processor.h:771
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff817a0d41)
Location: arch/x86/include/asm/processor.h:771
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8180dbe1)
Location: arch/x86/include/asm/processor.h:771
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff81240ed4-ffffffff81240edd: prefetchw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void prefetchw(const void *x);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106e56b)
Location: arch/x86/include/asm/processor.h:784
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff810d4ebb)
Location: arch/x86/include/asm/processor.h:784
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In mm/page_alloc.c (ffffffff811c5568)
Location: arch/x86/include/asm/processor.h:784
Inline: False
Direct callers:
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/vmscan.c (ffffffff811d1cf2)
Location: arch/x86/include/asm/processor.h:784
Inline: True
```
```
In fs/inode.c (ffffffff8127206d)
Location: arch/x86/include/asm/processor.h:784
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff812979d9)
Location: arch/x86/include/asm/processor.h:784
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff8131e8da)
Location: arch/x86/include/asm/processor.h:784
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff817bdd41)
Location: arch/x86/include/asm/processor.h:784
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8182e13f)
Location: arch/x86/include/asm/processor.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff811c5568-ffffffff811c5571: prefetchw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void prefetchw(const void *x);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107361a)
Location: arch/x86/include/asm/processor.h:806
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff810dcc78)
Location: arch/x86/include/asm/processor.h:806
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In mm/page_alloc.c (ffffffff811da318)
Location: arch/x86/include/asm/processor.h:806
Inline: False
Direct callers:
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/vmscan.c (ffffffff811e7192)
Location: arch/x86/include/asm/processor.h:806
Inline: True
```
```
In fs/inode.c (ffffffff8129498d)
Location: arch/x86/include/asm/processor.h:806
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff812bac61)
Location: arch/x86/include/asm/processor.h:806
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff81342f01)
Location: arch/x86/include/asm/processor.h:806
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff81837391)
Location: arch/x86/include/asm/processor.h:806
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff811da318-ffffffff811da321: prefetchw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void prefetchw(const void *x);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81075f6a)
Location: arch/x86/include/asm/processor.h:820
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff810e52af)
Location: arch/x86/include/asm/processor.h:820
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In mm/page_alloc.c (ffffffff811fac11)
Location: arch/x86/include/asm/processor.h:820
Inline: False
Direct callers:
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/vmscan.c (ffffffff812086e8)
Location: arch/x86/include/asm/processor.h:820
Inline: True
```
```
In fs/inode.c (ffffffff812baa85)
Location: arch/x86/include/asm/processor.h:820
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff812e37dd)
Location: arch/x86/include/asm/processor.h:820
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff81370d58)
Location: arch/x86/include/asm/processor.h:820
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff81881851)
Location: arch/x86/include/asm/processor.h:820
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff811fac11-ffffffff811fac1a: prefetchw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void prefetchw(const void *x);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107c1ef)
Location: arch/x86/include/asm/processor.h:815
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff810f0899)
Location: arch/x86/include/asm/processor.h:815
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In mm/page_alloc.c (ffffffff8120d455)
Location: arch/x86/include/asm/processor.h:815
Inline: False
Direct callers:
  - mm/page_alloc.c:memblock_free_pages
  - mm/page_alloc.c:memblock_free_pages
```
```
In mm/vmscan.c (ffffffff8121b378)
Location: arch/x86/include/asm/processor.h:815
Inline: True
```
```
In fs/inode.c (ffffffff812cfdc5)
Location: arch/x86/include/asm/processor.h:815
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff812f8484)
Location: arch/x86/include/asm/processor.h:815
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff813891fd)
Location: arch/x86/include/asm/processor.h:815
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff818a2371)
Location: arch/x86/include/asm/processor.h:815
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff8120d455-ffffffff8120d45e: prefetchw (STB_LOCAL)
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
In arch/x86/mm/fault.c (ffffffff8107ff3f)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff810f90bc)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/bpf/cpumap.c (ffffffff811f3c6a)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/vmscan.c (ffffffff8122b00d)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff812704c1)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In fs/inode.c (ffffffff812ecd15)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff81318ab6)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff813b33dc)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff818ed041)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
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
In arch/x86/mm/fault.c (ffffffff81080fcf)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff81104e9e)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/bpf/cpumap.c (ffffffff81200a0a)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/vmscan.c (ffffffff81238edd)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff8127f301)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In fs/inode.c (ffffffff812fe8a5)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff8132b8f6)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff813cc5ac)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff8191f161)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
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
In arch/x86/mm/fault.c (ffffffff81bbf606)
Location: arch/x86/include/asm/processor.h:826
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff8110fd0f)
Location: arch/x86/include/asm/processor.h:826
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/bpf/cpumap.c (ffffffff812284c2)
Location: arch/x86/include/asm/processor.h:826
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/vmscan.c (ffffffff81267a13)
Location: arch/x86/include/asm/processor.h:826
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff812b15f4)
Location: arch/x86/include/asm/processor.h:826
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In fs/inode.c (ffffffff81335ee5)
Location: arch/x86/include/asm/processor.h:826
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff8136557a)
Location: arch/x86/include/asm/processor.h:826
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/ext4/readpage.c (ffffffff81418776)
Location: arch/x86/include/asm/processor.h:826
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff819f22c7)
Location: arch/x86/include/asm/processor.h:826
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
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
In arch/x86/mm/fault.c (ffffffff81c38495)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff8110cecf)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/bpf/cpumap.c (ffffffff8122f27b)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/vmscan.c (ffffffff81272433)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff812bb3f4)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In fs/inode.c (ffffffff81341875)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff8137244a)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/ext4/readpage.c (ffffffff8142c2b9)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff819f22c7)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/ipv4/tcp.c (ffffffff81ab7173)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
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
In arch/x86/mm/fault.c (ffffffff81c2a885)
Location: arch/x86/include/asm/processor.h:728
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff8110ec3c)
Location: arch/x86/include/asm/processor.h:728
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/bpf/cpumap.c (ffffffff81234193)
Location: arch/x86/include/asm/processor.h:728
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/vmscan.c (ffffffff81277760)
Location: arch/x86/include/asm/processor.h:728
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff812c0564)
Location: arch/x86/include/asm/processor.h:728
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In fs/inode.c (ffffffff81347d05)
Location: arch/x86/include/asm/processor.h:728
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff8137852a)
Location: arch/x86/include/asm/processor.h:728
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/ext4/readpage.c (ffffffff81432fb0)
Location: arch/x86/include/asm/processor.h:728
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff819d0095)
Location: arch/x86/include/asm/processor.h:728
Inline: True
Inline callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/selftests.c (ffffffff81a36153)
Location: arch/x86/include/asm/processor.h:728
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/tcp.c (ffffffff81aa236c)
Location: arch/x86/include/asm/processor.h:728
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
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
In arch/x86/mm/fault.c (ffffffff81d48e75)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff8112e47f)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/bpf/cpumap.c (ffffffff8126dec8)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/vmscan.c (ffffffff812b510f)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff8130336d)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In fs/inode.c (ffffffff81395915)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff813c4e0a)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/ext4/readpage.c (ffffffff81486905)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff81a806f5)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/selftests.c (ffffffff81aebde8)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/tcp.c (ffffffff81b5e091)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
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
In arch/x86/mm/fault.c (ffffffff81f181f3)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff8114f690)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/bpf/cpumap.c (ffffffff812bcd14)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/vmscan.c (ffffffff8130d5c6)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff8136b0db)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/slub.c (ffffffff813aa8d2)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
```
```
In fs/inode.c (ffffffff81417e45)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff8144bc5c)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/ext4/readpage.c (ffffffff8150a103)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff81bf4e3a)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/selftests.c (ffffffff81c6e787)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/tcp.c (ffffffff81ceca5b)
Location: arch/x86/include/asm/processor.h:741
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
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
In arch/x86/mm/fault.c (ffffffff820bf9e3)
Location: arch/x86/include/asm/processor.h:618
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff820d6960)
Location: arch/x86/include/asm/processor.h:618
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/bpf/cpumap.c (ffffffff81320174)
Location: arch/x86/include/asm/processor.h:618
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/vmscan.c (ffffffff8137884d)
Location: arch/x86/include/asm/processor.h:618
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/page_alloc.c (ffffffff813e73db)
Location: arch/x86/include/asm/processor.h:618
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/slub.c (ffffffff8142ad9c)
Location: arch/x86/include/asm/processor.h:618
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
```
```
In fs/inode.c (ffffffff814a3615)
Location: arch/x86/include/asm/processor.h:618
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff814da27a)
Location: arch/x86/include/asm/processor.h:618
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/ext4/readpage.c (ffffffff815a4d2b)
Location: arch/x86/include/asm/processor.h:618
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff81da42a4)
Location: arch/x86/include/asm/processor.h:618
Inline: True
Inline callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/selftests.c (ffffffff81e264b7)
Location: arch/x86/include/asm/processor.h:618
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/tcp.c (ffffffff81eb095c)
Location: arch/x86/include/asm/processor.h:618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
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
In arch/x86/mm/fault.c (ffffffff821416e3)
Location: arch/x86/include/asm/processor.h:615
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff82159d64)
Location: arch/x86/include/asm/processor.h:615
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/bpf/cpumap.c (ffffffff8134ffe6)
Location: arch/x86/include/asm/processor.h:615
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/vmscan.c (ffffffff813ace3b)
Location: arch/x86/include/asm/processor.h:615
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/page_alloc.c (ffffffff8141c4f1)
Location: arch/x86/include/asm/processor.h:615
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/slub.c (ffffffff814602d1)
Location: arch/x86/include/asm/processor.h:615
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
```
```
In fs/mpage.c (ffffffff8150e1ba)
Location: arch/x86/include/asm/processor.h:615
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/ext4/readpage.c (ffffffff815db6b4)
Location: arch/x86/include/asm/processor.h:615
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff81e12f14)
Location: arch/x86/include/asm/processor.h:615
Inline: True
Inline callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/selftests.c (ffffffff81e9ba57)
Location: arch/x86/include/asm/processor.h:615
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/tcp.c (ffffffff81f0ee3c)
Location: arch/x86/include/asm/processor.h:615
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
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
In arch/x86/mm/fault.c (ffffffff82223663)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff8223d5e4)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/bpf/cpumap.c (ffffffff8137741f)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/vmscan.c (ffffffff813d6468)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/page_alloc.c (ffffffff81448f91)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/slub.c (ffffffff8145b64f)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:kmalloc_trace
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
```
```
In fs/mpage.c (ffffffff81542c97)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/ext4/readpage.c (ffffffff81613f81)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff81ed00d4)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/selftests.c (ffffffff81f5e1b7)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/tcp.c (ffffffff81fd2ef6)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
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
In kernel/locking/qspinlock.c (ffff80001016ab9c)
Location: arch/arm64/include/asm/processor.h:270
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:queued_spin_lock_slowpath
```
```
In kernel/bpf/cpumap.c (ffff80001028810c)
Location: arch/arm64/include/asm/processor.h:270
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/vmscan.c (ffff8000102c9d50)
Location: arch/arm64/include/asm/processor.h:270
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffff800010316e54)
Location: arch/arm64/include/asm/processor.h:270
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In fs/mpage.c (ffff8000103e6eb0)
Location: arch/arm64/include/asm/processor.h:270
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffff8000104a49e8)
Location: arch/arm64/include/asm/processor.h:270
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffff800010bb9b34)
Location: arch/arm64/include/asm/processor.h:270
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
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
In init/do_mounts.c (c15018a0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/arm/kernel/traps.c (c030f318)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:die
  - arch/arm/kernel/traps.c:die
```
```
In arch/arm/kernel/smp.c (c0312ac4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:secondary_start_kernel
```
```
In arch/arm/kernel/machine_kexec.c (c0315124)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - arch/arm/kernel/machine_kexec.c:machine_crash_nonpanic_core
```
```
In arch/arm/mm/fault-armv.c (c1507e94)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - arch/arm/mm/fault-armv.c:check_writebuffer_bugs
```
```
In arch/arm/mm/pgd.c (c031f9c8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - arch/arm/mm/pgd.c:pgd_free
```
```
In arch/arm/mm/context.c (c0322304)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
  - arch/arm/mm/context.c:check_and_switch_context
  - arch/arm/mm/context.c:check_and_switch_context
  - arch/arm/mm/context.c:check_and_switch_context
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In arch/arm/mm/cache-l2x0-pmu.c (c0324970)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_configure
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_read
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_read
```
```
In arch/arm/common/mcpm_entry.c (c0326100)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_powered_up
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_suspend
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_up
```
```
In arch/arm/mach-imx/mmdc.c (c0333758)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_add
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_start
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_update
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_update
```
```
In kernel/fork.c (c0353fb0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:walk_process_tree
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_mm_exe_file
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mmdrop_async
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/panic.c (c03549d8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/cpu.c (c03583c0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In kernel/exit.c (c0359ab4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (c035e26c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/resource.c:iomem_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_stop
```
```
In kernel/sysctl.c (c035fa5c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_cad_pid
```
```
In kernel/ptrace.c (c0362454)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (c036965c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:__sigqueue_alloc
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (c036af84)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/sys.c:__se_sys_umask
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
```
```
In kernel/umh.c (c036f360)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
  - kernel/umh.c:call_usermodehelper_exec
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (c0370850)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
```
```
In kernel/task_work.c (c0377e0c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
  - kernel/task_work.c:task_work_cancel
  - kernel/task_work.c:task_work_add
```
```
In kernel/kthread.c (c037ad64)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_associate_blkcg
  - kernel/kthread.c:kthread_associate_blkcg
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/nsproxy.c (c037bc4c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
```
In kernel/cred.c (c037d54c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/async.c (c037e600)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/async.c:async_schedule_node_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/smpboot.c (c037f7e8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/ucount.c (c037fd10)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/kmod.c (c0380004)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/groups.c (c0380790)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (c038daf0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wake_q_add_safe
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/loadavg.c (c038eb70)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/clock.c (c151f124)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init
```
```
In kernel/sched/cputime.c (c038eef4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (c0393b1c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (c039ef5c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c039fc6c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/cpupri.c (c03a6d28)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/topology.c (c03a96a8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:sched_get_rd
  - kernel/sched/topology.c:rq_attach_root
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/sched/stop_task.c (c03a9ecc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/autogroup.c (c03ab9ac)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/sched/membarrier.c (c03b2864)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
```
```
In kernel/sched/psi.c (c03b3524)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
```
```
In kernel/locking/mutex.c (c0e9c018)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/mutex.c:__mutex_add_waiter
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/locking/rwsem.c (c03b5604)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/spinlock.c (c0e9f3e4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:_raw_read_lock
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/osq_lock.c (c03b67c4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rtmutex.c (c0e9d6e0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
```
In kernel/power/process.c (c03baa10)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (c03bcf30)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/swap.c (c03c0c98)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/power/user.c (c03c34c0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
```
In kernel/printk/printk_safe.c (c03c89f8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/irq/handle.c (c03c9e14)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In kernel/irq/manage.c (c03cb18c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/irq/spurious.c (c03cdb38)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/chip.c (c03d0180)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/irq/irqdomain.c (c03d3180)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/update.c (c03d7914)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
  - kernel/rcu/update.c:rcu_expedite_gp
```
```
In kernel/rcu/srcutree.c (c03d8c78)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (c03daf08)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_eqs_special_set
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
  - kernel/rcu/tree.c:rcu_dynticks_eqs_enter
```
```
In kernel/kcmp.c (c03e2e1c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/profile.c (c03e386c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/time/posix-cpu-timers.c (c03f8848)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex.c (c0403cfc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:__unqueue_futex
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/smp.c (c04058bc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/uid16.c (c04064e8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/uid16.c:__se_sys_setgroups16
```
```
In kernel/module.c (c040c0e4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:try_module_get
  - kernel/module.c:__se_sys_delete_module
  - kernel/module.c:__se_sys_delete_module
```
```
In kernel/acct.c (c040f2a0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/kexec_core.c (c04109fc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/kexec.c (c04110b4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/cgroup/cgroup.c (c041bcf4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:online_css
  - kernel/cgroup/cgroup.c:online_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/namespace.c (c041cc38)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (c041ecec)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c04202b4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
  - kernel/cgroup/legacy_freezer.c:freezer_css_online
```
```
In kernel/cgroup/pids.c (c042044c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/cgroup/rdma.c (c042152c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (c04258fc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/utsname.c (c0425aa4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (c0426080)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_get
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (c0427a78)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (c0428708)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_signal_done
```
```
In kernel/audit.c (c042bff4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/audit_tree.c (c043578c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/debug/debug_core.c (c0439b0c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (c043cdf8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (c043f68c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/hung_task.c (c0445b50)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/relay.c (c0449cbc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/tracepoint.c (c044d91c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
```
In kernel/trace/trace_clock.c (c044daf8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (c044f598)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/ring_buffer.c (c045ab74)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_reader
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
  - kernel/trace/ring_buffer.c:ring_buffer_record_disable
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_start_commit
  - kernel/trace/ring_buffer.c:rb_start_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_list
  - kernel/trace/ring_buffer.c:rb_check_list
  - kernel/trace/ring_buffer.c:rb_set_head_page
  - kernel/trace/ring_buffer.c:rb_set_head_page
  - kernel/trace/ring_buffer.c:rb_set_head_page
```
```
In kernel/trace/trace.c (c04664bc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_functions.c (c046b6d8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (c046c71c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_stack.c (c046e43c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_functions_graph.c (c046f164)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (c0472498)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_remove
```
```
In kernel/trace/fgraph.c (c047435c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
  - kernel/trace/fgraph.c:function_graph_enter
```
```
In kernel/trace/trace_events.c (c0475a24)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (c047dac4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In kernel/trace/trace_kdb.c (c0488260)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_uprobe.c (c048b7ac)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/irq_work.c (c048e1b0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_claim
```
```
In kernel/bpf/core.c (c0491fb8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (c04939bc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_uncharge_memlock
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_put_uref
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_charge_memlock
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/bpf/helpers.c (c04a8fdc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/hashtab.c (c04aa450)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (c04ad350)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
  - kernel/bpf/arraymap.c:fd_array_map_delete_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_update_elem
```
```
In kernel/bpf/local_storage.c (c04b0244)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/devmap.c (c04b72a0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
```
```
In kernel/bpf/cpumap.c (c04b7e40)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_replace
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/xskmap.c (c04b8e14)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
```
```
In kernel/bpf/offload.c (c04b98f4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/stackmap.c (c04bb0bc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/bpf/cgroup.c (c04bf5e0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (c04ce320)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:task_clock_event_start
  - kernel/events/core.c:task_clock_event_update
  - kernel/events/core.c:task_clock_event_update
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_swevent_set_period
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_fault
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:perf_poll
  - kernel/events/core.c:put_event
  - kernel/events/core.c:free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:exclusive_event_destroy
  - kernel/events/core.c:exclusive_event_destroy
  - kernel/events/core.c:perf_sched_delayed
  - kernel/events/core.c:perf_adjust_period
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:_perf_event_refresh
```
```
In kernel/events/ring_buffer.c (c04d22cc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In kernel/events/callchain.c (c04d2df0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (c04d74d0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:xol_free_insn_slot
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (c04d8668)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/filemap.c (c04de13c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:unlock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/oom_kill.c (c04e4870)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:exit_oom_victim
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (c04e6d28)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:wb_update_write_bandwidth
```
```
In mm/readahead.c (c04eaee8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (c04ecadc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (c04ee8cc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (c04f67b0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (c04fdb48)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (c0502610)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:fold_diff
  - mm/vmstat.c:fold_diff
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
```
```
In mm/backing-dev.c (c0503100)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/mmu_context.c (c05048a8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/slab_common.c (c050b98c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/workingset.c (c0513b8c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/prfile.c (c0513c30)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/gup.c (c0515674)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (c051c09c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
  - mm/memory.c:sync_mm_rss
```
```
In mm/mincore.c (c051c414)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (c051d378)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (c051e1dc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (c052312c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (c05231fc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/msync.c (c0524b90)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/msync.c:__se_sys_msync
```
```
In mm/rmap.c (c0526bd8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/vmalloc.c (c052a76c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In mm/process_vm_access.c (c052d280)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In mm/page_alloc.c (c05345a4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/page_alloc.c:free_highmem_page
  - mm/page_alloc.c:free_highmem_page
  - mm/page_alloc.c:free_highmem_page
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/memblock.c (c1532db4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (c05385e0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/page_io.c (c05393c4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (c053aa58)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (c053ef08)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/frontswap.c (c054106c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
  - mm/frontswap.c:__frontswap_store
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/zswap.c (c05426a0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/mmu_notifier.c (c0543890)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (c0545ec8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/slub.c (c054d558)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__slab_free
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:discard_slab
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (c0552898)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/page_counter.c (c055343c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (c0555c30)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:drain_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/cleancache.c (c055e4e0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/cleancache.c:cleancache_register_ops
```
```
In mm/zpool.c (c055f1fc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
  - mm/zpool.c:zpool_get_driver
```
```
In mm/zsmalloc.c (c0561728)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:__free_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/balloon_compaction.c (c0563494)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/userfaultfd.c (c056398c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (c0564a18)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (c0564f98)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/hmm.c (c0565c90)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/memfd.c (c0566eb4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (c056768c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (c056b53c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:vfs_dedupe_get_page
```
```
In fs/file_table.c (c056e828)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/file_table.c:delayed_fput
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_file
  - fs/file_table.c:__alloc_file
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (c056f540)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/super.c:freeze_super
  - fs/super.c:super_setup_bdi
  - fs/super.c:grab_super
  - fs/super.c:deactivate_locked_super
  - fs/super.c:alloc_super
```
```
In fs/exec.c (c0576238)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/exec.c:set_dumpable
  - fs/exec.c:__do_execve_file
  - fs/exec.c:free_bprm
  - fs/exec.c:would_dump
  - fs/exec.c:would_dump
  - fs/exec.c:de_thread
  - fs/exec.c:kernel_read_file
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
  - fs/exec.c:copy_strings
  - fs/exec.c:copy_strings
  - fs/exec.c:acct_arg_size
  - fs/exec.c:__se_sys_uselib
  - fs/exec.c:__se_sys_uselib
```
```
In fs/pipe.c (c0578168)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:generic_pipe_buf_get
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (c057a274)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
  - fs/namei.c:do_last
  - fs/namei.c:do_last
```
```
In fs/fcntl.c (c05828a8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
```
```
In fs/select.c (c0584b6c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/dcache.c (c058a20c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/dcache.c:take_dentry_name_snapshot
```
```
In fs/inode.c (c058dbe0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/inode.c:inode_set_flags
  - fs/inode.c:generic_update_time
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:new_inode
  - fs/inode.c:get_next_ino
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (c0591cc0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__fget
  - fs/file.c:__close_fd_get_file
  - fs/file.c:get_files_struct
  - fs/file.c:dup_fd
```
```
In fs/filesystems.c (c0591f78)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:__se_sys_sysfs
  - fs/filesystems.c:__se_sys_sysfs
  - fs/filesystems.c:__se_sys_sysfs
```
```
In fs/namespace.c (c0598b40)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:delayed_mntput
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:mnt_init
```
```
In fs/libfs.c (c059df7c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (c05a70dc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/splice.c (c05a9bd0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_release
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/fs_struct.c (c05ad54c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/nsfs.c (c05ae5ac)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/fs_context.c (c05af010)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/buffer.c (c05b522c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
  - fs/buffer.c:unlock_buffer
```
```
In fs/block_dev.c (c05b99dc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (c05bcf20)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (c05bebc8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:mpage_readpages
```
```
In fs/proc_namespace.c (c05bf578)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/notification.c (c05c0064)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/notify/group.c (c05c0680)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/mark.c (c05c1968)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fanotify/fanotify.c (c05c3b58)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/notify/fanotify/fanotify_user.c (c05c572c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
```
```
In fs/eventpoll.c (c05c751c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (c05cdcd0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (c05cfc58)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:__get_reqs_available
  - fs/aio.c:put_reqs_available
  - fs/aio.c:exit_aio
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (c05d7b30)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_mem_free
  - fs/io_uring.c:io_account_mem
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
```
```
In fs/crypto/hooks.c (c05d9a1c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/crypto/keysetup.c (c05dbc90)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:derive_essiv_salt
```
```
In fs/verity/enable.c (c05de118)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/hash_algs.c (c05de294)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/verity/open.c (c05df254)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In fs/verity/verify.c (c05df6f4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/locks.c (c05e27c8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/locks.c:locks_get_lock_context
```
```
In fs/binfmt_script.c (c05e5fc8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/binfmt_script.c:load_script
```
```
In fs/binfmt_elf.c (c05e91f8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/binfmt_elf_fdpic.c (c05ea328)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
  - fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary
  - fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary
```
```
In fs/binfmt_flat.c (c05ed4fc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/binfmt_flat.c:load_flat_shared_library
```
```
In fs/mbcache.c (c05edcc0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (c05ef260)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/posix_acl.c:__forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/coredump.c (c05f1334)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (c05f31e4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (c05f6344)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/iomap/seek.c (c05f6d20)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/quota/dquot.c (c05fa2c0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/quota/netlink.c (c05ff190)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/task_mmu.c (c0600e4c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:smaps_pte_entry
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (c0601ce4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_entry_rundown
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/root.c (c0602974)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (c0603e30)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_release
  - fs/proc/base.c:mem_rw
  - fs/proc/base.c:proc_mem_open
```
```
In fs/proc/generic.c (c06086fc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/array.c (c060a008)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (c060bfb4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/proc_sysctl.c (c060f900)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_poll_notify
```
```
In fs/kernfs/dir.c (c0616810)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_activate
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - fs/kernfs/dir.c:kernfs_get
```
```
In fs/kernfs/file.c (c0616ce8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_put_open_node
```
```
In fs/sysfs/mount.c (c06197f0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/inode.c (c061aa38)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (c061c39c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/configfs/dir.c:detach_attrs
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_make_dirent
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/configfs/dir.c:put_fragment
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (c061e538)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/devpts/inode.c (c061f610)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
  - fs/devpts/inode.c:devpts_new_index
  - fs/devpts/inode.c:devpts_acquire
```
```
In fs/ext4/balloc.c (c0621870)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (c0623400)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (c0624fd8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (c063198c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/ialloc.c (c0637efc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (c06385f0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (c063d410)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (c064ba14)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_end_io_dio
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:ext4_update_bh_state
```
```
In fs/ext4/ioctl.c (c064ca54)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (c0659484)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_unload_buddy
  - fs/ext4/mballoc.c:ext4_mb_unload_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/migrate.c (c065a29c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (c065b018)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (c065c130)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (c06627f4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/page-io.c (c0665ee8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (c06665b4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/resize.c (c066a210)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_end
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (c067d8a8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/ext4/symlink.c (c0684bd4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In fs/ext4/sysfs.c (c0684d68)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (c0688b20)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/verity.c (c068bd94)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (c06904ac)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:sub_reserved_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/commit.c (c0690df4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (c0693490)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/checkpoint.c (c0693f40)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (c069accc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/block.c (c069b47c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/file.c (c069d3bc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (c069fd74)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/lz4_wrapper.c (c06a0c8c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (c06a0f10)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (c06a1210)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (c06a1578)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (c06a1874)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/fat/dir.c (c06a40a4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/fatent.c (c06a62d8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/fat/inode.c (c06ab474)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (c06ac9b8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In fs/fat/namei_vfat.c (c06af4a8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/ecryptfs/main.c (c06b2a38)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/mmap.c (c06b3be8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/ecryptfs/read_write.c (c06b409c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/miscdev.c (c06baee0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_open
```
```
In fs/fuse/dev.c (c06be638)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/dir.c (c06c4a34)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_invalidate_attr_mask
```
```
In fs/fuse/file.c (c06c6858)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_release_user_pages
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (c06cc0a8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In fs/fuse/readdir.c (c06d0204)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
```
```
In fs/debugfs/file.c (c06d2dd8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (c06d9888)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (c06dbb90)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/shm.c (c06e1bdc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:ksys_shmctl
```
```
In ipc/mqueue.c (c06e4404)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (c06e5614)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/gc.c (c06e59b0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In security/keys/key.c (c06e6a04)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/key.c:key_alloc
```
```
In security/keys/keyring.c (c06e8e18)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/keyctl.c (c06eb398)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/process_keys.c (c06ec8cc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (c06ed184)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (c06edb58)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/selinux/avc.c (c06fc68c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (c06fe040)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
  - security/selinux/hooks.c:selinux_secmark_refcount_inc
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/selinuxfs.c (c070b150)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/selinux/ss/services.c (c071cac4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_read_policy
  - security/selinux/ss/services.c:security_read_policy
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/selinux/xfrm.c (c071f51c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
```
In security/tomoyo/common.c (c072fe38)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
  - security/tomoyo/common.c:tomoyo_open_control
  - security/tomoyo/common.c:tomoyo_update_stat
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (c0730a6c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (c073279c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_update_domain
```
```
In security/tomoyo/environ.c (c07331e8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (c073466c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_put_name_union
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (c0734ddc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
  - security/tomoyo/gc.c:tomoyo_del_acl
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (c0735814)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (c0735ce8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (c07370f4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (c0738118)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (c1543df8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_alloc
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In security/apparmor/domain.c (c0745c2c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/policy.c (c0747cec)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (c0749bd4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In security/apparmor/lsm.c (c074e3e4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In security/integrity/iint.c (c075c134)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In security/integrity/ima/ima_queue.c (c075d3e4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (c07600d4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (c0768cac)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
```
```
In block/bio.c (c07883f0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
  - block/bio.c:__bio_associate_blkg
  - block/bio.c:bio_endio
  - block/bio.c:update_io_ticks
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-core.c (c0791658)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_set_pm_only
```
```
In block/blk-flush.c (c0793c38)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (c0795360)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-map.c (c0795b28)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In block/blk-merge.c (c079809c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In block/blk-mq.c (c079c65c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (c07a0610)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-mq-sched.c (c07a2950)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/genhd.c (c07a5d44)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_inc_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/partition-generic.c (c07a790c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (c07aa7e8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (c07ab3c8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (c07ab7f0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (c07ac4b4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (c07ae6bc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (c07afc28)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (c07b0400)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (c07b05e0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (c07b08ec)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (c07b0b44)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (c07b0e2c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (c07b1f94)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (c07b235c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In block/blk-rq-qos.c (c07b2494)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-cgroup.c (c07b93c4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (c07bc4a4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (c07c142c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:ioc_refresh_params
```
```
In block/blk-wbt.c (c07c8850)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/lockref.c (c07d092c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - lib/lockref.c:lockref_get_not_dead
  - lib/lockref.c:lockref_put_or_lock
  - lib/lockref.c:lockref_put_return
  - lib/lockref.c:lockref_get_or_lock
  - lib/lockref.c:lockref_put_not_zero
  - lib/lockref.c:lockref_get_not_zero
  - lib/lockref.c:lockref_get
```
```
In lib/debug_locks.c (c07d1298)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In lib/iov_iter.c (c07d4f10)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In lib/llist.c (c07d9c7c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - lib/llist.c:llist_del_first
  - lib/llist.c:llist_add_batch
```
```
In lib/percpu-refcount.c (c07db520)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/rhashtable.c (c07dc88c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_alloc
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/refcount.c (c07dd42c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/errseq.c (c07ddb00)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - lib/errseq.c:errseq_check_and_advance
  - lib/errseq.c:errseq_set
```
```
In lib/generic-radix-tree.c (c07dde68)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
```
```
In lib/crc-t10dif.c (c1548fdc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_init
```
```
In lib/genalloc.c (c07eac40)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:clear_bits_ll
  - lib/genalloc.c:set_bits_ll
```
```
In lib/irq_poll.c (c0810220)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - lib/irq_poll.c:__irq_poll_complete
```
```
In lib/sbitmap.c (c0811e14)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:__sbitmap_get_word
  - lib/sbitmap.c:sbitmap_resize
  - lib/sbitmap.c:sbitmap_resize
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081ef18)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_set_wake
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_set_wake
```
```
In drivers/irqchip/irq-renesas-irqc.c (c081fac0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake
```
```
In drivers/bus/ti-sysc.c (c0829424)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_remove
  - drivers/bus/ti-sysc.c:sysc_probe
```
```
In drivers/phy/phy-core.c (c082b588)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c0852148)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_retention_disable
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_retention_enable
```
```
In drivers/pci/pci.c (c0885738)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_find_domain_nr
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/pci-driver.c (c088786c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/pcie/portdrv_pci.c (c0898ce8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/ats.c (c08a0790)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/rapidio/rio.c (c08c0dd0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/video/fbdev/core/fbmem.c (c08c8004)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/video/fbdev/core/fb_defio.c (c08cec90)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/amba/bus.c (c08e5ec4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/clk/clk.c (c08e8188)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/dma/dmaengine.c (c091e9a0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:chan_dev_release
```
```
In drivers/dma/of-dma.c (c092009c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In drivers/dma/ipu/ipu_idmac.c (c092811c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/virtio/virtio_balloon.c (c0947508)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/regulator/core.c (c094c854)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/reset/core.c (c0958d84)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In drivers/tty/tty_io.c (c095d4c0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/tty/tty_buffer.c (c0965054)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
  - drivers/tty/tty_buffer.c:tty_buffer_flush
  - drivers/tty/tty_buffer.c:tty_buffer_flush
  - drivers/tty/tty_buffer.c:tty_buffer_free
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
  - drivers/tty/tty_buffer.c:tty_buffer_lock_exclusive
```
```
In drivers/tty/tty_ldsem.c (c0966b68)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/tty_jobctrl.c (c0967ad0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/tty_audit.c (c09694d0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
```
```
In drivers/tty/sysrq.c (c0969e2c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/vt/keyboard.c (c1593ee4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/vt/vt.c (c0976dec)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (c097ce88)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (c097f254)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serial/8250/8250_port.c (c0985d34)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098dd5c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove
```
```
In drivers/tty/serial/msm_serial.c (c099b384)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
```
```
In drivers/tty/serial/kgdb_nmi.c (c09a4c38)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (c09a5448)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
```
```
In drivers/tty/serdev/core.c (c09a64c4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/random.c (c09aaa80)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (c09af154)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/io-pgtable-arm.c (c09bfe78)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:arm_lpae_install_table
```
```
In drivers/iommu/omap-iommu.c (c09c4864)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_attach_dev
```
```
In drivers/iommu/exynos-iommu.c (c09ca0e8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_attach_device
  - drivers/iommu/exynos-iommu.c:exynos_iommu_detach_device
```
```
In drivers/connector/cn_queue.c (c09cc710)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/cn_proc.c (c09cd038)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In drivers/base/core.c (c09d5990)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (c09d88ec)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/devtmpfs.c (c09e28a4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In drivers/base/power/runtime.c (c09e8c00)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_forbid
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/power/main.c (c09ed0b0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/wakeup.c (c09eeeb8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
  - drivers/base/power/wakeup.c:pm_system_wakeup
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/power/domain.c (c09f0004)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:genpd_sd_counter_dec
```
```
In drivers/base/devcoredump.c (c0a045f8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (c0a07d58)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:lo_rw_aio_complete
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/mfd/twl6030-irq.c (c0a26810)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake
  - drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake
```
```
In drivers/mfd/mfd-core.c (c0a29678)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_disable
  - drivers/mfd/mfd-core.c:mfd_cell_disable
  - drivers/mfd/mfd-core.c:mfd_cell_enable
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/dax/super.c (0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (c0a3bbfc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/dma-buf/dma-fence.c (c0a3ce80)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/dma-buf/dma-fence-array.c (c0a3e400)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (c0a3e96c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (c0a42120)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/hosts.c (c0a44c40)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsicam.c (c0a457ec)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/scsi_lib.c (c0a4a2e4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:sdev_disable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/sd.c (c0a5966c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (c0a62790)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/ata/libata-core.c (c0a6f374)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (c0a73fb4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In drivers/spi/spi.c (c0ab3024)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab7f74)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
```
```
In drivers/net/loopback.c (c0ab8488)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (c0ac6b30)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac948c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0ad04b8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad4370)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_remove
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_tx_maxrate
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_vlan_rx_kill_vid
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_vlan_rx_add_vid
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_mac_address
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
```
```
In drivers/net/ethernet/ti/cpsw_ethtool.c (c0adaf20)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_ethtool_op_begin
```
```
In drivers/net/ppp/ppp_generic.c (c0adc1f4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/cdrom/cdrom.c (c0ae848c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In drivers/usb/core/hub.c (c0af1d90)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (c0af3e70)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/urb.c (c0af7094)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_anchor_suspend_wakeups
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
  - drivers/usb/core/urb.c:usb_block_urb
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/driver.c (c0afb7b4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/devio.c (c0b046a4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/usb/core/devices.c (c0b084fc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/usb/core/port.c (c0b094dc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (c0b09a2c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (c0b63378)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/usb/musb/musb_core.c (c0b668bc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_suspend
```
```
In drivers/usb/musb/musb_gadget.c (c0b6f928)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/usb/musb/musb_gadget.c:musb_gadget_queue
```
```
In drivers/input/serio/serio.c (c0b75d40)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (c0b784cc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/rtc/dev.c (c0b89af0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/i2c/i2c-core-base.c (c0b92a58)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg
```
```
In drivers/i2c/busses/i2c-designware-master.c (c0b997fc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b99f10)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9c3a8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_remove
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
```
```
In drivers/power/avs/smartreflex.c (c0ba9400)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/power/avs/smartreflex.c:omap_sr_probe
```
```
In drivers/power/reset/vexpress-poweroff.c (c0bab1b8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
```
```
In drivers/power/supply/power_supply_core.c (c0bac6cc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_phandle
  - drivers/power/supply/power_supply_core.c:power_supply_put
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
```
```
In drivers/thermal/thermal_core.c (c0bb4b20)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In drivers/md/md.c (c15c1158)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_seq_start
  - drivers/md/md.c:md_open
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_new_event
```
```
In drivers/md/md-bitmap.c (c0bdb79c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (c0be09c8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
  - drivers/md/dm.c:event_callback
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
  - drivers/md/dm.c:dm_blk_close
  - drivers/md/dm.c:dm_blk_open
  - drivers/md/dm.c:__dm_get_module_param
  - drivers/md/dm.c:dm_issue_global_event
```
```
In drivers/md/dm-stripe.c (c0be4990)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-io.c (c0be8748)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (c0be8e00)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/md/dm-stats.c (c0bebfd4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_device.c (c0bef104)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (c0bf11bc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (c0bf1ea8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_handle_npe
  - drivers/edac/edac_pci_sysfs.c:edac_pci_handle_pe
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/cpufreq/cpufreq_governor.c (c0bffb48)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/cpufreq/omap-cpufreq.c (c0c00484)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/cpufreq/omap-cpufreq.c:omap_cpu_exit
  - drivers/cpufreq/omap-cpufreq.c:omap_cpu_init
```
```
In drivers/cpuidle/coupled.c (c0c05458)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_coupled_set_done
  - drivers/cpuidle/coupled.c:cpuidle_coupled_set_done
  - drivers/cpuidle/coupled.c:cpuidle_coupled_parallel_barrier
  - drivers/cpuidle/coupled.c:cpuidle_coupled_parallel_barrier
```
```
In drivers/mmc/core/sdio.c (c0c15144)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/mmc/core/sdio_bus.c (c0c15cec)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/mmc/core/block.c (c0c1c548)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/mmc/host/sdhci.c (c0c25c80)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_set_power_noreg
  - drivers/mmc/host/sdhci.c:sdhci_set_power_noreg
  - drivers/mmc/host/sdhci.c:sdhci_reset
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2e3cc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove
```
```
In drivers/leds/led-triggers.c (c0c33bec)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/leds/trigger/ledtrig-cpu.c (c0c344b4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/firmware/arm_scmi/clock.c (c0c38c48)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
```
```
In drivers/firmware/efi/efi.c (c0e9930c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/firmware/efi/arm-runtime.c (c15aa044)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services
```
```
In drivers/clocksource/timer-ti-dm.c (c0c47820)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (c0c62660)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In drivers/remoteproc/remoteproc_core.c (c0c647ec)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (c0c687c4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (c0c6a098)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In drivers/extcon/extcon.c (c0c6dba4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/perf/arm-cci.c (c0c7b528)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_event_init
  - drivers/perf/arm-cci.c:cci_pmu_event_init
  - drivers/perf/arm-cci.c:cci_pmu_start
  - drivers/perf/arm-cci.c:pmu_handle_irq
  - drivers/perf/arm-cci.c:pmu_event_update
  - drivers/perf/arm-cci.c:pmu_event_update
```
```
In drivers/perf/arm-ccn.c (c0c7d16c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_start
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_update
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_update
```
```
In drivers/perf/arm_pmu.c (c0c7df5c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_init
  - drivers/perf/arm_pmu.c:armpmu_event_update
  - drivers/perf/arm_pmu.c:armpmu_event_update
  - drivers/perf/arm_pmu.c:armpmu_event_update
  - drivers/perf/arm_pmu.c:armpmu_event_set_period
  - drivers/perf/arm_pmu.c:armpmu_event_set_period
  - drivers/perf/arm_pmu.c:armpmu_event_set_period
```
```
In drivers/ras/debugfs.c (c0c80534)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
  - drivers/ras/debugfs.c:trace_open
```
```
In sound/core/control.c (c0c85e08)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - sound/core/control.c:snd_ctl_dev_disconnect
  - sound/core/control.c:snd_ctl_get_preferred_subdevice
```
```
In sound/core/pcm_native.c (c0c93230)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_mmap_data
  - sound/core/pcm_native.c:snd_pcm_mmap_data_fault
  - sound/core/pcm_native.c:snd_pcm_mmap_data_close
  - sound/core/pcm_native.c:snd_pcm_mmap_data_open
```
```
In net/socket.c (c0cc5cd8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (c0cc86b8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/skbuff.c (c0cd4984)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:sock_rmem_free
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:sock_zerocopy_put_abort
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:mm_unaccount_pinned_pages
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/datagram.c (c0cd7dd8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (c0cd92dc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/scm.c (c0cda31c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/gen_estimator.c (c0cdb518)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_kill_estimator
```
```
In net/core/net_namespace.c (c0cdbfc8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/sysctl_net_core.c (c0ce10b8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (c0cefb80)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_schedule_prep
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:__dev_forward_skb
  - net/core/dev.c:net_disable_timestamp
  - net/core/dev.c:net_enable_timestamp
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_inc_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
  - net/core/dev.c:net_inc_ingress_queue
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/dst.c (c0cfb268)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/dst.c:__dst_destroy_metrics_generic
  - net/core/dst.c:dst_cow_metrics_generic
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (c0cfd094)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_mark_dead
```
```
In net/core/filter.c (c0d14ddc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_skb_set_tunnel_proto
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/sock_diag.c (c0d1cfe0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/core/xdp.c (c0d20080)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d21730)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/net-sysfs.c (c0d23824)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/core/page_pool.c (c0d251bc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (c0d27b54)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/core/netpoll.c (c0d29484)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/lwtunnel.c (c0d35e38)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/core/lwtunnel.c:lwtunnel_encap_add_ops
```
```
In net/core/sock_map.c (c0d39144)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
  - net/core/sock_map.c:__sock_map_delete
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/dst_cache.c (c0d39420)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/core/gro_cells.c (c0d47a5c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/core/bpf_sk_storage.c (c0d48e2c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:selem_alloc
  - net/core/bpf_sk_storage.c:omem_charge
```
```
In net/sched/sch_generic.c (c0d4aa54)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In net/sched/sch_api.c (c0d4e7e0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (c0d51448)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
  - net/sched/cls_api.c:tcf_block_offload_dec
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (c0d58110)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_set_action_cookie
```
```
In net/sched/ematch.c (c0d5ad08)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In net/netlink/af_netlink.c (c0d5cc4c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/netfilter/nf_log.c (c0d653a4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (c0d657fc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (c0d66770)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/protocol.c (c0d6d274)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/protocol.c:inet_add_offload
  - net/ipv4/protocol.c:inet_add_protocol
```
```
In net/ipv4/ip_input.c (c0d6e1c4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (c0d6e8f8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_options.c (c0d70894)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (c0d73500)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (c0d76374)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (c0d7a9ac)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c0d7b984)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (c0d7e878)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (c0d87f24)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv4/tcp_input.c:clean_acked_data_enable
```
```
In net/ipv4/tcp_output.c (c0d969f0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (c0d99d3c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_minisocks.c (c0d9ea34)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_cong.c (c0d9fe94)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
```
```
In net/ipv4/tcp_fastopen.c (c0da2900)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable
```
```
In net/ipv4/datagram.c (c0da44d8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da55b4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c0daa118)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (c0dae6b0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/icmp.c (c0db18d0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/af_inet.c (c0db8028)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/igmp.c (c0dbe7ec)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv4/fib_frontend.c (c0dc130c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
```
In net/ipv4/fib_semantics.c (c0dc207c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/inet_fragment.c (c0dca30c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ping.c (c0dcd1fc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ip_tunnel_core.c (c0dce034)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata
```
```
In net/ipv4/ipmr.c (c0dd6d38)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_vif_seq_stop
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/ipmr_base.c (c0ddb228)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In net/ipv4/tcp_bpf.c (c0dddd3c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (c0de0168)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
```
```
In net/xfrm/xfrm_policy.c (c0dea2a4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (c0ded014)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (c0df2ea4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c0df4308)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_device.c (c0df64ec)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (c0dfa620)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (c0dfb4f4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
  - net/unix/garbage.c:dec_inflight
```
```
In net/unix/scm.c (c0dfbf74)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
```
In net/ipv6/af_inet6.c (c0dfcea0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/ip6_output.c (c0e03be4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c0e050c0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (c0e08c54)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
```
```
In net/ipv6/route.c (c0e1b3bc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_alloc
```
```
In net/ipv6/ip6_fib.c (c0e21018)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_new_sernum
```
```
In net/ipv6/ipv6_sockglue.c (c0e224b0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (c0e25238)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c0e28840)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_encap_enable
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2e214)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (c0e30a10)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c0e33954)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (c0e37684)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (c0e3c218)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ping.c (c0e3ca78)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (c0e40974)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (c0e4204c)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6_flowlabel.c:fl_free
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (c0e49afc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
```
In net/ipv6/xfrm6_policy.c (c0e49f10)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/fib6_rules.c (c0e4c4f4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (c0e4f9c4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/ipv6/seg6_local.c (c0e51998)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (c0e52f94)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/ipv6/ip6_icmp.c (c0e543d0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/ip6_icmp.c:inet6_register_icmp_sender
```
```
In net/ipv6/protocol.c (c0e54a14)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_add_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/ipv6/protocol.c:inet6_add_protocol
```
```
In net/packet/af_packet.c (c0e58684)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:packet_mm_open
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
```
```
In net/netlabel/netlabel_unlabeled.c (c0e67598)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e683fc)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (c0e69174)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_ops_register
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
```
In net/rfkill/core.c (c0e69ca4)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
```
```
In net/dns_resolver/dns_key.c (c0e6fde0)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In net/xdp/xdp_umem.c (c0e7b960)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_unaccount_pages
```
```
In lib/dec_and_lock.c (c0e7fbe8)
Location: arch/arm/include/asm/processor.h:130
Inline: True
```
```
In lib/dump_stack.c (c0e7fe60)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/nmi_backtrace.c (c0e87560)
Location: arch/arm/include/asm/processor.h:130
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/powerpc/lib/sstep.c (c0000000000b1e68)
Location: arch/powerpc/include/asm/processor.h:385
Inline: True
Inline callers:
  - arch/powerpc/lib/sstep.c:emulate_step
```
```
In kernel/bpf/cpumap.c (c000000000333790)
Location: arch/powerpc/include/asm/processor.h:385
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/vmscan.c (c000000000386544)
Location: arch/powerpc/include/asm/processor.h:385
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (c0000000003e91c0)
Location: arch/powerpc/include/asm/processor.h:385
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In fs/inode.c (c0000000004ab2b0)
Location: arch/powerpc/include/asm/processor.h:385
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (c0000000004ed394)
Location: arch/powerpc/include/asm/processor.h:385
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (c0000000005d1ac8)
Location: arch/powerpc/include/asm/processor.h:385
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (c000000000c92178)
Location: arch/powerpc/include/asm/processor.h:385
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
</details>
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
In arch/x86/mm/fault.c (ffffffff8107ffcf)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff810fe1ae)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/bpf/cpumap.c (ffffffff811f902a)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/vmscan.c (ffffffff8123152d)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff81277951)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In fs/inode.c (ffffffff812f6e85)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff81323ed6)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff813c4b8c)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff818bf161)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
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
In arch/x86/mm/fault.c (ffffffff8106ed4f)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff810ee3ae)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/bpf/cpumap.c (ffffffff811ebd7a)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/vmscan.c (ffffffff812245ed)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff81269861)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In fs/inode.c (ffffffff812e7aa5)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff81314a76)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff813b560c)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff818790a1)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
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
In arch/x86/mm/fault.c (ffffffff8107ff7f)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff810fb36e)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/bpf/cpumap.c (ffffffff811f6dfa)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/vmscan.c (ffffffff8122f2cd)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff812756f1)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In fs/inode.c (ffffffff812f4c95)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff813219a6)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff813c201c)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff81910161)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
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
In arch/x86/mm/fault.c (ffffffff8108207f)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In kernel/locking/qspinlock.c (ffffffff8110653e)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/bpf/cpumap.c (ffffffff812050d7)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/vmscan.c (ffffffff8123e6dd)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/page_alloc.c (ffffffff812852b1)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In fs/inode.c (ffffffff81305e25)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/inode.c:new_inode
```
```
In fs/mpage.c (ffffffff81333706)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff813d719c)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In net/core/skbuff.c (ffffffff819312c1)
Location: arch/x86/include/asm/processor.h:805
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
