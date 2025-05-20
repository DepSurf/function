# Function: <code>mas_prev</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *mas_prev(struct ma_state *mas, long unsigned int min);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8202e149)
Location: lib/maple_tree.c:5910
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_prev
Direct callers:
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff8202df80-ffffffff8202e02d: mas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *mas_prev(struct ma_state *mas, long unsigned int min);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820ad020)
Location: lib/maple_tree.c:5826
Inline: True
Direct callers:
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:vm_unmapped_area
  - mm/mmap.c:vm_unmapped_area
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:move_vma
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - fs/exec.c:shift_arg_pages
  - fs/userfaultfd.c:userfaultfd_register
  - lib/maple_tree.c:mt_prev
```
**Symbols:**

```
ffffffff820ad020-ffffffff820ad112: mas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *mas_prev(struct ma_state *mas, long unsigned int min);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8218cf10)
Location: lib/maple_tree.c:5835
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_prev
  - lib/maple_tree.c:mt_prev
Direct callers:
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:vm_unmapped_area
  - mm/mmap.c:vm_unmapped_area
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:move_vma
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - fs/exec.c:shift_arg_pages
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff8218cc90-ffffffff8218ccff: mas_prev (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
