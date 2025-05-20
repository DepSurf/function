# Function: <code>hmm_vma_walk_hole_</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff81291cf0)
Location: mm/hmm.c:345
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff81291cf0-ffffffff81291dd6: hmm_vma_walk_hole_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812a6ce0)
Location: mm/hmm.c:363
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff812a6ce0-ffffffff812a6dc6: hmm_vma_walk_hole_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812c3350)
Location: mm/hmm.c:342
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff812c3350-ffffffff812c3459: hmm_vma_walk_hole_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812d5340)
Location: mm/hmm.c:283
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff812d5340-ffffffff812d5486: hmm_vma_walk_hole_ (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffff80001037a690)
Location: mm/hmm.c:283
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
  - mm/hmm.c:hmm_vma_walk_hole
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffff80001037a690-ffff80001037a80c: hmm_vma_walk_hole_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c0565aec)
Location: mm/hmm.c:283
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
  - mm/hmm.c:hmm_vma_walk_hole
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
c0565aec-c0565c30: hmm_vma_walk_hole_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c00000000046eff0)
Location: mm/hmm.c:283
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
c00000000046eff0-c00000000046f1f0: hmm_vma_walk_hole_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffe000251ab0)
Location: mm/hmm.c:283
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffe000251ab0-ffffffe000251baa: hmm_vma_walk_hole_ (STB_LOCAL)
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
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cd920)
Location: mm/hmm.c:283
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff812cd920-ffffffff812cda66: hmm_vma_walk_hole_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812be790)
Location: mm/hmm.c:283
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff812be790-ffffffff812be8d6: hmm_vma_walk_hole_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cb730)
Location: mm/hmm.c:283
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff812cb730-ffffffff812cb876: hmm_vma_walk_hole_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hmm_vma_walk_hole_(long unsigned int addr, long unsigned int end, bool fault, bool write_fault, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812dc490)
Location: mm/hmm.c:283
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff812dc490-ffffffff812dc5d6: hmm_vma_walk_hole_ (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
