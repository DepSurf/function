# Function: <code>vm_flags_init</code>

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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83685131)
Location: include/linux/mm.h:776
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810d2f14)
Location: include/linux/mm.h:776
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:untrack_pfn
```
```
In mm/mlock.c (ffffffff813f7309)
Location: include/linux/mm.h:776
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff813fe802)
Location: include/linux/mm.h:776
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (ffffffff81403ec8)
Location: include/linux/mm.h:776
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/madvise.c (ffffffff81428704)
Location: include/linux/mm.h:776
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
```
```
In fs/exec.c (ffffffff814b952f)
Location: include/linux/mm.h:776
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
```
```
In fs/userfaultfd.c (ffffffff81523a0c)
Location: include/linux/mm.h:776
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_set_vm_flags
```
```
In fs/proc/vmcore.c (ffffffff8157e461)
Location: include/linux/mm.h:776
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/hugetlbfs/inode.c (ffffffff8162f50d)
Location: include/linux/mm.h:776
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b42d1)
Location: include/linux/mm.h:813
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810db6a4)
Location: include/linux/mm.h:813
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:untrack_pfn
```
```
In mm/mlock.c (ffffffff814227dc)
Location: include/linux/mm.h:813
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff8142ac82)
Location: include/linux/mm.h:813
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (ffffffff814303de)
Location: include/linux/mm.h:813
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/madvise.c (ffffffff81461f86)
Location: include/linux/mm.h:813
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
```
```
In fs/exec.c (ffffffff814ec035)
Location: include/linux/mm.h:813
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
```
```
In fs/userfaultfd.c (ffffffff81559c12)
Location: include/linux/mm.h:813
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:mremap_userfaultfd_prep
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/proc/vmcore.c (ffffffff815b6ea1)
Location: include/linux/mm.h:813
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/hugetlbfs/inode.c (ffffffff81668a1d)
Location: include/linux/mm.h:813
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
