# Function: <code>want_pmd_share</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool want_pmd_share(struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812dc8c3)
Location: mm/hugetlb.c:5601
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
**Symbols:**

```
ffffffff812dab90-ffffffff812dabd8: want_pmd_share (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool want_pmd_share(struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81323a8e)
Location: mm/hugetlb.c:5938
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
**Symbols:**

```
ffffffff81321ba0-ffffffff81321be8: want_pmd_share (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool want_pmd_share(struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8139167c)
Location: mm/hugetlb.c:6664
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
**Symbols:**

```
ffffffff8138ecb0-ffffffff8138ed13: want_pmd_share (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool want_pmd_share(struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8140d790)
Location: mm/hugetlb.c:6998
Inline: False
Direct callers:
  - mm/hugetlb.c:huge_pte_alloc
```
**Symbols:**

```
ffffffff8140d790-ffffffff8140d7eb: want_pmd_share (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool want_pmd_share(struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81440b40)
Location: mm/hugetlb.c:7093
Inline: False
Direct callers:
  - mm/hugetlb.c:huge_pte_alloc
```
**Symbols:**

```
ffffffff81440b40-ffffffff81440b9b: want_pmd_share (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool want_pmd_share(struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8147ac70)
Location: mm/hugetlb.c:7230
Inline: False
Direct callers:
  - mm/hugetlb.c:huge_pte_alloc
```
**Symbols:**

```
ffffffff8147ac70-ffffffff8147accb: want_pmd_share (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
