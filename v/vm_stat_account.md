# Function: <code>vm_stat_account</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, long unsigned int flags, struct file *file, long int pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c5990)
Location: mm/mmap.c:1216
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_munmap
  - mm/mmap.c:mmap_region
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:move_vma
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff811c5990-ffffffff811c59d1: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e2748)
Location: mm/mmap.c:2966
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff811e42b0-ffffffff811e42ff: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f2718)
Location: mm/mmap.c:3119
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff811f42b0-ffffffff811f42ff: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fd6ce)
Location: mm/mmap.c:3173
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff811ff230-ffffffff811ff27f: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81215c6e)
Location: mm/mmap.c:3216
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff81217830-ffffffff8121787f: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81236a9d)
Location: mm/mmap.c:3273
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - kernel/fork.c:copy_mm
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff81238b80-ffffffff81238bcd: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8124a34d)
Location: mm/mmap.c:3317
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff8124c540-ffffffff8124c58d: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125c69b)
Location: mm/mmap.c:3323
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff8125e970-ffffffff8125e9bd: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126adfb)
Location: mm/mmap.c:3329
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff8126d180-ffffffff8126d1cd: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129d01b)
Location: mm/mmap.c:3341
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff8129d380-ffffffff8129d3cd: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a841f)
Location: mm/mmap.c:3399
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff812a8780-ffffffff812a87cd: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812abe2f)
Location: mm/mmap.c:3370
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff812adc30-ffffffff812adc7d: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ed52f)
Location: mm/mmap.c:3350
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff812ef3a0-ffffffff812ef3ed: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813508b2)
Location: mm/mmap.c:3343
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff81352810-ffffffff8135288b: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813ca2cf)
Location: mm/mmap.c:3302
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:expand_downwards
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff813cc860-ffffffff813cc8db: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fe83f)
Location: mm/mmap.c:3397
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:expand_downwards
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff81401130-ffffffff814011ab: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8142acc3)
Location: mm/mmap.c:3485
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:expand_downwards
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff8142d770-ffffffff8142d7f2: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff8000103024e8)
Location: mm/mmap.c:3329
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__arm64_sys_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffff800010304110-ffff8000103041b8: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0520be8)
Location: mm/mmap.c:3329
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
c0522934-c05229a8: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003ce9d0)
Location: mm/mmap.c:3329
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
c0000000003d0f70-c0000000003d0fe0: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020f444)
Location: mm/mmap.c:3329
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffe0002109e6-ffffffe000210a66: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126344b)
Location: mm/mmap.c:3329
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff812657d0-ffffffff8126581d: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125586b)
Location: mm/mmap.c:3329
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff81257bf0-ffffffff81257c3d: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812611eb)
Location: mm/mmap.c:3329
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff81263570-ffffffff812635bd: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void vm_stat_account(struct mm_struct *mm, vm_flags_t flags, long int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81270bbb)
Location: mm/mmap.c:3329
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff81272f30-ffffffff81272f7d: vm_stat_account (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long int npages</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param removed. </b>
<code>long int pages</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int flags</code> ➡️ <code>vm_flags_t flags</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
