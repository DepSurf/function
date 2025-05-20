# Function: <code>collapse_file</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void collapse_file(struct mm_struct *mm, struct file *file, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812bbe10)
Location: mm/khugepaged.c:1492
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812bbe10-ffffffff812bcd53: collapse_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void collapse_file(struct mm_struct *mm, struct file *file, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812f1310)
Location: mm/khugepaged.c:1608
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
**Symbols:**

```
ffffffff812f1310-ffffffff812f2185: collapse_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void collapse_file(struct mm_struct *mm, struct file *file, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812fd890)
Location: mm/khugepaged.c:1645
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
**Symbols:**

```
ffffffff812fd890-ffffffff812fe636: collapse_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void collapse_file(struct mm_struct *mm, struct file *file, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813045e0)
Location: mm/khugepaged.c:1634
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
**Symbols:**

```
ffffffff813045e0-ffffffff813052b7: collapse_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void collapse_file(struct mm_struct *mm, struct file *file, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8134e310)
Location: mm/khugepaged.c:1638
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
**Symbols:**

```
ffffffff8134e310-ffffffff8134f103: collapse_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void collapse_file(struct mm_struct *mm, struct file *file, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c4a10)
Location: mm/khugepaged.c:1632
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
**Symbols:**

```
ffffffff813c4a10-ffffffff813c5d0f: collapse_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int collapse_file(struct mm_struct *mm, long unsigned int addr, struct file *file, long unsigned int start, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814492e0)
Location: mm/khugepaged.c:1759
Inline: False
Direct callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
**Symbols:**

```
ffffffff814492e0-ffffffff8144a75e: collapse_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int collapse_file(struct mm_struct *mm, long unsigned int addr, struct file *file, long unsigned int start, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8147f420)
Location: mm/khugepaged.c:1895
Inline: False
Direct callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
**Symbols:**

```
ffffffff8147f420-ffffffff8148099d: collapse_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int collapse_file(struct mm_struct *mm, long unsigned int addr, struct file *file, long unsigned int start, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:1791
Inline: False
Direct callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
**Symbols:**

```
ffffffff814ad450-ffffffff814ae980: collapse_file (STB_LOCAL)
ffffffff821c4392-ffffffff821c43b3: collapse_file.cold (STB_LOCAL)
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
void collapse_file(struct mm_struct *mm, struct file *file, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffff80001035d130)
Location: mm/khugepaged.c:1492
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffff80001035d130-ffff80001035e140: collapse_file (STB_LOCAL)
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
void collapse_file(struct mm_struct *mm, struct file *file, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (c000000000448440)
Location: mm/khugepaged.c:1492
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
c000000000448440-c0000000004499d8: collapse_file (STB_LOCAL)
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
void collapse_file(struct mm_struct *mm, struct file *file, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b43f0)
Location: mm/khugepaged.c:1492
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812b43f0-ffffffff812b5333: collapse_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void collapse_file(struct mm_struct *mm, struct file *file, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812a5470)
Location: mm/khugepaged.c:1492
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812a5470-ffffffff812a6364: collapse_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void collapse_file(struct mm_struct *mm, struct file *file, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b2200)
Location: mm/khugepaged.c:1492
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812b2200-ffffffff812b3143: collapse_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void collapse_file(struct mm_struct *mm, struct file *file, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812c2600)
Location: mm/khugepaged.c:1492
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff812c2600-ffffffff812c3592: collapse_file (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>long unsigned int addr</code>
</li>
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
<code>mm, file, start, hpage, node</code> ➡️ <code>mm, addr, file, start, cc</code>
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
