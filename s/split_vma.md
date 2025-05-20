# Function: <code>split_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c6420)
Location: mm/mmap.c:2518
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff811c6420-ffffffff811c644c: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e1eb0)
Location: mm/mmap.c:2415
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff811e1eb0-ffffffff811e1edc: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f1ea0)
Location: mm/mmap.c:2568
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff811f1ea0-ffffffff811f1ecc: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fce20)
Location: mm/mmap.c:2603
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff811fce20-ffffffff811fce41: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812153c0)
Location: mm/mmap.c:2621
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff812153c0-ffffffff812153e1: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812361f0)
Location: mm/mmap.c:2676
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff812361f0-ffffffff81236211: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81249a10)
Location: mm/mmap.c:2710
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81249a10-ffffffff81249a31: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125bd30)
Location: mm/mmap.c:2715
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff8125bd30-ffffffff8125bd51: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126a420)
Location: mm/mmap.c:2720
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff8126a420-ffffffff8126a441: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129ae70)
Location: mm/mmap.c:2729
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff8129ae70-ffffffff8129ae91: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a6030)
Location: mm/mmap.c:2792
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff812a6030-ffffffff812a6051: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ab390)
Location: mm/mmap.c:2796
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff812ab390-ffffffff812ab3b1: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812eca70)
Location: mm/mmap.c:2766
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff812eca70-ffffffff812eca91: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134fd70)
Location: mm/mmap.c:2789
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff8134fd70-ffffffff8134fda9: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c99a0)
Location: mm/mmap.c:2267
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff813c99a0-ffffffff813c99d9: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int split_vma(struct vma_iterator *vmi, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fde00)
Location: mm/mmap.c:2405
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:madvise_update_vma
  - mm/madvise.c:madvise_update_vma
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff813fde00-ffffffff813fde48: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8142a121)
Location: mm/mmap.c:2409
Inline: True
Inline callers:
  - mm/mmap.c:vma_modify
  - mm/mmap.c:vma_modify
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010301b48)
Location: mm/mmap.c:2720
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffff800010301b48-ffff800010301bb0: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c05202d0)
Location: mm/mmap.c:2720
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
c05202d0-c052030c: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cddc0)
Location: mm/mmap.c:2720
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
c0000000003cddc0-c0000000003cddf8: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020ecf2)
Location: mm/mmap.c:2720
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffe00020ecf2-ffffffe00020ed46: split_vma (STB_GLOBAL)
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
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81262a70)
Location: mm/mmap.c:2720
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff81262a70-ffffffff81262a91: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81254e90)
Location: mm/mmap.c:2720
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff81254e90-ffffffff81254eb1: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81260810)
Location: mm/mmap.c:2720
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff81260810-ffffffff81260831: split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812701e0)
Location: mm/mmap.c:2720
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff812701e0-ffffffff81270201: split_vma (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vma_iterator *vmi</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *mm</code>
</li>
</ul>
</details>
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
