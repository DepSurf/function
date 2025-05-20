# Function: <code>alloc_charge_hpage</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int alloc_charge_hpage(struct page **hpage, struct mm_struct *mm, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:958
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81447d90-ffffffff8144802f: alloc_charge_hpage (STB_LOCAL)
ffffffff82067d3b-ffffffff82067d4f: alloc_charge_hpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int alloc_charge_hpage(struct page **hpage, struct mm_struct *mm, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:1064
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8147d740-ffffffff8147da04: alloc_charge_hpage (STB_LOCAL)
ffffffff820e7662-ffffffff820e7676: alloc_charge_hpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int alloc_charge_hpage(struct page **hpage, struct mm_struct *mm, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:1058
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff814abb10-ffffffff814abd18: alloc_charge_hpage (STB_LOCAL)
ffffffff821c4300-ffffffff821c4314: alloc_charge_hpage.cold (STB_LOCAL)
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
