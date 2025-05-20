# Function: <code>vma_iter_init</code>

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
In mm/ksm.c (ffffffff81420629)
Location: include/linux/mm_types.h:906
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/khugepaged.c (ffffffff8144c119)
Location: include/linux/mm_types.h:906
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152d2ff)
Location: include/linux/mm_types.h:906
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff81537f1a)
Location: include/linux/mm_types.h:906
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
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
In kernel/sched/fair.c (ffffffff811548a5)
Location: include/linux/mm_types.h:941
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mmap.c (ffffffff813ff43c)
Location: include/linux/mm_types.h:941
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff81404215)
Location: include/linux/mm_types.h:941
Inline: True
Inline callers:
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff81405e5a)
Location: include/linux/mm_types.h:941
Inline: True
Inline callers:
  - mm/mremap.c:move_vma
```
```
In mm/mempolicy.c (ffffffff8144d436)
Location: include/linux/mm_types.h:941
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
```
```
In mm/ksm.c (ffffffff814552c6)
Location: include/linux/mm_types.h:941
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/khugepaged.c (ffffffff81481946)
Location: include/linux/mm_types.h:941
Inline: True
```
```
In fs/exec.c (ffffffff814b8e19)
Location: include/linux/mm_types.h:941
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
```
```
In fs/userfaultfd.c (ffffffff81525b62)
Location: include/linux/mm_types.h:941
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
```
```
In fs/proc/task_mmu.c (ffffffff815653dd)
Location: include/linux/mm_types.h:941
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8157011f)
Location: include/linux/mm_types.h:941
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
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
In kernel/sched/fair.c (ffffffff8116972f)
Location: include/linux/mm_types.h:1083
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/bpf/task_iter.c (ffffffff813498cc)
Location: include/linux/mm_types.h:1083
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_new
```
```
In mm/mmap.c (ffffffff8142b95c)
Location: include/linux/mm_types.h:1083
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff814307e5)
Location: include/linux/mm_types.h:1083
Inline: True
Inline callers:
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff81432559)
Location: include/linux/mm_types.h:1083
Inline: True
Inline callers:
  - mm/mremap.c:move_vma
```
```
In mm/mempolicy.c (ffffffff8148705f)
Location: include/linux/mm_types.h:1083
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
```
```
In mm/ksm.c (ffffffff8148f1dd)
Location: include/linux/mm_types.h:1083
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/khugepaged.c (ffffffff814b0d44)
Location: include/linux/mm_types.h:1083
Inline: True
```
```
In fs/exec.c (ffffffff814eb609)
Location: include/linux/mm_types.h:1083
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
```
```
In fs/userfaultfd.c (ffffffff8155983c)
Location: include/linux/mm_types.h:1083
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
```
```
In fs/proc/task_mmu.c (ffffffff8159c1dd)
Location: include/linux/mm_types.h:1083
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff815a8aaf)
Location: include/linux/mm_types.h:1083
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
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
