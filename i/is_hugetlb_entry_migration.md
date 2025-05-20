# Function: <code>is_hugetlb_entry_migration</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811db110)
Location: mm/hugetlb.c:3052
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:follow_huge_pmd
```
**Symbols:**

```
ffffffff811db110-ffffffff811db163: is_hugetlb_entry_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811f9290)
Location: mm/hugetlb.c:3079
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff811f9290-ffffffff811f92eb: is_hugetlb_entry_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81209e70)
Location: mm/hugetlb.c:3185
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff81209e70-ffffffff81209ecb: is_hugetlb_entry_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81217500)
Location: mm/hugetlb.c:3168
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff81217500-ffffffff81217558: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812321b0)
Location: mm/hugetlb.c:3184
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff812321b0-ffffffff81232210: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81255200)
Location: mm/hugetlb.c:3214
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff81255200-ffffffff81255260: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812695e0)
Location: mm/hugetlb.c:3208
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff812695e0-ffffffff81269640: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81284760)
Location: mm/hugetlb.c:3276
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff81284760-ffffffff812847c0: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81294300)
Location: mm/hugetlb.c:3393
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff81294300-ffffffff81294360: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c76d0)
Location: mm/hugetlb.c:3804
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff812c76d0-ffffffff812c7746: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d3240)
Location: mm/hugetlb.c:3774
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff812d3240-ffffffff812d32b5: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d9f90)
Location: mm/hugetlb.c:3943
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff812d9f90-ffffffff812da000: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81320d40)
Location: mm/hugetlb.c:4232
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff81320d40-ffffffff81320db0: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138da30)
Location: mm/hugetlb.c:4683
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/migrate.c:__migration_entry_wait_huge
```
**Symbols:**

```
ffffffff8138da30-ffffffff8138dac8: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8140c7a0)
Location: mm/hugetlb.c:4922
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/migrate.c:__migration_entry_wait_huge
```
**Symbols:**

```
ffffffff8140c7a0-ffffffff8140c838: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8143fc10)
Location: mm/hugetlb.c:4997
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/migrate.c:migration_entry_wait_huge
```
**Symbols:**

```
ffffffff8143fc10-ffffffff8143fca1: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81479830)
Location: mm/hugetlb.c:5255
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/migrate.c:migration_entry_wait_huge
```
**Symbols:**

```
ffffffff81479830-ffffffff814798c1: is_hugetlb_entry_migration (STB_GLOBAL)
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
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010335dd8)
Location: mm/hugetlb.c:3393
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffff800010332708-ffff80001033275c: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040bac0)
Location: mm/hugetlb.c:3393
Inline: False
Direct callers:
  - arch/powerpc/mm/hugetlbpage.c:follow_huge_pd
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
c00000000040bac0-c00000000040bb94: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe000231eba)
Location: mm/hugetlb.c:3393
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffe00022f262-ffffffe00022f2a0: is_hugetlb_entry_migration (STB_GLOBAL)
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
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128c8e0)
Location: mm/hugetlb.c:3393
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff8128c8e0-ffffffff8128c940: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127e710)
Location: mm/hugetlb.c:3393
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff8127e710-ffffffff8127e758: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128a6f0)
Location: mm/hugetlb.c:3393
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff8128a6f0-ffffffff8128a750: is_hugetlb_entry_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool is_hugetlb_entry_migration(pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129a4e0)
Location: mm/hugetlb.c:3393
Inline: False
Direct callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff8129a4e0-ffffffff8129a540: is_hugetlb_entry_migration (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
