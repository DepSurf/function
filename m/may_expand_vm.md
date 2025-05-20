# Function: <code>may_expand_vm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int may_expand_vm(struct mm_struct *mm, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c6147)
Location: mm/mmap.c:3007
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
Direct callers:
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff811c8180-ffffffff811c81b6: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e2a60)
Location: mm/mmap.c:2943
Inline: True
Direct callers:
  - mm/mmap.c:do_brk
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff811e2a60-ffffffff811e2b3a: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f2a30)
Location: mm/mmap.c:3096
Inline: True
Direct callers:
  - mm/mmap.c:do_brk
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff811f2a30-ffffffff811f2b0a: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fd9c0)
Location: mm/mmap.c:3150
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff811fd9c0-ffffffff811fda97: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81215f70)
Location: mm/mmap.c:3193
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff81215f70-ffffffff81216048: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:3248
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff81238f51-ffffffff81238faf: may_expand_vm.cold.40 (STB_LOCAL)
ffffffff81236d80-ffffffff81236e11: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff8124a678)
Location: mm/mmap.c:3292
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff8124c911-ffffffff8124c96f: may_expand_vm.cold.34 (STB_LOCAL)
ffffffff8124a630-ffffffff8124a6c1: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff8125c9e8)
Location: mm/mmap.c:3298
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff8125ed57-ffffffff8125edb7: may_expand_vm.cold (STB_LOCAL)
ffffffff8125c9a0-ffffffff8125ca39: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff8126b148)
Location: mm/mmap.c:3304
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff8126d567-ffffffff8126d5c7: may_expand_vm.cold (STB_LOCAL)
ffffffff8126b100-ffffffff8126b199: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff8129b4c0)
Location: mm/mmap.c:3316
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:mremap_to
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff81298ae0-ffffffff81298b50: may_expand_vm.part.0 (STB_LOCAL)
ffffffff8129d767-ffffffff8129d7c7: may_expand_vm.part.0.cold (STB_LOCAL)
ffffffff8129d320-ffffffff8129d376: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff812a6690)
Location: mm/mmap.c:3374
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:mremap_to
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff812a3c60-ffffffff812a3cd0: may_expand_vm.part.0 (STB_LOCAL)
ffffffff81be7a1f-ffffffff81be7a7b: may_expand_vm.part.0.cold (STB_LOCAL)
ffffffff812a8720-ffffffff812a8776: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff812ac158)
Location: mm/mmap.c:3345
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:mremap_to
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff81bd9879-ffffffff81bd98dd: may_expand_vm.cold (STB_LOCAL)
ffffffff812ac110-ffffffff812ac1a2: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff812ed890)
Location: mm/mmap.c:3325
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:mremap_to
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff81cbc856-ffffffff81cbc907: may_expand_vm.cold (STB_LOCAL)
ffffffff812ed830-ffffffff812ed8f7: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:3318
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff81e6e446-ffffffff81e6e4f7: may_expand_vm.cold (STB_LOCAL)
ffffffff81350bc0-ffffffff81350c9c: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:3277
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:expand_downwards
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff820643a0-ffffffff820643e5: may_expand_vm.cold (STB_LOCAL)
ffffffff813ca5f0-ffffffff813ca738: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:3372
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:expand_downwards
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff820e3a7e-ffffffff820e3ac3: may_expand_vm.cold (STB_LOCAL)
ffffffff813febc0-ffffffff813fed08: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:3460
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:expand_downwards
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff821c0627-ffffffff821c066c: may_expand_vm.cold (STB_LOCAL)
ffffffff8142b030-ffffffff8142b178: may_expand_vm (STB_GLOBAL)
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
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff8000103027d8)
Location: mm/mmap.c:3304
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffff8000103027d8-ffff8000103028d8: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0520e94)
Location: mm/mmap.c:3304
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
c0520e94-c0520f90: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cee30)
Location: mm/mmap.c:3304
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
c0000000003cee30-c0000000003cef44: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020f652)
Location: mm/mmap.c:3304
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffe00020f652-ffffffe00020f71c: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff81263798)
Location: mm/mmap.c:3304
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff81265bb7-ffffffff81265c17: may_expand_vm.cold (STB_LOCAL)
ffffffff81263750-ffffffff812637e9: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff81255bb8)
Location: mm/mmap.c:3304
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff81257fd7-ffffffff81258037: may_expand_vm.cold (STB_LOCAL)
ffffffff81255b70-ffffffff81255c09: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff81261538)
Location: mm/mmap.c:3304
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff81263957-ffffffff812639b7: may_expand_vm.cold (STB_LOCAL)
ffffffff812614f0-ffffffff81261589: may_expand_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool may_expand_vm(struct mm_struct *mm, vm_flags_t flags, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff81270f08)
Location: mm/mmap.c:3304
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
```
**Symbols:**

```
ffffffff81273317-ffffffff81273377: may_expand_vm.cold (STB_LOCAL)
ffffffff81270ec0-ffffffff81270f59: may_expand_vm (STB_GLOBAL)
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
<code>vm_flags_t flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, npages</code> ➡️ <code>mm, flags, npages</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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
