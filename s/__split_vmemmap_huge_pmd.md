# Function: <code>__split_vmemmap_huge_pmd</code>

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
int __split_vmemmap_huge_pmd(pmd_t *pmd, long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8139bc90)
Location: mm/sparse-vmemmap.c:57
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_range
```
**Symbols:**

```
ffffffff8139bc90-ffffffff8139bee5: __split_vmemmap_huge_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __split_vmemmap_huge_pmd(pmd_t *pmd, long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_vmemmap.c (ffffffff81413570)
Location: mm/hugetlb_vmemmap.c:39
Inline: False
Direct callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
**Symbols:**

```
ffffffff81413570-ffffffff814137e2: __split_vmemmap_huge_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __split_vmemmap_huge_pmd(pmd_t *pmd, long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_vmemmap.c (ffffffff81446ad0)
Location: mm/hugetlb_vmemmap.c:39
Inline: False
Direct callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
**Symbols:**

```
ffffffff81446ad0-ffffffff81446d3a: __split_vmemmap_huge_pmd (STB_LOCAL)
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
