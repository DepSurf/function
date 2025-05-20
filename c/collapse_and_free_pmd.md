# Function: <code>collapse_and_free_pmd</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void collapse_and_free_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c3ae0)
Location: mm/khugepaged.c:1400
Inline: False
Direct callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
**Symbols:**

```
ffffffff813c3ae0-ffffffff813c3bf1: collapse_and_free_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void collapse_and_free_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81447290)
Location: mm/khugepaged.c:1399
Inline: False
Direct callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
**Symbols:**

```
ffffffff81447290-ffffffff81447413: collapse_and_free_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void collapse_and_free_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8147c970)
Location: mm/khugepaged.c:1522
Inline: False
Direct callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
**Symbols:**

```
ffffffff8147c970-ffffffff8147caed: collapse_and_free_pmd (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
