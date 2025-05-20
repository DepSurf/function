# Function: <code>mas_set_range</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81144258)
Location: include/linux/maple_tree.h:537
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mmap.c (ffffffff813ccbe1)
Location: include/linux/maple_tree.h:537
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_mas_store
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff813cf8e3)
Location: include/linux/maple_tree.h:537
Inline: True
Inline callers:
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mempolicy.c (ffffffff81419966)
Location: include/linux/maple_tree.h:537
Inline: True
Inline callers:
  - mm/mempolicy.c:mbind_range
```
```
In fs/userfaultfd.c (ffffffff814eec2e)
Location: include/linux/maple_tree.h:537
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
```
In lib/maple_tree.c (ffffffff8202d98b)
Location: include/linux/maple_tree.h:537
Inline: True
Inline callers:
  - lib/maple_tree.c:mas_prev_entry
  - lib/maple_tree.c:mas_prev_entry
  - lib/maple_tree.c:mas_next_entry
  - lib/maple_tree.c:mas_next_entry
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
In kernel/sched/fair.c (ffffffff81154cea)
Location: include/linux/maple_tree.h:546
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mmap.c (ffffffff814014d0)
Location: include/linux/maple_tree.h:546
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:vma_shrink
  - mm/mmap.c:vma_shrink
  - mm/mmap.c:vma_expand
```
```
In fs/userfaultfd.c (ffffffff81525cdb)
Location: include/linux/maple_tree.h:546
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
```
```
In drivers/base/regmap/regcache-maple.c (ffffffff81b7262d)
Location: include/linux/maple_tree.h:546
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-maple.c:regcache_maple_insert_block
  - drivers/base/regmap/regcache-maple.c:regcache_maple_drop
  - drivers/base/regmap/regcache-maple.c:regcache_maple_drop
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
```
```
In lib/maple_tree.c (ffffffff820abf46)
Location: include/linux/maple_tree.h:546
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
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fb395)
Location: include/linux/maple_tree.h:729
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/fair.c (ffffffff81169e1b)
Location: include/linux/maple_tree.h:729
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mmap.c (ffffffff8142db0f)
Location: include/linux/maple_tree.h:729
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:unmap_region
  - mm/mmap.c:vma_merge
```
```
In fs/userfaultfd.c (ffffffff81559a84)
Location: include/linux/maple_tree.h:729
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
```
```
In drivers/base/regmap/regcache-maple.c (ffffffff81bc5e07)
Location: include/linux/maple_tree.h:729
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-maple.c:regcache_maple_insert_block
  - drivers/base/regmap/regcache-maple.c:regcache_maple_drop
  - drivers/base/regmap/regcache-maple.c:regcache_maple_drop
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
```
```
In lib/maple_tree.c (ffffffff8218d0ed)
Location: include/linux/maple_tree.h:729
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
