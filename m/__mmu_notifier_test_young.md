# Function: <code>__mmu_notifier_test_young</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff811e4000)
Location: mm/mmu_notifier.c:143
Inline: False
Direct callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
```
**Symbols:**

```
ffffffff811e4000-ffffffff811e4081: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81202a90)
Location: mm/mmu_notifier.c:143
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81202a90-ffffffff81202b11: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812148d0)
Location: mm/mmu_notifier.c:143
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff812148d0-ffffffff81214951: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8121fd50)
Location: mm/mmu_notifier.c:144
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8121fd50-ffffffff8121fdd1: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8123af70)
Location: mm/mmu_notifier.c:144
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff8123af70-ffffffff8123aff4: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8125e4b0)
Location: mm/mmu_notifier.c:144
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8125e4b0-ffffffff8125e534: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81272d30)
Location: mm/mmu_notifier.c:137
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81272d30-ffffffff81272db4: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8128e520)
Location: mm/mmu_notifier.c:135
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff8128e520-ffffffff8128e5b0: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8129e100)
Location: mm/mmu_notifier.c:129
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff8129e100-ffffffff8129e190: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812d2720)
Location: mm/mmu_notifier.c:405
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff812d2720-ffffffff812d27b0: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812de150)
Location: mm/mmu_notifier.c:405
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff812de150-ffffffff812de1e0: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812e58a0)
Location: mm/mmu_notifier.c:405
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff812e58a0-ffffffff812e5930: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8132d6d0)
Location: mm/mmu_notifier.c:405
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff8132d6d0-ffffffff8132d760: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8139d8b0)
Location: mm/mmu_notifier.c:405
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff8139d8b0-ffffffff8139d947: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8141cda0)
Location: mm/mmu_notifier.c:405
Inline: False
Direct callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff8141cda0-ffffffff8141ce37: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81450360)
Location: mm/mmu_notifier.c:405
Inline: False
Direct callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff81450360-ffffffff814503f7: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8148a090)
Location: mm/mmu_notifier.c:405
Inline: False
Direct callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff8148a090-ffffffff8148a127: __mmu_notifier_test_young (STB_GLOBAL)
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
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffff80001033d560)
Location: mm/mmu_notifier.c:129
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffff80001033d560-ffff80001033d60c: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (c0543b7c)
Location: mm/mmu_notifier.c:129
Inline: False
```
**Symbols:**

```
c0543b7c-c0543c44: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (c000000000418b90)
Location: mm/mmu_notifier.c:129
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
c000000000418b90-c000000000418cc8: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffe000232cb4)
Location: mm/mmu_notifier.c:129
Inline: False
```
**Symbols:**

```
ffffffe000232cb4-ffffffe000232d38: __mmu_notifier_test_young (STB_GLOBAL)
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
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812966e0)
Location: mm/mmu_notifier.c:129
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff812966e0-ffffffff81296770: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812882f0)
Location: mm/mmu_notifier.c:129
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff812882f0-ffffffff81288380: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812944f0)
Location: mm/mmu_notifier.c:129
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff812944f0-ffffffff81294580: __mmu_notifier_test_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __mmu_notifier_test_young(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812a4360)
Location: mm/mmu_notifier.c:129
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff812a4360-ffffffff812a43f0: __mmu_notifier_test_young (STB_GLOBAL)
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
