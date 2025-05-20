# Function: <code>pgtable_trans_huge_deposit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811d04a0)
Location: mm/pgtable-generic.c:155
Inline: False
Direct callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff811d04a0-ffffffff811d057a: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811ed650)
Location: mm/pgtable-generic.c:129
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff811ed650-ffffffff811ed718: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811f7a40)
Location: mm/pgtable-generic.c:129
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff811f7a40-ffffffff811f7afd: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81202c40)
Location: mm/pgtable-generic.c:149
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81202c40-ffffffff81202cfc: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8121b9a0)
Location: mm/pgtable-generic.c:151
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff8121b9a0-ffffffff8121ba5b: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8123d780)
Location: mm/pgtable-generic.c:151
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8123d780-ffffffff8123d803: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81251d30)
Location: mm/pgtable-generic.c:152
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81251d30-ffffffff81251db3: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81264010)
Location: mm/pgtable-generic.c:152
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81264010-ffffffff81264095: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81272880)
Location: mm/pgtable-generic.c:152
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81272880-ffffffff81272905: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812a3640)
Location: mm/pgtable-generic.c:161
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812a3640-ffffffff812a36c5: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812aef20)
Location: mm/pgtable-generic.c:161
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812aef20-ffffffff812aefa5: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812b4450)
Location: mm/pgtable-generic.c:161
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812b4450-ffffffff812b44d8: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812f6030)
Location: mm/pgtable-generic.c:161
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812f6030-ffffffff812f60b8: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8135a000)
Location: mm/pgtable-generic.c:162
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8135a000-ffffffff8135a0a4: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff813d4a60)
Location: mm/pgtable-generic.c:162
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff813d4a60-ffffffff813d4b04: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81409430)
Location: mm/pgtable-generic.c:164
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81409430-ffffffff814094dc: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81435c20)
Location: mm/pgtable-generic.c:165
Inline: False
Direct callers:
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81435c20-ffffffff81435ccc: pgtable_trans_huge_deposit (STB_GLOBAL)
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
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffff800010308320)
Location: mm/pgtable-generic.c:152
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffff800010308320-ffff8000103083a8: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c297c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1264
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/huge_memory.c (c0000000004407f0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1264
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (c000000000447b04)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1264
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (c000000000514570)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1264
Inline: True
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
<summary>In <code>aws</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8126aed0)
Location: mm/pgtable-generic.c:152
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8126aed0-ffffffff8126af55: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8125cf00)
Location: mm/pgtable-generic.c:152
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8125cf00-ffffffff8125cf85: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81268c70)
Location: mm/pgtable-generic.c:152
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81268c70-ffffffff81268cf5: pgtable_trans_huge_deposit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pgtable_trans_huge_deposit(struct mm_struct *mm, pmd_t *pmdp, pgtable_t pgtable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81278600)
Location: mm/pgtable-generic.c:152
Inline: False
Direct callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81278600-ffffffff81278685: pgtable_trans_huge_deposit (STB_GLOBAL)
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
