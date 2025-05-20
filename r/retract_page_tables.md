# Function: <code>retract_page_tables</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8121ae9d)
Location: mm/khugepaged.c:1238
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/khugepaged.c (ffffffff8122caf0)
Location: mm/khugepaged.c:1240
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/khugepaged.c (ffffffff8123912a)
Location: mm/khugepaged.c:1241
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/khugepaged.c (ffffffff81257839)
Location: mm/khugepaged.c:1247
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/khugepaged.c (ffffffff8127ba78)
Location: mm/khugepaged.c:1247
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/khugepaged.c (ffffffff8128fdb4)
Location: mm/khugepaged.c:1246
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/khugepaged.c (ffffffff812aafa9)
Location: mm/khugepaged.c:1251
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/khugepaged.c (ffffffff812bc938)
Location: mm/khugepaged.c:1417
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void retract_page_tables(struct address_space *mapping, long unsigned int pgoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812f10a0)
Location: mm/khugepaged.c:1529
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff812f10a0-ffffffff812f1303: retract_page_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void retract_page_tables(struct address_space *mapping, long unsigned int pgoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812fc6f0)
Location: mm/khugepaged.c:1560
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff812fc6f0-ffffffff812fc9a5: retract_page_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void retract_page_tables(struct address_space *mapping, long unsigned int pgoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81303460)
Location: mm/khugepaged.c:1549
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81303460-ffffffff81303712: retract_page_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void retract_page_tables(struct address_space *mapping, long unsigned int pgoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8134d1d0)
Location: mm/khugepaged.c:1553
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8134d1d0-ffffffff8134d47c: retract_page_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void retract_page_tables(struct address_space *mapping, long unsigned int pgoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c3c00)
Location: mm/khugepaged.c:1545
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff813c3c00-ffffffff813c3dca: retract_page_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int retract_page_tables(struct address_space *mapping, long unsigned int pgoff, struct mm_struct *target_mm, long unsigned int target_addr, struct page *hpage, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:1620
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81447aa0-ffffffff81447d7b: retract_page_tables (STB_LOCAL)
ffffffff82067cdf-ffffffff82067d3b: retract_page_tables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int retract_page_tables(struct address_space *mapping, long unsigned int pgoff, struct mm_struct *target_mm, long unsigned int target_addr, struct page *hpage, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:1751
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8147d3f0-ffffffff8147d727: retract_page_tables (STB_LOCAL)
ffffffff820e7606-ffffffff820e7662: retract_page_tables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void retract_page_tables(struct address_space *mapping, long unsigned int pgoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814acac0)
Location: mm/khugepaged.c:1682
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff814acac0-ffffffff814ace4a: retract_page_tables (STB_LOCAL)
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
In mm/khugepaged.c (ffff80001035db78)
Location: mm/khugepaged.c:1417
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (c0000000004491b4)
Location: mm/khugepaged.c:1417
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b4f18)
Location: mm/khugepaged.c:1417
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/khugepaged.c (ffffffff812a5f46)
Location: mm/khugepaged.c:1417
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/khugepaged.c (ffffffff812b2d28)
Location: mm/khugepaged.c:1417
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/khugepaged.c (ffffffff812c3165)
Location: mm/khugepaged.c:1417
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mm_struct *target_mm</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int target_addr</code>
</li>
<li>
<b>Param added. </b>
<code>struct page *hpage</code>
</li>
<li>
<b>Param added. </b>
<code>struct collapse_control *cc</code>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mm_struct *target_mm</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int target_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *hpage</code>
</li>
<li>
<b>Param removed. </b>
<code>struct collapse_control *cc</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>
