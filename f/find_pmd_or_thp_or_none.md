# Function: <code>find_pmd_or_thp_or_none</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int find_pmd_or_thp_or_none(struct mm_struct *mm, long unsigned int address, pmd_t **pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81447430)
Location: mm/khugepaged.c:854
Inline: False
Direct callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81447430-ffffffff81447543: find_pmd_or_thp_or_none (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int find_pmd_or_thp_or_none(struct mm_struct *mm, long unsigned int address, pmd_t **pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8147cb00)
Location: mm/khugepaged.c:947
Inline: False
Direct callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8147cb00-ffffffff8147cc13: find_pmd_or_thp_or_none (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int find_pmd_or_thp_or_none(struct mm_struct *mm, long unsigned int address, pmd_t **pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814ac1a0)
Location: mm/khugepaged.c:941
Inline: False
Direct callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff814ac1a0-ffffffff814ac2b3: find_pmd_or_thp_or_none (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
