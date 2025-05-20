# Function: <code>untrack_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81070af0)
Location: arch/x86/mm/pat.c:972
Inline: False
Direct callers:
  - mm/memory.c:unmap_single_vma
  - mm/memory.c:remap_pfn_range
```
**Symbols:**

```
ffffffff81070af0-ffffffff81070bbb: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810708a0)
Location: arch/x86/mm/pat.c:996
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff810708a0-ffffffff81070980: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81074530)
Location: arch/x86/mm/pat.c:1007
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff81074530-ffffffff81074610: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81073aa0)
Location: arch/x86/mm/pat.c:1004
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff81073aa0-ffffffff81073b5c: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81079460)
Location: arch/x86/mm/pat.c:1026
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
  - mm/hmm.c:hmm_devmem_pages_create
```
**Symbols:**

```
ffffffff81079460-ffffffff8107951c: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8107bd30)
Location: arch/x86/mm/pat.c:1042
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
  - mm/hmm.c:hmm_devmem_pages_create
```
**Symbols:**

```
ffffffff8107bd30-ffffffff8107bdf1: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810826a0)
Location: arch/x86/mm/pat.c:1051
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff810826a0-ffffffff81082761: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81086310)
Location: arch/x86/mm/pat.c:1052
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages_release
```
**Symbols:**

```
ffffffff81086310-ffffffff810863cd: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81087000)
Location: arch/x86/mm/pat.c:1052
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81087000-ffffffff810870bd: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810906d0)
Location: arch/x86/mm/pat/memtype.c:1079
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff810906d0-ffffffff81090794: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810903d0)
Location: arch/x86/mm/pat/memtype.c:1079
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pageunmap_range
```
**Symbols:**

```
ffffffff810903d0-ffffffff81090494: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff81090f40)
Location: arch/x86/mm/pat/memtype.c:1081
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81090f40-ffffffff81091004: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810a0ad0)
Location: arch/x86/mm/pat/memtype.c:1086
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff810a0ad0-ffffffff810a0b8b: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810b4ac0)
Location: arch/x86/mm/pat/memtype.c:1094
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff810b4ac0-ffffffff810b4b98: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810cf8a0)
Location: arch/x86/mm/pat/memtype.c:1047
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff810cf8a0-ffffffff810cf978: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size, bool mm_wr_locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810d2e80)
Location: arch/x86/mm/pat/memtype.c:1047
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff810d2e80-ffffffff810d2f8d: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size, bool mm_wr_locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810db610)
Location: arch/x86/mm/pat/memtype.c:1047
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff810db610-ffffffff810db71d: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:835
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:835
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:835
Inline: True
```
```
In mm/memremap.c (0)
Location: include/asm-generic/pgtable.h:835
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:835
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
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81086000)
Location: arch/x86/mm/pat.c:1052
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81086000-ffffffff810860bd: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81074d80)
Location: arch/x86/mm/pat.c:1052
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81074d80-ffffffff81074e3d: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81085fb0)
Location: arch/x86/mm/pat.c:1052
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81085fb0-ffffffff8108606d: untrack_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void untrack_pfn(struct vm_area_struct *vma, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81088100)
Location: arch/x86/mm/pat.c:1052
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_single_vma
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81088100-ffffffff810881bd: untrack_pfn (STB_GLOBAL)
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
<code>bool mm_wr_locked</code>
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
