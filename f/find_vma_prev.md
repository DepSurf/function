# Function: <code>find_vma_prev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c6010)
Location: mm/mmap.c:2078
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/madvise.c:SyS_madvise
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff811c6010-ffffffff811c606b: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e1e50)
Location: mm/mmap.c:1977
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/madvise.c:SyS_madvise
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff811e1e50-ffffffff811e1eab: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f1e40)
Location: mm/mmap.c:2130
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/madvise.c:SyS_madvise
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff811f1e40-ffffffff811f1e9b: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fcbe0)
Location: mm/mmap.c:2152
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/madvise.c:SyS_madvise
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff811fcbe0-ffffffff811fcc2e: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81215170)
Location: mm/mmap.c:2168
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/madvise.c:SyS_madvise
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81215170-ffffffff812151be: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81235fe0)
Location: mm/mmap.c:2228
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81235fe0-ffffffff8123602e: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81249800)
Location: mm/mmap.c:2263
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81249800-ffffffff8124984e: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125bb30)
Location: mm/mmap.c:2264
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - mm/madvise.c:__do_sys_madvise
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff8125bb30-ffffffff8125bb7e: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126a210)
Location: mm/mmap.c:2272
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - mm/madvise.c:__do_sys_madvise
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff8126a210-ffffffff8126a265: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129a7f0)
Location: mm/mmap.c:2271
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff8129a7f0-ffffffff8129a895: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a59c0)
Location: mm/mmap.c:2337
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff812a59c0-ffffffff812a5a65: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ab150)
Location: mm/mmap.c:2341
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff812ab150-ffffffff812ab1e6: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ec820)
Location: mm/mmap.c:2311
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff812ec820-ffffffff812ec8b6: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134f94f)
Location: mm/mmap.c:2339
Inline: True
Inline callers:
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
  - mm/mmap.c:generic_get_unmapped_area
Direct callers:
  - mm/madvise.c:madvise_walk_vmas
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff8134fb00-ffffffff8134fba2: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c8e30)
Location: mm/mmap.c:1853
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
  - mm/madvise.c:madvise_walk_vmas
```
**Symbols:**

```
ffffffff813c8e30-ffffffff813c8ee5: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fd1d0)
Location: mm/mmap.c:1881
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:expand_stack
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
  - mm/madvise.c:madvise_walk_vmas
```
**Symbols:**

```
ffffffff813fd1d0-ffffffff813fd289: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81429bf0)
Location: mm/mmap.c:1913
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:expand_stack
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
  - mm/madvise.c:madvise_walk_vmas
```
**Symbols:**

```
ffffffff81429bf0-ffffffff81429cb0: find_vma_prev (STB_GLOBAL)
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
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010301568)
Location: mm/mmap.c:2272
Inline: True
Direct callers:
  - mm/mmap.c:arch_get_unmapped_area_topdown
  - mm/mmap.c:arch_get_unmapped_area
  - mm/madvise.c:__arm64_sys_madvise
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffff800010301568-ffff8000103015e8: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c05200ec)
Location: mm/mmap.c:2272
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
c05200ec-c0520140: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cdaa0)
Location: mm/mmap.c:2272
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
c0000000003cdaa0-c0000000003cdb4c: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020e938)
Location: mm/mmap.c:2272
Inline: True
Direct callers:
  - mm/mmap.c:arch_get_unmapped_area_topdown
  - mm/mmap.c:arch_get_unmapped_area
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffe00020e938-ffffffe00020e9a0: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81262860)
Location: mm/mmap.c:2272
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - mm/madvise.c:__do_sys_madvise
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff81262860-ffffffff812628b5: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81254c80)
Location: mm/mmap.c:2272
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - mm/madvise.c:__do_sys_madvise
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff81254c80-ffffffff81254cd5: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81260600)
Location: mm/mmap.c:2272
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - mm/madvise.c:__do_sys_madvise
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff81260600-ffffffff81260655: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vm_area_struct *find_vma_prev(struct mm_struct *mm, long unsigned int addr, struct vm_area_struct **pprev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126ffd0)
Location: mm/mmap.c:2272
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - mm/madvise.c:__do_sys_madvise
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff8126ffd0-ffffffff81270025: find_vma_prev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
