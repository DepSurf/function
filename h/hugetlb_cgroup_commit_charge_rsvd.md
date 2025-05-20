# Function: <code>hugetlb_cgroup_commit_charge_rsvd</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hugetlb_cgroup_commit_charge_rsvd(int idx, long unsigned int nr_pages, struct hugetlb_cgroup *h_cg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff812ffae0)
Location: mm/hugetlb_cgroup.c:307
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff812ffae0-ffffffff812ffb0c: hugetlb_cgroup_commit_charge_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hugetlb_cgroup_commit_charge_rsvd(int idx, long unsigned int nr_pages, struct hugetlb_cgroup *h_cg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff8130be60)
Location: mm/hugetlb_cgroup.c:305
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff8130be60-ffffffff8130be8c: hugetlb_cgroup_commit_charge_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hugetlb_cgroup_commit_charge_rsvd(int idx, long unsigned int nr_pages, struct hugetlb_cgroup *h_cg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff81312460)
Location: mm/hugetlb_cgroup.c:305
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff81312460-ffffffff8131248c: hugetlb_cgroup_commit_charge_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hugetlb_cgroup_commit_charge_rsvd(int idx, long unsigned int nr_pages, struct hugetlb_cgroup *h_cg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff8135de30)
Location: mm/hugetlb_cgroup.c:305
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff8135de30-ffffffff8135de59: hugetlb_cgroup_commit_charge_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hugetlb_cgroup_commit_charge_rsvd(int idx, long unsigned int nr_pages, struct hugetlb_cgroup *h_cg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff813d8180)
Location: mm/hugetlb_cgroup.c:341
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff813d8180-ffffffff813d81e4: hugetlb_cgroup_commit_charge_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hugetlb_cgroup_commit_charge_rsvd(int idx, long unsigned int nr_pages, struct hugetlb_cgroup *h_cg, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff8145de00)
Location: mm/hugetlb_cgroup.c:341
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff8145de00-ffffffff8145de67: hugetlb_cgroup_commit_charge_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hugetlb_cgroup_commit_charge_rsvd(int idx, long unsigned int nr_pages, struct hugetlb_cgroup *h_cg, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff81493b20)
Location: mm/hugetlb_cgroup.c:339
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_hugetlb_folio
```
**Symbols:**

```
ffffffff81493b20-ffffffff81493b53: hugetlb_cgroup_commit_charge_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hugetlb_cgroup_commit_charge_rsvd(int idx, long unsigned int nr_pages, struct hugetlb_cgroup *h_cg, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff814c3470)
Location: mm/hugetlb_cgroup.c:333
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_hugetlb_folio
```
**Symbols:**

```
ffffffff814c3470-ffffffff814c3491: hugetlb_cgroup_commit_charge_rsvd (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
