# Function: <code>__mas_set_range</code>

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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fb29e)
Location: include/linux/maple_tree.h:708
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/fair.c (ffffffff81169e1b)
Location: include/linux/maple_tree.h:708
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mmap.c (ffffffff8142db1e)
Location: include/linux/maple_tree.h:708
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:__split_vma
  - mm/mmap.c:unmap_region
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_shrink
  - mm/mmap.c:vma_shrink
  - mm/mmap.c:vma_expand
  - mm/mmap.c:vma_expand
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
```
```
In fs/userfaultfd.c (ffffffff81559a97)
Location: include/linux/maple_tree.h:708
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
```
```
In drivers/base/regmap/regcache-maple.c (ffffffff81bc5e1a)
Location: include/linux/maple_tree.h:708
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-maple.c:regcache_maple_insert_block
  - drivers/base/regmap/regcache-maple.c:regcache_maple_drop
  - drivers/base/regmap/regcache-maple.c:regcache_maple_drop
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
```
```
In lib/maple_tree.c (ffffffff8218d0fc)
Location: include/linux/maple_tree.h:708
Inline: True
Inline callers:
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
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
