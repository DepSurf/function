# Function: <code>vma_prev</code>

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
In mm/mlock.c (ffffffff813f743d)
Location: include/linux/mm.h:894
Inline: True
Inline callers:
  - mm/mlock.c:apply_vma_lock_flags
```
```
In mm/mmap.c (ffffffff813ff23c)
Location: include/linux/mm.h:894
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:vma_merge
```
```
In mm/mprotect.c (ffffffff814042cc)
Location: include/linux/mm.h:894
Inline: True
Inline callers:
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff81405fb4)
Location: include/linux/mm.h:894
Inline: True
Inline callers:
  - mm/mremap.c:move_vma
```
```
In mm/mempolicy.c (ffffffff8144cef2)
Location: include/linux/mm.h:894
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
```
```
In fs/exec.c (ffffffff814b812a)
Location: include/linux/mm.h:894
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
```
```
In fs/userfaultfd.c (ffffffff81525cf2)
Location: include/linux/mm.h:894
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
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
In mm/mlock.c (ffffffff814228bc)
Location: include/linux/mm.h:971
Inline: True
Inline callers:
  - mm/mlock.c:apply_vma_lock_flags
```
```
In mm/mmap.c (ffffffff8142b77e)
Location: include/linux/mm.h:971
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_merge
```
```
In mm/mprotect.c (ffffffff814308a6)
Location: include/linux/mm.h:971
Inline: True
Inline callers:
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff814325ed)
Location: include/linux/mm.h:971
Inline: True
Inline callers:
  - mm/mremap.c:move_vma
```
```
In mm/mempolicy.c (ffffffff814867e1)
Location: include/linux/mm.h:971
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
```
```
In fs/exec.c (ffffffff814ea63a)
Location: include/linux/mm.h:971
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
```
```
In fs/userfaultfd.c (ffffffff81559a97)
Location: include/linux/mm.h:971
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
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
