# Function: <code>__split_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff811c5420)
Location: mm/mmap.c:2451
Inline: True
Direct callers:
  - mm/mmap.c:split_vma
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
```
**Symbols:**

```
ffffffff811c5420-ffffffff811c5605: __split_vma.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff811e1290)
Location: mm/mmap.c:2348
Inline: True
Direct callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:split_vma
```
**Symbols:**

```
ffffffff811e1290-ffffffff811e1475: __split_vma.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff811f1250)
Location: mm/mmap.c:2501
Inline: True
Direct callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:split_vma
```
**Symbols:**

```
ffffffff811f1250-ffffffff811f143b: __split_vma.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fcc30)
Location: mm/mmap.c:2536
Inline: False
Direct callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff811fcc30-ffffffff811fce16: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812151c0)
Location: mm/mmap.c:2552
Inline: True
Direct callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff812151c0-ffffffff812153b1: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81236030)
Location: mm/mmap.c:2612
Inline: False
Direct callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff81236030-ffffffff812361e2: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81249850)
Location: mm/mmap.c:2646
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff81249850-ffffffff81249a02: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125bb80)
Location: mm/mmap.c:2651
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff8125bb80-ffffffff8125bd2e: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126a270)
Location: mm/mmap.c:2656
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff8126a270-ffffffff8126a41e: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129acc0)
Location: mm/mmap.c:2665
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:madvise_behavior
  - mm/madvise.c:madvise_behavior
```
**Symbols:**

```
ffffffff8129acc0-ffffffff8129ae6e: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a5e80)
Location: mm/mmap.c:2728
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:madvise_behavior
  - mm/madvise.c:madvise_behavior
```
**Symbols:**

```
ffffffff812a5e80-ffffffff812a602e: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ab1f0)
Location: mm/mmap.c:2732
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:madvise_behavior
  - mm/madvise.c:madvise_behavior
```
**Symbols:**

```
ffffffff812ab1f0-ffffffff812ab384: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ec8c0)
Location: mm/mmap.c:2702
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:madvise_behavior
  - mm/madvise.c:madvise_behavior
```
**Symbols:**

```
ffffffff812ec8c0-ffffffff812eca6e: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134fbb0)
Location: mm/mmap.c:2725
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:madvise_update_vma
  - mm/madvise.c:madvise_update_vma
```
**Symbols:**

```
ffffffff8134fbb0-ffffffff8134fd6f: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c92b0)
Location: mm/mmap.c:2198
Inline: False
Direct callers:
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:madvise_update_vma
  - mm/madvise.c:madvise_update_vma
```
**Symbols:**

```
ffffffff813c92b0-ffffffff813c946f: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __split_vma(struct vma_iterator *vmi, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fd640)
Location: mm/mmap.c:2323
Inline: False
Direct callers:
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:split_vma
```
**Symbols:**

```
ffffffff813fd640-ffffffff813fd88e: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __split_vma(struct vma_iterator *vmi, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81427760)
Location: mm/mmap.c:2327
Inline: False
Direct callers:
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:vma_modify
  - mm/mmap.c:vma_modify
```
**Symbols:**

```
ffffffff81427760-ffffffff81427a35: __split_vma (STB_LOCAL)
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
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff8000103019a0)
Location: mm/mmap.c:2656
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:__arm64_sys_madvise
```
**Symbols:**

```
ffff8000103019a0-ffff800010301b48: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0520140)
Location: mm/mmap.c:2656
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
c0520140-c05202d0: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cdb50)
Location: mm/mmap.c:2656
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
c0000000003cdb50-c0000000003cddb4: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020ebc0)
Location: mm/mmap.c:2656
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
ffffffe00020ebc0-ffffffe00020ecf2: __split_vma (STB_GLOBAL)
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
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812628c0)
Location: mm/mmap.c:2656
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff812628c0-ffffffff81262a6e: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81254ce0)
Location: mm/mmap.c:2656
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81254ce0-ffffffff81254e8e: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81260660)
Location: mm/mmap.c:2656
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81260660-ffffffff8126080e: __split_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __split_vma(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, int new_below);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81270030)
Location: mm/mmap.c:2656
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:split_vma
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81270030-ffffffff812701de: __split_vma (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
