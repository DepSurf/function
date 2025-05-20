# Function: <code>raw_atomic_long_add_return</code>

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
In kernel/ucount.c (ffffffff81137c82)
Location: include/linux/atomic/atomic-long.h:139
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:inc_rlimit_ucounts
```
```
In kernel/locking/rwsem.c (ffffffff82154d1f)
Location: include/linux/atomic/atomic-long.h:139
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/dma/swiotlb.c (ffffffff811d72e1)
Location: include/linux/atomic/atomic-long.h:139
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
```
```
In kernel/cgroup/misc.c (ffffffff81235869)
Location: include/linux/atomic/atomic-long.h:139
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/bpf/core.c (ffffffff812e992c)
Location: include/linux/atomic/atomic-long.h:139
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In mm/page-writeback.c (ffffffff813999b1)
Location: include/linux/atomic/atomic-long.h:139
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff813ac7b4)
Location: include/linux/atomic/atomic-long.h:139
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (ffffffff81410e3e)
Location: include/linux/atomic/atomic-long.h:139
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff8148296d)
Location: include/linux/atomic/atomic-long.h:139
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff814be670)
Location: include/linux/atomic/atomic-long.h:139
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
In drivers/tty/tty_ldsem.c (ffffffff81aa1185)
Location: include/linux/atomic/atomic-long.h:139
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
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81142e92)
Location: include/linux/atomic/atomic-long.h:139
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:inc_rlimit_ucounts
```
```
In kernel/locking/rwsem.c (ffffffff82237b5f)
Location: include/linux/atomic/atomic-long.h:139
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/dma/swiotlb.c (ffffffff811ec2a1)
Location: include/linux/atomic/atomic-long.h:139
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_search_pool_area
```
```
In kernel/bpf/core.c (ffffffff81307b7c)
Location: include/linux/atomic/atomic-long.h:139
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In mm/page-writeback.c (ffffffff813c37b1)
Location: include/linux/atomic/atomic-long.h:139
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/shrinker.c (ffffffff813e4062)
Location: include/linux/atomic/atomic-long.h:139
Inline: True
Inline callers:
  - mm/shrinker.c:do_shrink_slab
  - mm/shrinker.c:do_shrink_slab
```
```
In mm/vmalloc.c (ffffffff8143d62e)
Location: include/linux/atomic/atomic-long.h:139
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff814b1ced)
Location: include/linux/atomic/atomic-long.h:139
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff814f0b0c)
Location: include/linux/atomic/atomic-long.h:139
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
In drivers/tty/tty_ldsem.c (ffffffff81af3be5)
Location: include/linux/atomic/atomic-long.h:139
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
