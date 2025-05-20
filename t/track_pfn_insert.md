# Function: <code>track_pfn_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81070a90)
Location: arch/x86/mm/pat.c:951
Inline: False
Direct callers:
  - mm/memory.c:vm_insert_pfn
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff81070a90-ffffffff81070ae5: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81070850)
Location: arch/x86/mm/pat.c:975
Inline: False
Direct callers:
  - mm/memory.c:vm_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff81070850-ffffffff81070899: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810744e0)
Location: arch/x86/mm/pat.c:989
Inline: False
Direct callers:
  - mm/memory.c:vm_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff810744e0-ffffffff81074525: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81073a50)
Location: arch/x86/mm/pat.c:986
Inline: False
Direct callers:
  - mm/memory.c:vm_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff81073a50-ffffffff81073a93: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81079410)
Location: arch/x86/mm/pat.c:1008
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vm_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff81079410-ffffffff81079453: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8107bce0)
Location: arch/x86/mm/pat.c:1024
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vm_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff8107bce0-ffffffff8107bd22: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81082650)
Location: arch/x86/mm/pat.c:1033
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff81082650-ffffffff81082692: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810862c0)
Location: arch/x86/mm/pat.c:1034
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff810862c0-ffffffff81086302: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81086fb0)
Location: arch/x86/mm/pat.c:1034
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff81086fb0-ffffffff81086ff2: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff81090690)
Location: arch/x86/mm/pat/memtype.c:1061
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
**Symbols:**

```
ffffffff81090690-ffffffff810906ce: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff81090390)
Location: arch/x86/mm/pat/memtype.c:1061
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
**Symbols:**

```
ffffffff81090390-ffffffff810903ce: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff81090f00)
Location: arch/x86/mm/pat/memtype.c:1063
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
**Symbols:**

```
ffffffff81090f00-ffffffff81090f3e: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:1068
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
**Symbols:**

```
ffffffff81ca1854-ffffffff81ca1870: track_pfn_insert.cold (STB_LOCAL)
ffffffff810a0a70-ffffffff810a0ac2: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:1076
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
**Symbols:**

```
ffffffff81e50e74-ffffffff81e50e90: track_pfn_insert.cold (STB_LOCAL)
ffffffff810b4a60-ffffffff810b4abe: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:1029
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
**Symbols:**

```
ffffffff82054f6f-ffffffff82054f8b: track_pfn_insert.cold (STB_LOCAL)
ffffffff810cf830-ffffffff810cf88e: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:1029
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff820d353e-ffffffff820d355a: track_pfn_insert.cold (STB_LOCAL)
ffffffff810d2e10-ffffffff810d2e6e: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:1029
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff821ae3ac-ffffffff821ae3c8: track_pfn_insert.cold (STB_LOCAL)
ffffffff810db5a0-ffffffff810db5fe: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:816
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable.h:816
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
Location: include/asm-generic/pgtable.h:816
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
Location: include/asm-generic/pgtable.h:816
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable.h:816
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
Location: include/asm-generic/pgtable.h:816
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
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81085fb0)
Location: arch/x86/mm/pat.c:1034
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff81085fb0-ffffffff81085ff2: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81074d30)
Location: arch/x86/mm/pat.c:1034
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff81074d30-ffffffff81074d72: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81085f60)
Location: arch/x86/mm/pat.c:1034
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff81085f60-ffffffff81085fa2: track_pfn_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void track_pfn_insert(struct vm_area_struct *vma, pgprot_t *prot, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810880b0)
Location: arch/x86/mm/pat.c:1034
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff810880b0-ffffffff810880f2: track_pfn_insert (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>long unsigned int pfn</code> ➡️ <code>pfn_t pfn</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
