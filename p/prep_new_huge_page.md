# Function: <code>prep_new_huge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void prep_new_huge_page(struct hstate *h, struct page *page, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811da1a0)
Location: mm/hugetlb.c:1251
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_init
```
**Symbols:**

```
ffffffff811da1a0-ffffffff811da21e: prep_new_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void prep_new_huge_page(struct hstate *h, struct page *page, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811f92f0)
Location: mm/hugetlb.c:1277
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
ffffffff811f92f0-ffffffff811f93af: prep_new_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void prep_new_huge_page(struct hstate *h, struct page *page, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120a620)
Location: mm/hugetlb.c:1277
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
ffffffff8120a620-ffffffff8120a6df: prep_new_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void prep_new_huge_page(struct hstate *h, struct page *page, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812159d0)
Location: mm/hugetlb.c:1295
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
ffffffff812159d0-ffffffff81215a62: prep_new_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void prep_new_huge_page(struct hstate *h, struct page *page, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812305e0)
Location: mm/hugetlb.c:1301
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
ffffffff812305e0-ffffffff8123069f: prep_new_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void prep_new_huge_page(struct hstate *h, struct page *page, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81252460)
Location: mm/hugetlb.c:1290
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
ffffffff81252460-ffffffff812524d3: prep_new_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void prep_new_huge_page(struct hstate *h, struct page *page, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812666c0)
Location: mm/hugetlb.c:1291
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
ffffffff812666c0-ffffffff81266735: prep_new_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff828d84c5)
Location: mm/hugetlb.c:1322
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff828e096c)
Location: mm/hugetlb.c:1370
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void prep_new_huge_page(struct hstate *h, struct page *page, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c47d0)
Location: mm/hugetlb.c:1511
Inline: False
Direct callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
ffffffff812c47d0-ffffffff812c4871: prep_new_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void prep_new_huge_page(struct hstate *h, struct page *page, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d0470)
Location: mm/hugetlb.c:1538
Inline: False
Direct callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
ffffffff812d0470-ffffffff812d051c: prep_new_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff831f4bea)
Location: mm/hugetlb.c:1503
Inline: True
Inline callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:alloc_fresh_huge_page
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
In mm/hugetlb.c (ffffffff832daeb5)
Location: mm/hugetlb.c:1659
Inline: True
Inline callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:alloc_fresh_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void prep_new_huge_page(struct hstate *h, struct page *page, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81389620)
Location: mm/hugetlb.c:1751
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
ffffffff81389620-ffffffff81389748: prep_new_huge_page (STB_LOCAL)
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void prep_new_huge_page(struct hstate *h, struct page *page, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff80001032ed50)
Location: mm/hugetlb.c:1370
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
ffff80001032ed50-ffff80001032ee40: prep_new_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void prep_new_huge_page(struct hstate *h, struct page *page, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000407430)
Location: mm/hugetlb.c:1370
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
c000000000407430-c000000000407564: prep_new_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe000018012)
Location: mm/hugetlb.c:1370
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff828c9820)
Location: mm/hugetlb.c:1370
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff828c1f45)
Location: mm/hugetlb.c:1370
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff828dc5a0)
Location: mm/hugetlb.c:1370
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff828e19bc)
Location: mm/hugetlb.c:1370
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
