# Function: <code>gup_pte_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, int write, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff81071490)
Location: arch/x86/mm/gup.c:71
Inline: False
Direct callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
**Symbols:**

```
ffffffff81071490-ffffffff810715d9: gup_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, int write, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff81071740)
Location: arch/x86/mm/gup.c:105
Inline: False
Direct callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
**Symbols:**

```
ffffffff81071740-ffffffff81071a51: gup_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, int write, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff810752d0)
Location: arch/x86/mm/gup.c:105
Inline: False
Direct callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
**Symbols:**

```
ffffffff810752d0-ffffffff810755de: gup_pte_range (STB_LOCAL)
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
In mm/gup.c (ffffffff811f0891)
Location: mm/gup.c:1279
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
In mm/gup.c (ffffffff812053c0)
Location: mm/gup.c:1368
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
In mm/gup.c (ffffffff81226a63)
Location: mm/gup.c:1372
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
In mm/gup.c (ffffffff81239b60)
Location: mm/gup.c:1397
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
In mm/gup.c (ffffffff8124ad9f)
Location: mm/gup.c:1818
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
In mm/gup.c (ffffffff8125928f)
Location: mm/gup.c:1821
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
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81287f50)
Location: mm/gup.c:2219
Inline: False
```
**Symbols:**

```
ffffffff81287f50-ffffffff8128822a: gup_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81291c30)
Location: mm/gup.c:1997
Inline: False
```
**Symbols:**

```
ffffffff81291c30-ffffffff81291f0c: gup_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81297750)
Location: mm/gup.c:2063
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff81297750-ffffffff81297a2a: gup_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d8110)
Location: mm/gup.c:2151
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff812d8110-ffffffff812d8463: gup_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81338000)
Location: mm/gup.c:2281
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff81338000-ffffffff813383f5: gup_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gup_pte_range(pmd_t pmd, pmd_t *pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813af7a0)
Location: mm/gup.c:2328
Inline: False
```
**Symbols:**

```
ffffffff813af7a0-ffffffff813afbd9: gup_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gup_pte_range(pmd_t pmd, pmd_t *pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e3f40)
Location: mm/gup.c:2549
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff813e3f40-ffffffff813e42ef: gup_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gup_pte_range(pmd_t pmd, pmd_t *pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8140e7a0)
Location: mm/gup.c:2567
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff8140e7a0-ffffffff8140eb05: gup_pte_range (STB_LOCAL)
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
In mm/gup.c (ffff8000102f1108)
Location: mm/gup.c:1821
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
In mm/gup.c (c0000000003b69ec)
Location: mm/gup.c:1821
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
In mm/gup.c (ffffffff812518df)
Location: mm/gup.c:1821
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
In mm/gup.c (ffffffff812447b3)
Location: mm/gup.c:1821
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
In mm/gup.c (ffffffff8124f67f)
Location: mm/gup.c:1821
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
In mm/gup.c (ffffffff8125efef)
Location: mm/gup.c:1821
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pmd_t *pmdp</code>
</li>
<li>
<b>Param reordered. </b>
<code>pmd, addr, end, flags, pages, nr</code> ➡️ <code>pmd, pmdp, addr, end, flags, pages, nr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
