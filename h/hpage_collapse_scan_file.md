# Function: <code>hpage_collapse_scan_file</code>

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
int hpage_collapse_scan_file(struct mm_struct *mm, long unsigned int addr, struct file *file, long unsigned int start, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2131
Inline: False
Direct callers:
  - mm/khugepaged.c:madvise_collapse
```
**Symbols:**

```
ffffffff8144a770-ffffffff8144ad2a: hpage_collapse_scan_file (STB_LOCAL)
ffffffff82067db5-ffffffff82067de5: hpage_collapse_scan_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hpage_collapse_scan_file(struct mm_struct *mm, long unsigned int addr, struct file *file, long unsigned int start, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2320
Inline: False
Direct callers:
  - mm/khugepaged.c:madvise_collapse
```
**Symbols:**

```
ffffffff814809b0-ffffffff81480f30: hpage_collapse_scan_file (STB_LOCAL)
ffffffff820e77da-ffffffff820e7809: hpage_collapse_scan_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hpage_collapse_scan_file(struct mm_struct *mm, long unsigned int addr, struct file *file, long unsigned int start, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2218
Inline: False
Direct callers:
  - mm/khugepaged.c:madvise_collapse
```
**Symbols:**

```
ffffffff814ae990-ffffffff814aeefb: hpage_collapse_scan_file (STB_LOCAL)
ffffffff821c43b3-ffffffff821c43e2: hpage_collapse_scan_file.cold (STB_LOCAL)
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
