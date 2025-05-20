# Function: <code>free_pcp_prepare</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a8cff)
Location: mm/page_alloc.c:1047
Inline: True
Inline callers:
  - mm/page_alloc.c:free_hot_cold_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b929c)
Location: mm/page_alloc.c:1063
Inline: True
Inline callers:
  - mm/page_alloc.c:free_hot_cold_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c131c)
Location: mm/page_alloc.c:1077
Inline: True
Inline callers:
  - mm/page_alloc.c:free_hot_cold_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool free_pcp_prepare(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d3c90)
Location: mm/page_alloc.c:1091
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff811d3c90-ffffffff811d3d38: free_pcp_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool free_pcp_prepare(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f4e70)
Location: mm/page_alloc.c:1049
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff811f4e70-ffffffff811f4f32: free_pcp_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool free_pcp_prepare(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81207250)
Location: mm/page_alloc.c:1094
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff81207250-ffffffff81207312: free_pcp_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool free_pcp_prepare(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126d2c0)
Location: mm/page_alloc.c:1215
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff8126d2c0-ffffffff8126d3c5: free_pcp_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool free_pcp_prepare(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127be00)
Location: mm/page_alloc.c:1202
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff8127be00-ffffffff8127bf05: free_pcp_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool free_pcp_prepare(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812ae290)
Location: mm/page_alloc.c:1252
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff812ae290-ffffffff812ae39b: free_pcp_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool free_pcp_prepare(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b9e80)
Location: mm/page_alloc.c:1314
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff812b9e80-ffffffff812b9fbe: free_pcp_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool free_pcp_prepare(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bf310)
Location: mm/page_alloc.c:1349
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff812bf310-ffffffff812bf44f: free_pcp_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool free_pcp_prepare(struct page *page, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1408
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff81301c60-ffffffff81301ec2: free_pcp_prepare (STB_LOCAL)
ffffffff81cbd1ca-ffffffff81cbd274: free_pcp_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool free_pcp_prepare(struct page *page, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1434
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff8136a5f0-ffffffff8136a8f8: free_pcp_prepare (STB_LOCAL)
ffffffff81e6f184-ffffffff81e6f24a: free_pcp_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool free_pcp_prepare(struct page *page, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1514
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff813e68d0-ffffffff813e6bd2: free_pcp_prepare (STB_LOCAL)
ffffffff82065007-ffffffff820650cd: free_pcp_prepare.cold (STB_LOCAL)
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
bool free_pcp_prepare(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010313ce0)
Location: mm/page_alloc.c:1202
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffff800010313ce0-ffff800010313e3c: free_pcp_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool free_pcp_prepare(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052e140)
Location: mm/page_alloc.c:1202
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
c052e140-c052e2b0: free_pcp_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool free_pcp_prepare(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e4e40)
Location: mm/page_alloc.c:1202
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
c0000000003e4e40-c0000000003e50c0: free_pcp_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool free_pcp_prepare(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021a68c)
Location: mm/page_alloc.c:1202
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffe00021a68c-ffffffe00021a7c0: free_pcp_prepare (STB_LOCAL)
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
bool free_pcp_prepare(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81274450)
Location: mm/page_alloc.c:1202
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff81274450-ffffffff81274555: free_pcp_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool free_pcp_prepare(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812663c0)
Location: mm/page_alloc.c:1202
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff812663c0-ffffffff812664c5: free_pcp_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool free_pcp_prepare(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812721f0)
Location: mm/page_alloc.c:1202
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff812721f0-ffffffff812722f5: free_pcp_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool free_pcp_prepare(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81281c50)
Location: mm/page_alloc.c:1202
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff81281c50-ffffffff81281d8a: free_pcp_prepare (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int order</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
