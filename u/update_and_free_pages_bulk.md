# Function: <code>update_and_free_pages_bulk</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d7bd9)
Location: mm/hugetlb.c:1399
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:return_unused_surplus_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_and_free_pages_bulk(struct hstate *h, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131dad0)
Location: mm/hugetlb.c:1554
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
ffffffff8131dad0-ffffffff8131db23: update_and_free_pages_bulk (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff8138a635)
Location: mm/hugetlb.c:1644
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:return_unused_surplus_pages
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
In mm/hugetlb.c (ffffffff8140a01c)
Location: mm/hugetlb.c:1831
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:return_unused_surplus_pages
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
In mm/hugetlb.c (ffffffff8143d687)
Location: mm/hugetlb.c:1854
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:return_unused_surplus_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_and_free_pages_bulk(struct hstate *h, struct list_head *folio_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81473c40)
Location: mm/hugetlb.c:1920
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
ffffffff81473c40-ffffffff81473d44: update_and_free_pages_bulk (STB_LOCAL)
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
</ul>
