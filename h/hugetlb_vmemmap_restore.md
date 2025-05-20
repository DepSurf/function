# Function: <code>hugetlb_vmemmap_restore</code>

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
int hugetlb_vmemmap_restore(const struct hstate *h, struct page *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb_vmemmap.c (0)
Location: mm/hugetlb_vmemmap.c:459
Inline: False
Direct callers:
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__update_and_free_page
```
**Symbols:**

```
ffffffff82067160-ffffffff8206717d: hugetlb_vmemmap_restore.cold (STB_LOCAL)
ffffffff81414530-ffffffff814145b7: hugetlb_vmemmap_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hugetlb_vmemmap_restore(const struct hstate *h, struct page *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb_vmemmap.c (0)
Location: mm/hugetlb_vmemmap.c:459
Inline: False
Direct callers:
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
```
**Symbols:**

```
ffffffff820e6a1c-ffffffff820e6a39: hugetlb_vmemmap_restore.cold (STB_LOCAL)
ffffffff81447a80-ffffffff81447b18: hugetlb_vmemmap_restore (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
