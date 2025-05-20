# Function: <code>track_pfn_remap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810709b0)
Location: arch/x86/mm/pat.c:912
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
```
**Symbols:**

```
ffffffff810709b0-ffffffff81070a88: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81070730)
Location: arch/x86/mm/pat.c:935
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/memory.c:remap_pfn_range
```
**Symbols:**

```
ffffffff81070730-ffffffff8107084f: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810743c0)
Location: arch/x86/mm/pat.c:949
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/memory.c:remap_pfn_range
```
**Symbols:**

```
ffffffff810743c0-ffffffff810744df: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81073910)
Location: arch/x86/mm/pat.c:946
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/memory.c:remap_pfn_range
```
**Symbols:**

```
ffffffff81073910-ffffffff81073a41: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810792d0)
Location: arch/x86/mm/pat.c:968
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/memory.c:remap_pfn_range
```
**Symbols:**

```
ffffffff810792d0-ffffffff81079401: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8107bbe0)
Location: arch/x86/mm/pat.c:984
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/memory.c:remap_pfn_range
```
**Symbols:**

```
ffffffff8107bbe0-ffffffff8107bce0: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81082550)
Location: arch/x86/mm/pat.c:993
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/memory.c:remap_pfn_range
```
**Symbols:**

```
ffffffff81082550-ffffffff81082650: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810861d0)
Location: arch/x86/mm/pat.c:994
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff810861d0-ffffffff810862b5: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81086ec0)
Location: arch/x86/mm/pat.c:994
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81086ec0-ffffffff81086fa5: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810905b0)
Location: arch/x86/mm/pat/memtype.c:1021
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff810905b0-ffffffff8109068e: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810902b0)
Location: arch/x86/mm/pat/memtype.c:1021
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff810902b0-ffffffff8109038e: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff81090e20)
Location: arch/x86/mm/pat/memtype.c:1023
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81090e20-ffffffff81090efe: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:1028
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81ca183f-ffffffff81ca1854: track_pfn_remap.cold (STB_LOCAL)
ffffffff810a0980-ffffffff810a0a6d: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:1036
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81e50e5f-ffffffff81e50e74: track_pfn_remap.cold (STB_LOCAL)
ffffffff810b4950-ffffffff810b4a52: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:989
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff82054f5a-ffffffff82054f6f: track_pfn_remap.cold (STB_LOCAL)
ffffffff810cf710-ffffffff810cf812: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:989
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff820d3529-ffffffff820d353e: track_pfn_remap.cold (STB_LOCAL)
ffffffff810d2cd0-ffffffff810d2dfb: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:989
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff821ae397-ffffffff821ae3ac: track_pfn_remap.cold (STB_LOCAL)
ffffffff810db460-ffffffff810db58b: track_pfn_remap (STB_GLOBAL)
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
Location: include/asm-generic/pgtable.h:805
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
Location: include/asm-generic/pgtable.h:805
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
Location: include/asm-generic/pgtable.h:805
Inline: True
```
```
In mm/memremap.c (0)
Location: include/asm-generic/pgtable.h:805
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
Location: include/asm-generic/pgtable.h:805
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
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81085ec0)
Location: arch/x86/mm/pat.c:994
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81085ec0-ffffffff81085fa5: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81074c40)
Location: arch/x86/mm/pat.c:994
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81074c40-ffffffff81074d25: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81085e70)
Location: arch/x86/mm/pat.c:994
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81085e70-ffffffff81085f55: track_pfn_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int track_pfn_remap(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn, long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81087fc0)
Location: arch/x86/mm/pat.c:994
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81087fc0-ffffffff810880a5: track_pfn_remap (STB_GLOBAL)
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
