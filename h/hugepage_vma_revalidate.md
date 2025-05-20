# Function: <code>hugepage_vma_revalidate</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812195f0)
Location: mm/khugepaged.c:841
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812195f0-ffffffff8121966e: hugepage_vma_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8122bb70)
Location: mm/khugepaged.c:843
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff8122bb70-ffffffff8122bbee: hugepage_vma_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81237640)
Location: mm/khugepaged.c:842
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff81237640-ffffffff812376c1: hugepage_vma_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812569d0)
Location: mm/khugepaged.c:848
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff812569d0-ffffffff81256a51: hugepage_vma_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8127a9b0)
Location: mm/khugepaged.c:848
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff8127a9b0-ffffffff8127aa2e: hugepage_vma_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8128efb0)
Location: mm/khugepaged.c:848
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff8128efb0-ffffffff8128f032: hugepage_vma_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812a9880)
Location: mm/khugepaged.c:848
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff812a9880-ffffffff812a990b: hugepage_vma_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812badf0)
Location: mm/khugepaged.c:860
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff812badf0-ffffffff812bae7b: hugepage_vma_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812efc80)
Location: mm/khugepaged.c:942
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff812efc80-ffffffff812efd35: hugepage_vma_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812fb380)
Location: mm/khugepaged.c:969
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff812fb380-ffffffff812fb42f: hugepage_vma_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81302150)
Location: mm/khugepaged.c:967
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff81302150-ffffffff813021fa: hugepage_vma_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8134bfb0)
Location: mm/khugepaged.c:971
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff8134bfb0-ffffffff8134c05a: hugepage_vma_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c6210)
Location: mm/khugepaged.c:946
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff813c6210-ffffffff813c62d0: hugepage_vma_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, bool expect_anon, struct vm_area_struct **vmap, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:819
Inline: False
Direct callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81445fc0-ffffffff814460d2: hugepage_vma_revalidate (STB_LOCAL)
ffffffff82067cc1-ffffffff82067cdf: hugepage_vma_revalidate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, bool expect_anon, struct vm_area_struct **vmap, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:916
Inline: False
Direct callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8147b6a0-ffffffff8147b7b8: hugepage_vma_revalidate (STB_LOCAL)
ffffffff820e75e8-ffffffff820e7606: hugepage_vma_revalidate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, bool expect_anon, struct vm_area_struct **vmap, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:910
Inline: False
Direct callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff814abfc0-ffffffff814ac182: hugepage_vma_revalidate (STB_LOCAL)
ffffffff821c4314-ffffffff821c4332: hugepage_vma_revalidate.cold (STB_LOCAL)
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
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffff80001035be70)
Location: mm/khugepaged.c:860
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffff80001035be70-ffff80001035bf24: hugepage_vma_revalidate (STB_LOCAL)
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
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (c000000000445a70)
Location: mm/khugepaged.c:860
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
c000000000445a70-c000000000445b58: hugepage_vma_revalidate (STB_LOCAL)
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
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b33d0)
Location: mm/khugepaged.c:860
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff812b33d0-ffffffff812b345b: hugepage_vma_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812a4750)
Location: mm/khugepaged.c:860
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff812a4750-ffffffff812a47db: hugepage_vma_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b11e0)
Location: mm/khugepaged.c:860
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff812b11e0-ffffffff812b126b: hugepage_vma_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hugepage_vma_revalidate(struct mm_struct *mm, long unsigned int address, struct vm_area_struct **vmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812c1520)
Location: mm/khugepaged.c:860
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff812c1520-ffffffff812c15ab: hugepage_vma_revalidate (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool expect_anon</code>
</li>
<li>
<b>Param added. </b>
<code>struct collapse_control *cc</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, address, vmap</code> ➡️ <code>mm, address, expect_anon, vmap, cc</code>
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
