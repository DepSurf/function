# Function: <code>khugepaged_scan_pmd</code>

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
In mm/huge_memory.c (ffffffff811f4988)
Location: mm/huge_memory.c:2641
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
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
In mm/khugepaged.c (ffffffff8121bc4d)
Location: mm/khugepaged.c:1089
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/khugepaged.c (ffffffff8122cf93)
Location: mm/khugepaged.c:1091
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/khugepaged.c (ffffffff8123972c)
Location: mm/khugepaged.c:1092
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/khugepaged.c (ffffffff812583f7)
Location: mm/khugepaged.c:1098
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/khugepaged.c (ffffffff8127cdbd)
Location: mm/khugepaged.c:1098
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
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
In mm/khugepaged.c (ffffffff81291922)
Location: mm/khugepaged.c:1097
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int khugepaged_scan_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812abcb0)
Location: mm/khugepaged.c:1102
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff812abcb0-ffffffff812ac22d: khugepaged_scan_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int khugepaged_scan_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812bd4c0)
Location: mm/khugepaged.c:1115
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812bd4c0-ffffffff812bda3d: khugepaged_scan_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int khugepaged_scan_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812f2be0)
Location: mm/khugepaged.c:1197
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812f2be0-ffffffff812f3240: khugepaged_scan_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int khugepaged_scan_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812fd210)
Location: mm/khugepaged.c:1224
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812fd210-ffffffff812fd885: khugepaged_scan_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int khugepaged_scan_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81303f80)
Location: mm/khugepaged.c:1218
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff81303f80-ffffffff813045d3: khugepaged_scan_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int khugepaged_scan_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8134dcb0)
Location: mm/khugepaged.c:1222
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff8134dcb0-ffffffff8134e303: khugepaged_scan_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int khugepaged_scan_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c6f10)
Location: mm/khugepaged.c:1197
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff813c6f10-ffffffff813c76c5: khugepaged_scan_pmd (STB_LOCAL)
```
</details>
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
int khugepaged_scan_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffff80001035ea08)
Location: mm/khugepaged.c:1115
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffff80001035ea08-ffff80001035eefc: khugepaged_scan_pmd (STB_LOCAL)
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
int khugepaged_scan_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (c000000000447d40)
Location: mm/khugepaged.c:1115
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
c000000000447d40-c000000000448440: khugepaged_scan_pmd (STB_LOCAL)
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
int khugepaged_scan_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b5aa0)
Location: mm/khugepaged.c:1115
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812b5aa0-ffffffff812b601d: khugepaged_scan_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int khugepaged_scan_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812a6c90)
Location: mm/khugepaged.c:1115
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812a6c90-ffffffff812a7203: khugepaged_scan_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int khugepaged_scan_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b38b0)
Location: mm/khugepaged.c:1115
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812b38b0-ffffffff812b3e2d: khugepaged_scan_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int khugepaged_scan_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812c3cf0)
Location: mm/khugepaged.c:1115
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff812c3cf0-ffffffff812c42b8: khugepaged_scan_pmd (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
