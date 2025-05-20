# Function: <code>free_vmemmap_page_list</code>

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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8132c6a7)
Location: mm/sparse-vmemmap.c:223
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8139c725)
Location: mm/sparse-vmemmap.c:249
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_free
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb_vmemmap.c (ffffffff81413d25)
Location: mm/hugetlb_vmemmap.c:226
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb_vmemmap.c (ffffffff81447425)
Location: mm/hugetlb_vmemmap.c:226
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_vmemmap_page_list(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_vmemmap.c (ffffffff814803d0)
Location: mm/hugetlb_vmemmap.c:194
Inline: False
Direct callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize_folios
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize_folios
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize_folio
```
**Symbols:**

```
ffffffff814803d0-ffffffff81480444: free_vmemmap_page_list (STB_LOCAL)
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
</ul>
