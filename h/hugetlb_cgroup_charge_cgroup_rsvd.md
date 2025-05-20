# Function: <code>hugetlb_cgroup_charge_cgroup_rsvd</code>

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
int hugetlb_cgroup_charge_cgroup_rsvd(int idx, long unsigned int nr_pages, struct hugetlb_cgroup **ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff812ffa90)
Location: mm/hugetlb_cgroup.c:282
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff812ffa90-ffffffff812ffaa5: hugetlb_cgroup_charge_cgroup_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hugetlb_cgroup_charge_cgroup_rsvd(int idx, long unsigned int nr_pages, struct hugetlb_cgroup **ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff8130be10)
Location: mm/hugetlb_cgroup.c:280
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff8130be10-ffffffff8130be25: hugetlb_cgroup_charge_cgroup_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hugetlb_cgroup_charge_cgroup_rsvd(int idx, long unsigned int nr_pages, struct hugetlb_cgroup **ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff81312410)
Location: mm/hugetlb_cgroup.c:280
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff81312410-ffffffff81312425: hugetlb_cgroup_charge_cgroup_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hugetlb_cgroup_charge_cgroup_rsvd(int idx, long unsigned int nr_pages, struct hugetlb_cgroup **ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff8135dde0)
Location: mm/hugetlb_cgroup.c:280
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff8135dde0-ffffffff8135ddf5: hugetlb_cgroup_charge_cgroup_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hugetlb_cgroup_charge_cgroup_rsvd(int idx, long unsigned int nr_pages, struct hugetlb_cgroup **ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff813d80d0)
Location: mm/hugetlb_cgroup.c:306
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff813d80d0-ffffffff813d80f1: hugetlb_cgroup_charge_cgroup_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hugetlb_cgroup_charge_cgroup_rsvd(int idx, long unsigned int nr_pages, struct hugetlb_cgroup **ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff8145dd20)
Location: mm/hugetlb_cgroup.c:304
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff8145dd20-ffffffff8145dd41: hugetlb_cgroup_charge_cgroup_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hugetlb_cgroup_charge_cgroup_rsvd(int idx, long unsigned int nr_pages, struct hugetlb_cgroup **ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff81493a10)
Location: mm/hugetlb_cgroup.c:304
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_hugetlb_folio
```
**Symbols:**

```
ffffffff81493a10-ffffffff81493a31: hugetlb_cgroup_charge_cgroup_rsvd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hugetlb_cgroup_charge_cgroup_rsvd(int idx, long unsigned int nr_pages, struct hugetlb_cgroup **ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff814c3370)
Location: mm/hugetlb_cgroup.c:298
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_hugetlb_folio
```
**Symbols:**

```
ffffffff814c3370-ffffffff814c3391: hugetlb_cgroup_charge_cgroup_rsvd (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
