# Function: <code>vmemmap_remap_free</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vmemmap_remap_free(long unsigned int start, long unsigned int end, long unsigned int reuse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8132c5d0)
Location: mm/sparse-vmemmap.c:277
Inline: False
Direct callers:
  - mm/hugetlb_vmemmap.c:free_huge_page_vmemmap
```
**Symbols:**

```
ffffffff8132c5d0-ffffffff8132c7cd: vmemmap_remap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vmemmap_remap_free(long unsigned int start, long unsigned int end, long unsigned int reuse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8139c660)
Location: mm/sparse-vmemmap.c:324
Inline: False
Direct callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_free
```
**Symbols:**

```
ffffffff8139c660-ffffffff8139c839: vmemmap_remap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vmemmap_remap_free(long unsigned int start, long unsigned int end, long unsigned int reuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_vmemmap.c (ffffffff81413c00)
Location: mm/hugetlb_vmemmap.c:317
Inline: False
Direct callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize
```
**Symbols:**

```
ffffffff81413c00-ffffffff81413e44: vmemmap_remap_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vmemmap_remap_free(long unsigned int start, long unsigned int end, long unsigned int reuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_vmemmap.c (ffffffff81447300)
Location: mm/hugetlb_vmemmap.c:317
Inline: False
Direct callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize
```
**Symbols:**

```
ffffffff81447300-ffffffff81447544: vmemmap_remap_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb_vmemmap.c (ffffffff814807c4)
Location: mm/hugetlb_vmemmap.c:313
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
