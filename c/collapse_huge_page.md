# Function: <code>collapse_huge_page</code>

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
In mm/huge_memory.c (ffffffff811f4d69)
Location: mm/huge_memory.c:2505
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void collapse_huge_page(struct mm_struct *mm, long unsigned int address, struct page **hpage, int node, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812199f0)
Location: mm/khugepaged.c:924
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff812199f0-ffffffff8121ab3c: collapse_huge_page (STB_LOCAL)
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
Location: mm/khugepaged.c:926
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void collapse_huge_page(struct mm_struct *mm, long unsigned int address, struct page **hpage, int node, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81237e90)
Location: mm/khugepaged.c:927
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81237e90-ffffffff81238b93: collapse_huge_page (STB_LOCAL)
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
Location: mm/khugepaged.c:933
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void collapse_huge_page(struct mm_struct *mm, long unsigned int address, struct page **hpage, int node, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8127bdc0)
Location: mm/khugepaged.c:933
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff8127bdc0-ffffffff8127cc4c: collapse_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void collapse_huge_page(struct mm_struct *mm, long unsigned int address, struct page **hpage, int node, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81290420)
Location: mm/khugepaged.c:934
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81290420-ffffffff81291327: collapse_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void collapse_huge_page(struct mm_struct *mm, long unsigned int address, struct page **hpage, int node, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812ab560)
Location: mm/khugepaged.c:934
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
**Symbols:**

```
ffffffff812ab560-ffffffff812abca1: collapse_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void collapse_huge_page(struct mm_struct *mm, long unsigned int address, struct page **hpage, int node, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812bcd60)
Location: mm/khugepaged.c:946
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
**Symbols:**

```
ffffffff812bcd60-ffffffff812bd4b6: collapse_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void collapse_huge_page(struct mm_struct *mm, long unsigned int address, struct page **hpage, int node, int referenced, int unmapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812f24d0)
Location: mm/khugepaged.c:1031
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
**Symbols:**

```
ffffffff812f24d0-ffffffff812f2bda: collapse_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void collapse_huge_page(struct mm_struct *mm, long unsigned int address, struct page **hpage, int node, int referenced, int unmapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812fc9b0)
Location: mm/khugepaged.c:1058
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
**Symbols:**

```
ffffffff812fc9b0-ffffffff812fd204: collapse_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void collapse_huge_page(struct mm_struct *mm, long unsigned int address, struct page **hpage, int node, int referenced, int unmapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81303720)
Location: mm/khugepaged.c:1055
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
**Symbols:**

```
ffffffff81303720-ffffffff81303f7c: collapse_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void collapse_huge_page(struct mm_struct *mm, long unsigned int address, struct page **hpage, int node, int referenced, int unmapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8134d480)
Location: mm/khugepaged.c:1059
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
**Symbols:**

```
ffffffff8134d480-ffffffff8134dcac: collapse_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void collapse_huge_page(struct mm_struct *mm, long unsigned int address, struct page **hpage, int node, int referenced, int unmapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c65d0)
Location: mm/khugepaged.c:1034
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
**Symbols:**

```
ffffffff813c65d0-ffffffff813c6f01: collapse_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int collapse_huge_page(struct mm_struct *mm, long unsigned int address, int referenced, int unmapped, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81448a40)
Location: mm/khugepaged.c:973
Inline: False
Direct callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
**Symbols:**

```
ffffffff81448a40-ffffffff814492c5: collapse_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int collapse_huge_page(struct mm_struct *mm, long unsigned int address, int referenced, int unmapped, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8147e290)
Location: mm/khugepaged.c:1086
Inline: False
Direct callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
**Symbols:**

```
ffffffff8147e290-ffffffff8147eac2: collapse_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int collapse_huge_page(struct mm_struct *mm, long unsigned int address, int referenced, int unmapped, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814aef10)
Location: mm/khugepaged.c:1083
Inline: False
Direct callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
**Symbols:**

```
ffffffff814aef10-ffffffff814af7ac: collapse_huge_page (STB_LOCAL)
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
void collapse_huge_page(struct mm_struct *mm, long unsigned int address, struct page **hpage, int node, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffff80001035e140)
Location: mm/khugepaged.c:946
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
**Symbols:**

```
ffff80001035e140-ffff80001035ea04: collapse_huge_page (STB_LOCAL)
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
void collapse_huge_page(struct mm_struct *mm, long unsigned int address, struct page **hpage, int node, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (c0000000004474a0)
Location: mm/khugepaged.c:946
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
**Symbols:**

```
c0000000004474a0-c000000000447d34: collapse_huge_page (STB_LOCAL)
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
void collapse_huge_page(struct mm_struct *mm, long unsigned int address, struct page **hpage, int node, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b5340)
Location: mm/khugepaged.c:946
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
**Symbols:**

```
ffffffff812b5340-ffffffff812b5a96: collapse_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void collapse_huge_page(struct mm_struct *mm, long unsigned int address, struct page **hpage, int node, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812a6370)
Location: mm/khugepaged.c:946
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
**Symbols:**

```
ffffffff812a6370-ffffffff812a6c8d: collapse_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void collapse_huge_page(struct mm_struct *mm, long unsigned int address, struct page **hpage, int node, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b3150)
Location: mm/khugepaged.c:946
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
**Symbols:**

```
ffffffff812b3150-ffffffff812b38a6: collapse_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void collapse_huge_page(struct mm_struct *mm, long unsigned int address, struct page **hpage, int node, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812c35a0)
Location: mm/khugepaged.c:946
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
**Symbols:**

```
ffffffff812c35a0-ffffffff812c3ce7: collapse_huge_page (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int unmapped</code>
</li>
</ul>
</details>
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
<code>struct collapse_control *cc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page **hpage</code>
</li>
<li>
<b>Param removed. </b>
<code>int node</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, address, hpage, node, referenced, unmapped</code> ➡️ <code>mm, address, referenced, unmapped, cc</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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
