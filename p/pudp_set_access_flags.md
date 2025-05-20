# Function: <code>pudp_set_access_flags</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81073fd0)
Location: arch/x86/mm/pgtable.c:459
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
```
**Symbols:**

```
ffffffff81073fd0-ffffffff8107400a: pudp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81079a00)
Location: arch/x86/mm/pgtable.c:459
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
```
**Symbols:**

```
ffffffff81079a00-ffffffff81079a3a: pudp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8107c5d0)
Location: arch/x86/mm/pgtable.c:464
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
```
**Symbols:**

```
ffffffff8107c5d0-ffffffff8107c60a: pudp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81082fd0)
Location: arch/x86/mm/pgtable.c:530
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
```
**Symbols:**

```
ffffffff81082fd0-ffffffff81083015: pudp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086c40)
Location: arch/x86/mm/pgtable.c:517
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
**Symbols:**

```
ffffffff81086c40-ffffffff81086c8d: pudp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81087930)
Location: arch/x86/mm/pgtable.c:513
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
**Symbols:**

```
ffffffff81087930-ffffffff8108797d: pudp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089d60)
Location: arch/x86/mm/pgtable.c:520
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
**Symbols:**

```
ffffffff81089d60-ffffffff81089db8: pudp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089fe0)
Location: arch/x86/mm/pgtable.c:520
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
**Symbols:**

```
ffffffff81089fe0-ffffffff8108a038: pudp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108ac40)
Location: arch/x86/mm/pgtable.c:520
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
**Symbols:**

```
ffffffff8108ac40-ffffffff8108ac98: pudp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8109a1e0)
Location: arch/x86/mm/pgtable.c:520
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
**Symbols:**

```
ffffffff8109a1e0-ffffffff8109a238: pudp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ad300)
Location: arch/x86/mm/pgtable.c:520
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
**Symbols:**

```
ffffffff810ad300-ffffffff810ad380: pudp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c73e0)
Location: arch/x86/mm/pgtable.c:524
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
**Symbols:**

```
ffffffff810c73e0-ffffffff810c7470: pudp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810cab30)
Location: arch/x86/mm/pgtable.c:524
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
**Symbols:**

```
ffffffff810cab30-ffffffff810cabc0: pudp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d3080)
Location: arch/x86/mm/pgtable.c:536
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
**Symbols:**

```
ffffffff810d3080-ffffffff810d3110: pudp_set_access_flags (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086930)
Location: arch/x86/mm/pgtable.c:513
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
**Symbols:**

```
ffffffff81086930-ffffffff8108697d: pudp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810755e0)
Location: arch/x86/mm/pgtable.c:513
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
**Symbols:**

```
ffffffff810755e0-ffffffff81075605: pudp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810868e0)
Location: arch/x86/mm/pgtable.c:513
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
**Symbols:**

```
ffffffff810868e0-ffffffff8108692d: pudp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, pud_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81088a10)
Location: arch/x86/mm/pgtable.c:513
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
**Symbols:**

```
ffffffff81088a10-ffffffff81088a5d: pudp_set_access_flags (STB_GLOBAL)
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
