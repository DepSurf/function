# Function: <code>hmm_vma_handle_pte</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812935e2)
Location: mm/hmm.c:486
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/hmm.c (ffffffff812a7b56)
Location: mm/hmm.c:504
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff812c4290)
Location: mm/hmm.c:522
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812c4290-ffffffff812c45f0: hmm_vma_handle_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff812d5c40)
Location: mm/hmm.c:454
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812d5c40-ffffffff812d604e: hmm_vma_handle_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff8130ae00)
Location: mm/hmm.c:221
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff8130ae00-ffffffff8130b0e3: hmm_vma_handle_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff81316cd0)
Location: mm/hmm.c:229
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff81316cd0-ffffffff81316fb0: hmm_vma_handle_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff8131cf10)
Location: mm/hmm.c:229
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff8131cf10-ffffffff8131d1d3: hmm_vma_handle_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff8136a250)
Location: mm/hmm.c:231
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff8136a250-ffffffff8136a564: hmm_vma_handle_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff813e83b0)
Location: mm/hmm.c:223
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff813e83b0-ffffffff813e870e: hmm_vma_handle_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff814702d0)
Location: mm/hmm.c:223
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff814702d0-ffffffff81470679: hmm_vma_handle_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hmm_vma_handle_pte(struct mm_walk *walk, long unsigned int addr, long unsigned int end, pmd_t *pmdp, pte_t *ptep, long unsigned int *hmm_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff814a4aa0)
Location: mm/hmm.c:223
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff814a4aa0-ffffffff814a4e60: hmm_vma_handle_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hmm_vma_handle_pte(struct mm_walk *walk, long unsigned int addr, long unsigned int end, pmd_t *pmdp, pte_t *ptep, long unsigned int *hmm_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff814d5b00)
Location: mm/hmm.c:223
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff814d5b00-ffffffff814d5f1e: hmm_vma_handle_pte (STB_LOCAL)
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
In mm/hmm.c (ffff80001037b750)
Location: mm/hmm.c:454
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/hmm.c (c05664f0)
Location: mm/hmm.c:454
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (c00000000046fe30)
Location: mm/hmm.c:454
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
c00000000046fe30-c000000000470448: hmm_vma_handle_pte.isra.0 (STB_LOCAL)
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
In mm/hmm.c (ffffffe000251f6e)
Location: mm/hmm.c:454
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff812ce220)
Location: mm/hmm.c:454
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812ce220-ffffffff812ce62e: hmm_vma_handle_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff812bf0a0)
Location: mm/hmm.c:454
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812bf0a0-ffffffff812bf3de: hmm_vma_handle_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff812cc030)
Location: mm/hmm.c:454
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812cc030-ffffffff812cc43e: hmm_vma_handle_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff812dcd70)
Location: mm/hmm.c:454
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812dcd70-ffffffff812dd19c: hmm_vma_handle_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
