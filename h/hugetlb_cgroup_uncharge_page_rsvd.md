# Function: <code>hugetlb_cgroup_uncharge_page_rsvd</code>

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
void hugetlb_cgroup_uncharge_page_rsvd(int idx, long unsigned int nr_pages, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff812ffb30)
Location: mm/hugetlb_cgroup.c:346
Inline: False
Direct callers:
  - mm/hugetlb.c:__free_huge_page
```
**Symbols:**

```
ffffffff812ffb30-ffffffff812ffb4b: hugetlb_cgroup_uncharge_page_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hugetlb_cgroup_uncharge_page_rsvd(int idx, long unsigned int nr_pages, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff8130beb0)
Location: mm/hugetlb_cgroup.c:344
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
**Symbols:**

```
ffffffff8130beb0-ffffffff8130becb: hugetlb_cgroup_uncharge_page_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hugetlb_cgroup_uncharge_page_rsvd(int idx, long unsigned int nr_pages, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff813124b0)
Location: mm/hugetlb_cgroup.c:344
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff813124b0-ffffffff813124cb: hugetlb_cgroup_uncharge_page_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hugetlb_cgroup_uncharge_page_rsvd(int idx, long unsigned int nr_pages, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff8135de80)
Location: mm/hugetlb_cgroup.c:344
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff8135de80-ffffffff8135de98: hugetlb_cgroup_uncharge_page_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hugetlb_cgroup_uncharge_page_rsvd(int idx, long unsigned int nr_pages, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff813d8220)
Location: mm/hugetlb_cgroup.c:389
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff813d8220-ffffffff813d8250: hugetlb_cgroup_uncharge_page_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
</ul>
