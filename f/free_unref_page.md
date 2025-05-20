# Function: <code>free_unref_page</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_unref_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d58e0)
Location: mm/page_alloc.c:2672
Inline: False
```
**Symbols:**

```
ffffffff811d58e0-ffffffff811d594a: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_unref_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f6cf0)
Location: mm/page_alloc.c:2776
Inline: False
```
**Symbols:**

```
ffffffff811f6cf0-ffffffff811f6d5a: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_unref_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81209090)
Location: mm/page_alloc.c:2875
Inline: False
Direct callers:
  - mm/page_alloc.c:page_frag_free
```
**Symbols:**

```
ffffffff81209090-ffffffff812090fa: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_unref_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81270410)
Location: mm/page_alloc.c:3051
Inline: False
Direct callers:
  - mm/page_alloc.c:page_frag_free
```
**Symbols:**

```
ffffffff81270410-ffffffff81270477: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_unref_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127f250)
Location: mm/page_alloc.c:3042
Inline: False
Direct callers:
  - mm/page_alloc.c:page_frag_free
```
**Symbols:**

```
ffffffff8127f250-ffffffff8127f2b7: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_unref_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b1440)
Location: mm/page_alloc.c:3134
Inline: False
Direct callers:
  - mm/swap.c:__put_page
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
```
**Symbols:**

```
ffffffff812b1440-ffffffff812b14f7: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_unref_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bce90)
Location: mm/page_alloc.c:3234
Inline: False
Direct callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
**Symbols:**

```
ffffffff812bce90-ffffffff812bcf3e: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_unref_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c1d30)
Location: mm/page_alloc.c:3283
Inline: False
Direct callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
```
**Symbols:**

```
ffffffff812c1d30-ffffffff812c1de5: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_unref_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81305580)
Location: mm/page_alloc.c:3390
Inline: False
Direct callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:free_compound_page
```
**Symbols:**

```
ffffffff81305580-ffffffff813056cf: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_unref_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136d840)
Location: mm/page_alloc.c:3428
Inline: False
Direct callers:
  - mm/swap.c:__put_page
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:free_compound_page
```
**Symbols:**

```
ffffffff8136d840-ffffffff8136d9bf: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_unref_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e9c00)
Location: mm/page_alloc.c:3456
Inline: False
Direct callers:
  - mm/swap.c:__folio_put
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:free_compound_page
```
**Symbols:**

```
ffffffff813e9c00-ffffffff813e9e2a: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_unref_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141ecf0)
Location: mm/page_alloc.c:2435
Inline: False
Direct callers:
  - mm/swap.c:__folio_put
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:free_compound_page
```
**Symbols:**

```
ffffffff8141ecf0-ffffffff8141ee5d: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_unref_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144b980)
Location: mm/page_alloc.c:2478
Inline: False
Direct callers:
  - mm/swap.c:__folio_put
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:destroy_large_folio
```
**Symbols:**

```
ffffffff8144b980-ffffffff8144bb3a: free_unref_page (STB_GLOBAL)
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
void free_unref_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010316d20)
Location: mm/page_alloc.c:3042
Inline: False
Direct callers:
  - mm/swap.c:__put_page
  - mm/page_alloc.c:page_frag_free
```
**Symbols:**

```
ffff800010316d20-ffff800010316dac: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_unref_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c05315ac)
Location: mm/page_alloc.c:3042
Inline: False
Direct callers:
  - mm/page_alloc.c:page_frag_free
```
**Symbols:**

```
c05315ac-c053162c: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_unref_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e90a0)
Location: mm/page_alloc.c:3042
Inline: False
Direct callers:
  - mm/page_alloc.c:page_frag_free
```
**Symbols:**

```
c0000000003e90a0-c0000000003e9138: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_unref_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021d0d6)
Location: mm/page_alloc.c:3042
Inline: False
Direct callers:
  - mm/swap.c:__put_page
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:page_frag_free
```
**Symbols:**

```
ffffffe00021d0d6-ffffffe00021d13c: free_unref_page (STB_GLOBAL)
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
void free_unref_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812778a0)
Location: mm/page_alloc.c:3042
Inline: False
Direct callers:
  - mm/page_alloc.c:page_frag_free
```
**Symbols:**

```
ffffffff812778a0-ffffffff81277907: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_unref_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812697c0)
Location: mm/page_alloc.c:3042
Inline: False
Direct callers:
  - mm/page_alloc.c:page_frag_free
```
**Symbols:**

```
ffffffff812697c0-ffffffff81269814: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_unref_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81275640)
Location: mm/page_alloc.c:3042
Inline: False
Direct callers:
  - mm/page_alloc.c:page_frag_free
```
**Symbols:**

```
ffffffff81275640-ffffffff812756a7: free_unref_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_unref_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81285200)
Location: mm/page_alloc.c:3042
Inline: False
Direct callers:
  - mm/page_alloc.c:page_frag_free
```
**Symbols:**

```
ffffffff81285200-ffffffff81285267: free_unref_page (STB_GLOBAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
