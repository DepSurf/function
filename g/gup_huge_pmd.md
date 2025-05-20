# Function: <code>gup_huge_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gup_huge_pmd(pmd_t pmd, long unsigned int addr, long unsigned int end, int write, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff81071720)
Location: arch/x86/mm/gup.c:117
Inline: False
Direct callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
**Symbols:**

```
ffffffff81071720-ffffffff81071851: gup_huge_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gup_huge_pmd(pmd_t pmd, long unsigned int addr, long unsigned int end, int write, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff81071420)
Location: arch/x86/mm/gup.c:183
Inline: False
Direct callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
**Symbols:**

```
ffffffff81071420-ffffffff81071740: gup_huge_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gup_huge_pmd(pmd_t pmd, long unsigned int addr, long unsigned int end, int write, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff81074fa0)
Location: arch/x86/mm/gup.c:187
Inline: False
Direct callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
**Symbols:**

```
ffffffff81074fa0-ffffffff810752c1: gup_huge_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811f0db2)
Location: mm/gup.c:1413
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81205938)
Location: mm/gup.c:1502
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81226dde)
Location: mm/gup.c:1525
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81239e63)
Location: mm/gup.c:1550
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124b0a6)
Location: mm/gup.c:2058
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81259596)
Location: mm/gup.c:2073
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gup_huge_pmd(pmd_t orig, pmd_t *pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128ac10)
Location: mm/gup.c:2480
Inline: False
```
**Symbols:**

```
ffffffff8128ac10-ffffffff8128aec6: gup_huge_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gup_huge_pmd(pmd_t orig, pmd_t *pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812948d0)
Location: mm/gup.c:2258
Inline: False
```
**Symbols:**

```
ffffffff812948d0-ffffffff81294b86: gup_huge_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gup_huge_pmd(pmd_t orig, pmd_t *pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8129a310)
Location: mm/gup.c:2324
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff8129a310-ffffffff8129a5c0: gup_huge_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gup_huge_pmd(pmd_t orig, pmd_t *pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812daca0)
Location: mm/gup.c:2419
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff812daca0-ffffffff812daf42: gup_huge_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gup_huge_pmd(pmd_t orig, pmd_t *pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8133a850)
Location: mm/gup.c:2554
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff8133a850-ffffffff8133ab29: gup_huge_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gup_huge_pmd(pmd_t orig, pmd_t *pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b2360)
Location: mm/gup.c:2606
Inline: False
```
**Symbols:**

```
ffffffff813b2360-ffffffff813b2663: gup_huge_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gup_huge_pmd(pmd_t orig, pmd_t *pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e70b0)
Location: mm/gup.c:2846
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff813e70b0-ffffffff813e7369: gup_huge_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gup_huge_pmd(pmd_t orig, pmd_t *pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81411d30)
Location: mm/gup.c:2864
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff81411d30-ffffffff81412006: gup_huge_pmd (STB_LOCAL)
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
In mm/gup.c (ffff8000102f1234)
Location: mm/gup.c:2073
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b6db8)
Location: mm/gup.c:2073
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81251be6)
Location: mm/gup.c:2073
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124496a)
Location: mm/gup.c:2073
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124f986)
Location: mm/gup.c:2073
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125f310)
Location: mm/gup.c:2073
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
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
