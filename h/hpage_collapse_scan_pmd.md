# Function: <code>hpage_collapse_scan_pmd</code>

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
int hpage_collapse_scan_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, bool *mmap_locked, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:1128
Inline: False
Direct callers:
  - mm/khugepaged.c:madvise_collapse
```
**Symbols:**

```
ffffffff8144ad40-ffffffff8144b6ab: hpage_collapse_scan_pmd (STB_LOCAL)
ffffffff82067de5-ffffffff82067f1f: hpage_collapse_scan_pmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hpage_collapse_scan_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, bool *mmap_locked, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:1246
Inline: False
Direct callers:
  - mm/khugepaged.c:madvise_collapse
```
**Symbols:**

```
ffffffff8147eae0-ffffffff8147f407: hpage_collapse_scan_pmd (STB_LOCAL)
ffffffff820e76d6-ffffffff820e77da: hpage_collapse_scan_pmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hpage_collapse_scan_pmd(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, bool *mmap_locked, struct collapse_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:1247
Inline: False
Direct callers:
  - mm/khugepaged.c:madvise_collapse
```
**Symbols:**

```
ffffffff814af7c0-ffffffff814aff1b: hpage_collapse_scan_pmd (STB_LOCAL)
ffffffff821c43e2-ffffffff821c4502: hpage_collapse_scan_pmd.cold (STB_LOCAL)
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
