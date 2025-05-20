# Function: <code>dequeue_hugetlb_folio_nodemask</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct folio *dequeue_hugetlb_folio_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81438f90)
Location: mm/hugetlb.c:1310
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_hugetlb_folio_nodemask
  - mm/hugetlb.c:dequeue_hugetlb_folio_vma
  - mm/hugetlb.c:dequeue_hugetlb_folio_vma
```
**Symbols:**

```
ffffffff81438f90-ffffffff814393f7: dequeue_hugetlb_folio_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct folio *dequeue_hugetlb_folio_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81472ac0)
Location: mm/hugetlb.c:1348
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_hugetlb_folio_nodemask
  - mm/hugetlb.c:dequeue_hugetlb_folio_vma
  - mm/hugetlb.c:dequeue_hugetlb_folio_vma
```
**Symbols:**

```
ffffffff81472ac0-ffffffff81472f27: dequeue_hugetlb_folio_nodemask (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
