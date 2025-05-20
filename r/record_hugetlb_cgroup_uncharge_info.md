# Function: <code>record_hugetlb_cgroup_uncharge_info</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c3a2e)
Location: mm/hugetlb.c:262
Inline: True
Inline callers:
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff812cfe23)
Location: mm/hugetlb.c:278
Inline: True
Inline callers:
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
Direct callers:
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
**Symbols:**

```
ffffffff812cf760-ffffffff812cf7e9: record_hugetlb_cgroup_uncharge_info.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff812d63e0)
Location: mm/hugetlb.c:276
Inline: True
Direct callers:
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
**Symbols:**

```
ffffffff812d63e0-ffffffff812d6487: record_hugetlb_cgroup_uncharge_info.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131d2fd)
Location: mm/hugetlb.c:278
Inline: True
Inline callers:
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
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
In mm/hugetlb.c (ffffffff8138aeb1)
Location: mm/hugetlb.c:292
Inline: True
Inline callers:
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
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
In mm/hugetlb.c (ffffffff81407c1a)
Location: mm/hugetlb.c:438
Inline: True
Inline callers:
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
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
In mm/hugetlb.c (ffffffff8143b9da)
Location: mm/hugetlb.c:432
Inline: True
Inline callers:
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff814760ca)
Location: mm/hugetlb.c:465
Inline: True
Inline callers:
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
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
