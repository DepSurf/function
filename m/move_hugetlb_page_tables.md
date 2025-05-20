# Function: <code>move_hugetlb_page_tables</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int move_hugetlb_page_tables(struct vm_area_struct *vma, struct vm_area_struct *new_vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4931
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff81e72372-ffffffff81e723d0: move_hugetlb_page_tables.cold (STB_LOCAL)
ffffffff81392460-ffffffff813928d8: move_hugetlb_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int move_hugetlb_page_tables(struct vm_area_struct *vma, struct vm_area_struct *new_vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5171
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff82066ad2-ffffffff82066b5e: move_hugetlb_page_tables.cold (STB_LOCAL)
ffffffff8140f430-ffffffff8140f915: move_hugetlb_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int move_hugetlb_page_tables(struct vm_area_struct *vma, struct vm_area_struct *new_vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5257
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff820e62bc-ffffffff820e635a: move_hugetlb_page_tables.cold (STB_LOCAL)
ffffffff814427e0-ffffffff81442cd6: move_hugetlb_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int move_hugetlb_page_tables(struct vm_area_struct *vma, struct vm_area_struct *new_vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5512
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff821c3448-ffffffff821c34ea: move_hugetlb_page_tables.cold (STB_LOCAL)
ffffffff8147ca10-ffffffff8147ced1: move_hugetlb_page_tables (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
