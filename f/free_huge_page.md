# Function: <code>free_huge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811db740)
Location: mm/hugetlb.c:1204
Inline: False
```
**Symbols:**

```
ffffffff811db740-ffffffff811db985: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811f99f0)
Location: mm/hugetlb.c:1230
Inline: False
```
**Symbols:**

```
ffffffff811f99f0-ffffffff811f9bf2: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120a2c0)
Location: mm/hugetlb.c:1230
Inline: False
```
**Symbols:**

```
ffffffff8120a2c0-ffffffff8120a4c2: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812157c0)
Location: mm/hugetlb.c:1248
Inline: False
```
**Symbols:**

```
ffffffff812157c0-ffffffff812159c2: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812303d0)
Location: mm/hugetlb.c:1254
Inline: False
```
**Symbols:**

```
ffffffff812303d0-ffffffff812305d2: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812537e0)
Location: mm/hugetlb.c:1239
Inline: False
```
**Symbols:**

```
ffffffff812537e0-ffffffff81253a4e: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81267720)
Location: mm/hugetlb.c:1239
Inline: False
```
**Symbols:**

```
ffffffff81267720-ffffffff81267992: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812832f0)
Location: mm/hugetlb.c:1259
Inline: False
```
**Symbols:**

```
ffffffff812832f0-ffffffff81283510: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81292ee0)
Location: mm/hugetlb.c:1350
Inline: True
```
**Symbols:**

```
ffffffff81292ee0-ffffffff81292f2f: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c6790)
Location: mm/hugetlb.c:1491
Inline: False
```
**Symbols:**

```
ffffffff812c6790-ffffffff812c67df: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d2390)
Location: mm/hugetlb.c:1518
Inline: False
```
**Symbols:**

```
ffffffff812d2390-ffffffff812d23df: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d8cd0)
Location: mm/hugetlb.c:1420
Inline: False
```
**Symbols:**

```
ffffffff812d8cd0-ffffffff812d8e87: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:1575
Inline: False
Direct callers:
  - mm/hugetlb.c:gather_surplus_pages
```
**Symbols:**

```
ffffffff81cbf5bf-ffffffff81cbf632: free_huge_page.cold (STB_LOCAL)
ffffffff8131eed0-ffffffff8131f0fb: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:1665
Inline: False
Direct callers:
  - mm/hugetlb.c:gather_surplus_pages
```
**Symbols:**

```
ffffffff81e7194a-ffffffff81e719bd: free_huge_page.cold (STB_LOCAL)
ffffffff8138b810-ffffffff8138bb06: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:1854
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
ffffffff8206634a-ffffffff820663ba: free_huge_page.cold (STB_LOCAL)
ffffffff81408f60-ffffffff8140920b: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:1877
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_surplus_hugetlb_folio
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
ffffffff820e5afc-ffffffff820e5b6c: free_huge_page.cold (STB_LOCAL)
ffffffff8143c5d0-ffffffff8143c87b: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010330a40)
Location: mm/hugetlb.c:1350
Inline: True
```
**Symbols:**

```
ffff800010330a40-ffff800010330ac4: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000409860)
Location: mm/hugetlb.c:1350
Inline: True
```
**Symbols:**

```
c000000000409860-c000000000409900: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022dc66)
Location: mm/hugetlb.c:1350
Inline: True
```
**Symbols:**

```
ffffffe00022dc66-ffffffe00022dcde: free_huge_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128b4c0)
Location: mm/hugetlb.c:1350
Inline: True
```
**Symbols:**

```
ffffffff8128b4c0-ffffffff8128b50f: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127d2f0)
Location: mm/hugetlb.c:1350
Inline: True
```
**Symbols:**

```
ffffffff8127d2f0-ffffffff8127d33f: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812892d0)
Location: mm/hugetlb.c:1350
Inline: True
```
**Symbols:**

```
ffffffff812892d0-ffffffff8128931f: free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812990b0)
Location: mm/hugetlb.c:1350
Inline: True
```
**Symbols:**

```
ffffffff812990b0-ffffffff812990ff: free_huge_page (STB_GLOBAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
