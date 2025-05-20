# Function: <code>hugetlb_cgroup_uncharge_folio_rsvd</code>

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
void hugetlb_cgroup_uncharge_folio_rsvd(int idx, long unsigned int nr_pages, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff8145dec0)
Location: mm/hugetlb_cgroup.c:391
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff8145dec0-ffffffff8145def0: hugetlb_cgroup_uncharge_folio_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hugetlb_cgroup_uncharge_folio_rsvd(int idx, long unsigned int nr_pages, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff81493bb0)
Location: mm/hugetlb_cgroup.c:387
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff81493bb0-ffffffff81493be0: hugetlb_cgroup_uncharge_folio_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hugetlb_cgroup_uncharge_folio_rsvd(int idx, long unsigned int nr_pages, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff814c34f0)
Location: mm/hugetlb_cgroup.c:381
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:free_huge_folio
```
**Symbols:**

```
ffffffff814c34f0-ffffffff814c3520: hugetlb_cgroup_uncharge_folio_rsvd (STB_GLOBAL)
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
