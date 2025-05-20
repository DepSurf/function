# Function: <code>mpol_misplaced</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e2c40)
Location: mm/mempolicy.c:2247
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff811e2c40-ffffffff811e2de3: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81201620)
Location: mm/mempolicy.c:2268
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81201620-ffffffff812017d5: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81213110)
Location: mm/mempolicy.c:2262
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81213110-ffffffff812132c5: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121e430)
Location: mm/mempolicy.c:2164
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff8121e430-ffffffff8121e5e3: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81239680)
Location: mm/mempolicy.c:2226
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81239680-ffffffff8123980a: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125cc20)
Location: mm/mempolicy.c:2286
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff8125cc20-ffffffff8125cdbd: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81271500)
Location: mm/mempolicy.c:2325
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81271500-ffffffff8127169d: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128cb10)
Location: mm/mempolicy.c:2346
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff8128cb10-ffffffff8128ccb5: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129c740)
Location: mm/mempolicy.c:2385
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff8129c740-ffffffff8129c8e5: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d0390)
Location: mm/mempolicy.c:2484
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff812d0390-ffffffff812d0592: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812dbeb0)
Location: mm/mempolicy.c:2459
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff812dbeb0-ffffffff812dc0b2: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e3720)
Location: mm/mempolicy.c:2461
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff812e3720-ffffffff812e395d: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8132a940)
Location: mm/mempolicy.c:2378
Inline: False
Direct callers:
  - mm/memory.c:numa_migrate_prep
```
**Symbols:**

```
ffffffff8132a940-ffffffff8132ac38: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8139a2f0)
Location: mm/mempolicy.c:2554
Inline: False
Direct callers:
  - mm/memory.c:numa_migrate_prep
```
**Symbols:**

```
ffffffff8139a2f0-ffffffff8139a5eb: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8141a310)
Location: mm/mempolicy.c:2569
Inline: False
Direct callers:
  - mm/memory.c:numa_migrate_prep
```
**Symbols:**

```
ffffffff8141a310-ffffffff8141a608: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144d8b0)
Location: mm/mempolicy.c:2580
Inline: False
Direct callers:
  - mm/memory.c:numa_migrate_prep
```
**Symbols:**

```
ffffffff8144d8b0-ffffffff8144db80: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mpol_misplaced(struct folio *folio, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814874e0)
Location: mm/mempolicy.c:2480
Inline: False
Direct callers:
  - mm/memory.c:numa_migrate_prep
```
**Symbols:**

```
ffffffff814874e0-ffffffff81487720: mpol_misplaced (STB_GLOBAL)
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
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff80001033b6c0)
Location: mm/mempolicy.c:2385
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffff80001033b6c0-ffff80001033b874: mpol_misplaced (STB_GLOBAL)
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
Location: include/linux/mempolicy.h:302
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000416420)
Location: mm/mempolicy.c:2385
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
c000000000416420-c000000000416668: mpol_misplaced (STB_GLOBAL)
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
Location: include/linux/mempolicy.h:302
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
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81294d20)
Location: mm/mempolicy.c:2385
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81294d20-ffffffff81294ec5: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81286930)
Location: mm/mempolicy.c:2385
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81286930-ffffffff81286ad5: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81292b30)
Location: mm/mempolicy.c:2385
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81292b30-ffffffff81292cd5: mpol_misplaced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mpol_misplaced(struct page *page, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a2920)
Location: mm/mempolicy.c:2385
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff812a2920-ffffffff812a2ac5: mpol_misplaced (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
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
