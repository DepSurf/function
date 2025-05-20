# Function: <code>numa_migrate_prep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bf6e3)
Location: mm/memory.c:3134
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811db429)
Location: mm/memory.c:3328
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811eaf79)
Location: mm/memory.c:3367
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In mm/memory.c (ffffffff811f605f)
Location: mm/memory.c:3571
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
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
In mm/memory.c (ffffffff8120dcc9)
Location: mm/memory.c:3740
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
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
In mm/memory.c (ffffffff8122e769)
Location: mm/memory.c:3785
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
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
In mm/memory.c (ffffffff81242671)
Location: mm/memory.c:3575
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
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
In mm/memory.c (ffffffff81251473)
Location: mm/memory.c:3624
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
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
In mm/memory.c (ffffffff8125fa23)
Location: mm/memory.c:3649
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128fedb)
Location: mm/memory.c:4010
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129a95b)
Location: mm/memory.c:4170
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129fe3b)
Location: mm/memory.c:4178
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int numa_migrate_prep(struct page *page, struct vm_area_struct *vma, long unsigned int addr, int page_nid, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e3120)
Location: mm/memory.c:4325
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff812e3120-ffffffff812e3163: numa_migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int numa_migrate_prep(struct page *page, struct vm_area_struct *vma, long unsigned int addr, int page_nid, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81344460)
Location: mm/memory.c:4658
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81344460-ffffffff813444e1: numa_migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int numa_migrate_prep(struct page *page, struct vm_area_struct *vma, long unsigned int addr, int page_nid, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bc5b0)
Location: mm/memory.c:4661
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff813bc5b0-ffffffff813bc622: numa_migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int numa_migrate_prep(struct page *page, struct vm_area_struct *vma, long unsigned int addr, int page_nid, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f0f70)
Location: mm/memory.c:4685
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff813f0f70-ffffffff813f103d: numa_migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int numa_migrate_prep(struct folio *folio, struct vm_area_struct *vma, long unsigned int addr, int page_nid, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141bca0)
Location: mm/memory.c:4903
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff8141bca0-ffffffff8141bd21: numa_migrate_prep (STB_GLOBAL)
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
In mm/memory.c (ffff8000102fa178)
Location: mm/memory.c:3649
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
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
Location: mm/memory.c:3649
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003bf518)
Location: mm/memory.c:3649
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
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
Location: mm/memory.c:3649
Inline: True
```
</details>
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
In mm/memory.c (ffffffff81258073)
Location: mm/memory.c:3649
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
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
In mm/memory.c (ffffffff8124db22)
Location: mm/memory.c:3649
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
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
In mm/memory.c (ffffffff81255e13)
Location: mm/memory.c:3649
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
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
In mm/memory.c (ffffffff812658a1)
Location: mm/memory.c:3649
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
