# Function: <code>add_reservation_in_range</code>

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
long int add_reservation_in_range(struct resv_map *resv, long int f, long int t, struct hugetlb_cgroup *h_cg, struct hstate *h, long int *regions_needed, bool count_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c3940)
Location: mm/hugetlb.c:333
Inline: False
Direct callers:
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_add
  - mm/hugetlb.c:region_add
```
**Symbols:**

```
ffffffff812c3940-ffffffff812c3c15: add_reservation_in_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int add_reservation_in_range(struct resv_map *resv, long int f, long int t, struct hugetlb_cgroup *h_cg, struct hstate *h, long int *regions_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812cfd00)
Location: mm/hugetlb.c:368
Inline: False
Direct callers:
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_add
  - mm/hugetlb.c:region_add
```
**Symbols:**

```
ffffffff812cfd00-ffffffff812cff71: add_reservation_in_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int add_reservation_in_range(struct resv_map *resv, long int f, long int t, struct hugetlb_cgroup *h_cg, struct hstate *h, long int *regions_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d6bd0)
Location: mm/hugetlb.c:384
Inline: False
Direct callers:
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_add
  - mm/hugetlb.c:region_add
```
**Symbols:**

```
ffffffff812d6bd0-ffffffff812d6dd2: add_reservation_in_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int add_reservation_in_range(struct resv_map *resv, long int f, long int t, struct hugetlb_cgroup *h_cg, struct hstate *h, long int *regions_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:386
Inline: False
Direct callers:
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_add
  - mm/hugetlb.c:region_add
```
**Symbols:**

```
ffffffff8131d1a0-ffffffff8131d5b6: add_reservation_in_range (STB_LOCAL)
ffffffff81cbf3e3-ffffffff81cbf451: add_reservation_in_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int add_reservation_in_range(struct resv_map *resv, long int f, long int t, struct hugetlb_cgroup *h_cg, struct hstate *h, long int *regions_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:399
Inline: False
Direct callers:
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_add
  - mm/hugetlb.c:region_add
```
**Symbols:**

```
ffffffff8138abd0-ffffffff8138b049: add_reservation_in_range (STB_LOCAL)
ffffffff81e71873-ffffffff81e718e2: add_reservation_in_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int add_reservation_in_range(struct resv_map *resv, long int f, long int t, struct hugetlb_cgroup *h_cg, struct hstate *h, long int *regions_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:545
Inline: False
Direct callers:
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_add
  - mm/hugetlb.c:region_add
```
**Symbols:**

```
ffffffff81407940-ffffffff81407da7: add_reservation_in_range (STB_LOCAL)
ffffffff82066225-ffffffff8206626c: add_reservation_in_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int add_reservation_in_range(struct resv_map *resv, long int f, long int t, struct hugetlb_cgroup *h_cg, struct hstate *h, long int *regions_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:539
Inline: False
Direct callers:
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_add
  - mm/hugetlb.c:region_add
```
**Symbols:**

```
ffffffff8143b700-ffffffff8143bb66: add_reservation_in_range (STB_LOCAL)
ffffffff820e5a21-ffffffff820e5a97: add_reservation_in_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int add_reservation_in_range(struct resv_map *resv, long int f, long int t, struct hugetlb_cgroup *h_cg, struct hstate *h, long int *regions_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:572
Inline: False
Direct callers:
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_add
  - mm/hugetlb.c:region_add
```
**Symbols:**

```
ffffffff81475df0-ffffffff81476256: add_reservation_in_range (STB_LOCAL)
ffffffff821c2b3f-ffffffff821c2bb5: add_reservation_in_range.cold (STB_LOCAL)
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
<b>Param removed. </b>
<code>bool count_only</code>
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
