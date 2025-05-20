# Function: <code>prep_new_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81195f46)
Location: mm/page_alloc.c:1364
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a991c)
Location: mm/page_alloc.c:1732
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff811b9e75)
Location: mm/page_alloc.c:1751
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff811c23e3)
Location: mm/page_alloc.c:1764
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d6d8e)
Location: mm/page_alloc.c:1802
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f80d6)
Location: mm/page_alloc.c:1909
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120a88c)
Location: mm/page_alloc.c:1953
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void prep_new_page(struct page *page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126d3d0)
Location: mm/page_alloc.c:2150
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff8126d3d0-ffffffff8126d526: prep_new_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void prep_new_page(struct page *page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127bf10)
Location: mm/page_alloc.c:2141
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff8127bf10-ffffffff8127c066: prep_new_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void prep_new_page(struct page *page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812af740)
Location: mm/page_alloc.c:2213
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff812af740-ffffffff812af7f7: prep_new_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bdff5)
Location: mm/page_alloc.c:2294
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff812c47b3)
Location: mm/page_alloc.c:2345
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff8130862b)
Location: mm/page_alloc.c:2423
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff813709c6)
Location: mm/page_alloc.c:2449
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff813ece48)
Location: mm/page_alloc.c:2528
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff81421d92)
Location: mm/page_alloc.c:1574
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff8144ebc4)
Location: mm/page_alloc.c:1537
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void prep_new_page(struct page *page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010313490)
Location: mm/page_alloc.c:2141
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffff800010313490-ffff800010313610: prep_new_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void prep_new_page(struct page *page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052e2b0)
Location: mm/page_alloc.c:2141
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
c052e2b0-c052e410: prep_new_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void prep_new_page(struct page *page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e50c0)
Location: mm/page_alloc.c:2141
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
c0000000003e50c0-c0000000003e5344: prep_new_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void prep_new_page(struct page *page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021a7c0)
Location: mm/page_alloc.c:2141
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffe00021a7c0-ffffffe00021a92c: prep_new_page (STB_LOCAL)
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
void prep_new_page(struct page *page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81274560)
Location: mm/page_alloc.c:2141
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81274560-ffffffff812746b6: prep_new_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void prep_new_page(struct page *page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812664d0)
Location: mm/page_alloc.c:2141
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff812664d0-ffffffff81266626: prep_new_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void prep_new_page(struct page *page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81272300)
Location: mm/page_alloc.c:2141
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81272300-ffffffff81272456: prep_new_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void prep_new_page(struct page *page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81282130)
Location: mm/page_alloc.c:2141
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81282130-ffffffff812822a9: prep_new_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
