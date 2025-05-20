# Function: <code>arch_atomic_long_add_return</code>

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
In kernel/ucount.c (ffffffff810ea413)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
  - kernel/ucount.c:inc_rlimit_ucounts
```
```
In kernel/locking/rwsem.c (ffffffff81d53fdc)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/cgroup/misc.c (ffffffff811a8e65)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8122bb6c)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In mm/page-writeback.c (ffffffff812a4f26)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff812b096d)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/memory.c (ffffffff812e28a4)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/vmalloc.c (ffffffff812fbbbd)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/madvise.c (ffffffff8130ebbe)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff81345316)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134fc43)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff813506ca)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/exec.c (ffffffff8137a55e)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
```
In fs/pipe.c (ffffffff8137f7d8)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In drivers/tty/tty_ldsem.c (ffffffff817c0bb5)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In net/core/sock.c (ffffffff81a79113)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81b75256)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In kernel/ucount.c (ffffffff811050e2)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:inc_rlimit_ucounts
```
```
In kernel/locking/rwsem.c (ffffffff81f2506f)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/cgroup/misc.c (ffffffff811da181)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/bpf/core.c (ffffffff8126d68c)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In mm/page-writeback.c (ffffffff812fcef1)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8130c1e9)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/memory.c (ffffffff81343088)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/vmalloc.c (ffffffff81360beb)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/madvise.c (ffffffff81376a46)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff813bb1b5)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c330c)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
```
```
In mm/page_counter.c (ffffffff813c89ba)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/exec.c (ffffffff813fa2ae)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
```
In fs/pipe.c (ffffffff813ff942)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In drivers/tty/tty_ldsem.c (ffffffff818fd4a5)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In net/core/sock.c (ffffffff81bed573)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81d04a69)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In kernel/ucount.c (ffffffff8112ab32)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:inc_rlimit_ucounts
```
```
In kernel/locking/rwsem.c (ffffffff820d098f)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/cgroup/misc.c (ffffffff8121f701)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/bpf/core.c (ffffffff812c2a3c)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In mm/page-writeback.c (ffffffff81367331)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff813784b9)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (ffffffff813dc551)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff8144d0ad)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff81489742)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In drivers/tty/tty_ldsem.c (ffffffff81a56ba5)
Location: include/linux/atomic/atomic-long.h:57
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
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
