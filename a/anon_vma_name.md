# Function: <code>anon_vma_name</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct anon_vma_name *anon_vma_name(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813782e5)
Location: mm/madvise.c:93
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
  - mm/madvise.c:madvise_update_vma
Direct callers:
  - kernel/fork.c:vm_area_dup
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:can_vma_merge_before
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff81378900-ffffffff81378921: anon_vma_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct anon_vma_name *anon_vma_name(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813f5d90)
Location: mm/madvise.c:94
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
  - mm/madvise.c:madvise_update_vma
Direct callers:
  - kernel/fork.c:vm_area_dup
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:can_vma_merge_after
  - mm/mmap.c:can_vma_merge_before
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff813f6220-ffffffff813f6238: anon_vma_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct anon_vma_name *anon_vma_name(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff814289c9)
Location: mm/madvise.c:94
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
  - mm/madvise.c:madvise_update_vma
Direct callers:
  - kernel/fork.c:vm_area_dup
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:can_vma_merge_after
  - mm/mmap.c:can_vma_merge_before
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff81429010-ffffffff81429028: anon_vma_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct anon_vma_name *anon_vma_name(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff814621f9)
Location: mm/madvise.c:94
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
  - mm/madvise.c:madvise_update_vma
Direct callers:
  - kernel/fork.c:vm_area_dup
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_merge_extend
  - mm/mmap.c:can_vma_merge_after
  - mm/mmap.c:can_vma_merge_before
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff81462840-ffffffff81462858: anon_vma_name (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
