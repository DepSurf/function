# Function: <code>enqueue_hugetlb_folio</code>

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
void enqueue_hugetlb_folio(struct hstate *h, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81405130)
Location: mm/hugetlb.c:1278
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:add_hugetlb_folio
```
**Symbols:**

```
ffffffff81405130-ffffffff814051a2: enqueue_hugetlb_folio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void enqueue_hugetlb_folio(struct hstate *h, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff814387b0)
Location: mm/hugetlb.c:1272
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:add_hugetlb_folio
```
**Symbols:**

```
ffffffff814387b0-ffffffff81438822: enqueue_hugetlb_folio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void enqueue_hugetlb_folio(struct hstate *h, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81474773)
Location: mm/hugetlb.c:1310
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_and_add_allocated_folios
Direct callers:
  - mm/hugetlb.c:prep_and_add_bootmem_folios
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:free_huge_folio
  - mm/hugetlb.c:add_hugetlb_folio
```
**Symbols:**

```
ffffffff81472140-ffffffff814721b2: enqueue_hugetlb_folio (STB_LOCAL)
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
