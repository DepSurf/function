# Function: <code>dequeue_huge_page_nodemask</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81214410)
Location: mm/hugetlb.c:890
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
```
**Symbols:**

```
ffffffff81214410-ffffffff8121463a: dequeue_huge_page_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8122efd0)
Location: mm/hugetlb.c:891
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
```
**Symbols:**

```
ffffffff8122efd0-ffffffff8122f1cb: dequeue_huge_page_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81251790)
Location: mm/hugetlb.c:883
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
```
**Symbols:**

```
ffffffff81251790-ffffffff812519a0: dequeue_huge_page_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81265b90)
Location: mm/hugetlb.c:883
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
```
**Symbols:**

```
ffffffff81265b90-ffffffff81265da0: dequeue_huge_page_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81281070)
Location: mm/hugetlb.c:893
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
```
**Symbols:**

```
ffffffff81281070-ffffffff81281279: dequeue_huge_page_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81290d00)
Location: mm/hugetlb.c:894
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
```
**Symbols:**

```
ffffffff81290d00-ffffffff81290f09: dequeue_huge_page_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c35b0)
Location: mm/hugetlb.c:1059
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:dequeue_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
```
**Symbols:**

```
ffffffff812c35b0-ffffffff812c37b3: dequeue_huge_page_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812cf530)
Location: mm/hugetlb.c:1093
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
```
**Symbols:**

```
ffffffff812cf530-ffffffff812cf756: dequeue_huge_page_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d6710)
Location: mm/hugetlb.c:1103
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_nodemask
```
**Symbols:**

```
ffffffff812d6710-ffffffff812d69a7: dequeue_huge_page_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131c4a0)
Location: mm/hugetlb.c:1107
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_nodemask
```
**Symbols:**

```
ffffffff8131c4a0-ffffffff8131c827: dequeue_huge_page_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81387620)
Location: mm/hugetlb.c:1155
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
```
**Symbols:**

```
ffffffff81387620-ffffffff81387a56: dequeue_huge_page_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81405a50)
Location: mm/hugetlb.c:1315
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
```
**Symbols:**

```
ffffffff81405a50-ffffffff81405ee2: dequeue_huge_page_nodemask (STB_LOCAL)
```
</details>
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
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff80001032d800)
Location: mm/hugetlb.c:894
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
```
**Symbols:**

```
ffff80001032d800-ffff80001032da30: dequeue_huge_page_nodemask (STB_LOCAL)
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
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000405e10)
Location: mm/hugetlb.c:894
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
```
**Symbols:**

```
c000000000405e10-c0000000004060b8: dequeue_huge_page_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffe00022c024)
Location: mm/hugetlb.c:894
Inline: True
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
```
**Symbols:**

```
ffffffe00022c024-ffffffe00022c1bc: dequeue_huge_page_nodemask.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812892e0)
Location: mm/hugetlb.c:894
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
```
**Symbols:**

```
ffffffff812892e0-ffffffff812894e9: dequeue_huge_page_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127b180)
Location: mm/hugetlb.c:894
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
```
**Symbols:**

```
ffffffff8127b180-ffffffff8127b389: dequeue_huge_page_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812870f0)
Location: mm/hugetlb.c:894
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
```
**Symbols:**

```
ffffffff812870f0-ffffffff812872f9: dequeue_huge_page_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *dequeue_huge_page_nodemask(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81297870)
Location: mm/hugetlb.c:894
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
```
**Symbols:**

```
ffffffff81297870-ffffffff81297a79: dequeue_huge_page_nodemask (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
