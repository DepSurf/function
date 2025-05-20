# Function: <code>hmm_range_need_fault</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff81293256)
Location: mm/hmm.c:404
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff81292920-ffffffff812929b8: hmm_range_need_fault.part.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff812a76c2)
Location: mm/hmm.c:422
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff812a7320-ffffffff812a73b8: hmm_range_need_fault.part.13 (STB_LOCAL)
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
In mm/hmm.c (ffffffff812c4ed8)
Location: mm/hmm.c:414
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff812c3810-ffffffff812c38c7: hmm_range_need_fault.part.0 (STB_LOCAL)
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
In mm/hmm.c (ffffffff812d6888)
Location: mm/hmm.c:357
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff812d5840-ffffffff812d58f7: hmm_range_need_fault.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int hmm_range_need_fault(const struct hmm_vma_walk *hmm_vma_walk, const long unsigned int *hmm_pfns, long unsigned int npages, long unsigned int cpu_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8130abd0)
Location: mm/hmm.c:118
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_test
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_handle_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff8130abd0-ffffffff8130ac4e: hmm_range_need_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int hmm_range_need_fault(const struct hmm_vma_walk *hmm_vma_walk, const long unsigned int *hmm_pfns, long unsigned int npages, long unsigned int cpu_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff81316aa0)
Location: mm/hmm.c:119
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_test
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_handle_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff81316aa0-ffffffff81316b1e: hmm_range_need_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int hmm_range_need_fault(const struct hmm_vma_walk *hmm_vma_walk, const long unsigned int *hmm_pfns, long unsigned int npages, long unsigned int cpu_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8131ccf0)
Location: mm/hmm.c:119
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_test
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff8131ccf0-ffffffff8131cd6c: hmm_range_need_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int hmm_range_need_fault(const struct hmm_vma_walk *hmm_vma_walk, const long unsigned int *hmm_pfns, long unsigned int npages, long unsigned int cpu_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8136a030)
Location: mm/hmm.c:121
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_test
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff8136a030-ffffffff8136a0ac: hmm_range_need_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int hmm_range_need_fault(const struct hmm_vma_walk *hmm_vma_walk, const long unsigned int *hmm_pfns, long unsigned int npages, long unsigned int cpu_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff813e7e50)
Location: mm/hmm.c:121
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_test
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff813e7e50-ffffffff813e7ef8: hmm_range_need_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int hmm_range_need_fault(const struct hmm_vma_walk *hmm_vma_walk, const long unsigned int *hmm_pfns, long unsigned int npages, long unsigned int cpu_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8146fd30)
Location: mm/hmm.c:121
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_test
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff8146fd30-ffffffff8146fdd8: hmm_range_need_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int hmm_range_need_fault(const struct hmm_vma_walk *hmm_vma_walk, const long unsigned int *hmm_pfns, long unsigned int npages, long unsigned int cpu_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff814a4510)
Location: mm/hmm.c:121
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_test
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff814a4510-ffffffff814a45a2: hmm_range_need_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int hmm_range_need_fault(const struct hmm_vma_walk *hmm_vma_walk, const long unsigned int *hmm_pfns, long unsigned int npages, long unsigned int cpu_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff814d5350)
Location: mm/hmm.c:121
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_test
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_handle_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff814d5350-ffffffff814d53e2: hmm_range_need_fault (STB_LOCAL)
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
In mm/hmm.c (ffff80001037b558)
Location: mm/hmm.c:357
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
  - mm/hmm.c:hmm_vma_walk_hole
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
In mm/hmm.c (c05662c0)
Location: mm/hmm.c:357
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hole
  - mm/hmm.c:hmm_vma_walk_hole
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
In mm/hmm.c (c000000000470740)
Location: mm/hmm.c:357
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
c00000000046f820-c00000000046f954: hmm_range_need_fault.part.0 (STB_LOCAL)
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
In mm/hmm.c (ffffffe000251e7a)
Location: mm/hmm.c:357
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hole
  - mm/hmm.c:hmm_vma_walk_hole
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
In mm/hmm.c (ffffffff812cee68)
Location: mm/hmm.c:357
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff812cde20-ffffffff812cded7: hmm_range_need_fault.part.0 (STB_LOCAL)
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
In mm/hmm.c (ffffffff812bfafb)
Location: mm/hmm.c:357
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff812bec90-ffffffff812bed47: hmm_range_need_fault.part.0 (STB_LOCAL)
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
In mm/hmm.c (ffffffff812ccc78)
Location: mm/hmm.c:357
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff812cbc30-ffffffff812cbce7: hmm_range_need_fault.part.0 (STB_LOCAL)
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
In mm/hmm.c (ffffffff812dda08)
Location: mm/hmm.c:357
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff812dc990-ffffffff812dca47: hmm_range_need_fault.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
