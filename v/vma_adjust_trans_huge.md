# Function: <code>vma_adjust_trans_huge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f91f0)
Location: mm/huge_memory.c:3047
Inline: False
Direct callers:
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_adjust
```
**Symbols:**

```
ffffffff811f91f0-ffffffff811f92cc: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812167d0)
Location: mm/huge_memory.c:1686
Inline: False
Direct callers:
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:vma_adjust
```
**Symbols:**

```
ffffffff812167d0-ffffffff812168a1: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81228d90)
Location: mm/huge_memory.c:1814
Inline: False
Direct callers:
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff81228d90-ffffffff81228e61: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81234a80)
Location: mm/huge_memory.c:2141
Inline: False
Direct callers:
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff81234a80-ffffffff81234b4a: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812544a0)
Location: mm/huge_memory.c:2293
Inline: False
Direct callers:
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff812544a0-ffffffff8125456a: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812782f0)
Location: mm/huge_memory.c:2285
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff812782f0-ffffffff812783be: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128c930)
Location: mm/huge_memory.c:2307
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff8128c930-ffffffff8128c9fe: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a7610)
Location: mm/huge_memory.c:2365
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff812a7610-ffffffff812a76e7: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b8ab0)
Location: mm/huge_memory.c:2370
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff812b8ab0-ffffffff812b8b87: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ed660)
Location: mm/huge_memory.c:2280
Inline: False
Direct callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff812ed660-ffffffff812ed737: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f8d80)
Location: mm/huge_memory.c:2304
Inline: False
Direct callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff812f8d80-ffffffff812f8e53: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ff2d0)
Location: mm/huge_memory.c:2333
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff812ff2d0-ffffffff812ff3e3: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81348ee0)
Location: mm/huge_memory.c:2261
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff81348ee0-ffffffff81348ff3: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813bf360)
Location: mm/huge_memory.c:2281
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff813bf360-ffffffff813bf496: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81441840)
Location: mm/huge_memory.c:2352
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_expand
```
**Symbols:**

```
ffffffff81441840-ffffffff814419e2: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81477210)
Location: mm/huge_memory.c:2345
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_shrink
  - mm/mmap.c:vma_expand
```
**Symbols:**

```
ffffffff81477210-ffffffff814773b2: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a6990)
Location: mm/huge_memory.c:2676
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_shrink
  - mm/mmap.c:vma_expand
```
**Symbols:**

```
ffffffff814a6990-ffffffff814a6b32: vma_adjust_trans_huge (STB_GLOBAL)
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
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010359140)
Location: mm/huge_memory.c:2370
Inline: False
Direct callers:
  - mm/mmap.c:__arm64_sys_remap_file_pages
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffff800010359140-ffff800010359240: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (0)
Location: include/linux/huge_mm.h:350
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c000000000442410)
Location: mm/huge_memory.c:2370
Inline: False
Direct callers:
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
c000000000442410-c0000000004425d4: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (0)
Location: include/linux/huge_mm.h:350
Inline: True
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
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b1090)
Location: mm/huge_memory.c:2370
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff812b1090-ffffffff812b1167: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a2460)
Location: mm/huge_memory.c:2370
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff812a2460-ffffffff812a2537: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812aeea0)
Location: mm/huge_memory.c:2370
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff812aeea0-ffffffff812aef77: vma_adjust_trans_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vma_adjust_trans_huge(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long int adjust_next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bf1f0)
Location: mm/huge_memory.c:2370
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff812bf1f0-ffffffff812bf2c7: vma_adjust_trans_huge (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
