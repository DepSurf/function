# Function: <code>hugetlb_cgroup_uncharge_file_region</code>

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
void hugetlb_cgroup_uncharge_file_region(struct resv_map *resv, struct file_region *rg, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff812ffca0)
Location: mm/hugetlb_cgroup.c:394
Inline: False
Direct callers:
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
```
**Symbols:**

```
ffffffff812ffca0-ffffffff812ffd23: hugetlb_cgroup_uncharge_file_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hugetlb_cgroup_uncharge_file_region(struct resv_map *resv, struct file_region *rg, long unsigned int nr_pages, bool region_del);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff8130c030)
Location: mm/hugetlb_cgroup.c:392
Inline: False
Direct callers:
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
```
**Symbols:**

```
ffffffff8130c030-ffffffff8130c0cf: hugetlb_cgroup_uncharge_file_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hugetlb_cgroup_uncharge_file_region(struct resv_map *resv, struct file_region *rg, long unsigned int nr_pages, bool region_del);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff81312630)
Location: mm/hugetlb_cgroup.c:392
Inline: False
Direct callers:
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
```
**Symbols:**

```
ffffffff81312630-ffffffff813126cf: hugetlb_cgroup_uncharge_file_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hugetlb_cgroup_uncharge_file_region(struct resv_map *resv, struct file_region *rg, long unsigned int nr_pages, bool region_del);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff8135e090)
Location: mm/hugetlb_cgroup.c:392
Inline: False
Direct callers:
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
```
**Symbols:**

```
ffffffff8135e090-ffffffff8135e12c: hugetlb_cgroup_uncharge_file_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hugetlb_cgroup_uncharge_file_region(struct resv_map *resv, struct file_region *rg, long unsigned int nr_pages, bool region_del);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff813d84a0)
Location: mm/hugetlb_cgroup.c:437
Inline: False
Direct callers:
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
```
**Symbols:**

```
ffffffff813d84a0-ffffffff813d855c: hugetlb_cgroup_uncharge_file_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hugetlb_cgroup_uncharge_file_region(struct resv_map *resv, struct file_region *rg, long unsigned int nr_pages, bool region_del);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff8145e180)
Location: mm/hugetlb_cgroup.c:439
Inline: False
Direct callers:
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
```
**Symbols:**

```
ffffffff8145e180-ffffffff8145e23c: hugetlb_cgroup_uncharge_file_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hugetlb_cgroup_uncharge_file_region(struct resv_map *resv, struct file_region *rg, long unsigned int nr_pages, bool region_del);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff81493e70)
Location: mm/hugetlb_cgroup.c:435
Inline: False
Direct callers:
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
```
**Symbols:**

```
ffffffff81493e70-ffffffff81493f2c: hugetlb_cgroup_uncharge_file_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hugetlb_cgroup_uncharge_file_region(struct resv_map *resv, struct file_region *rg, long unsigned int nr_pages, bool region_del);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff814c3750)
Location: mm/hugetlb_cgroup.c:426
Inline: False
Direct callers:
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
```
**Symbols:**

```
ffffffff814c3750-ffffffff814c380c: hugetlb_cgroup_uncharge_file_region (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool region_del</code>
</li>
</ul>
</details>
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
