# Function: <code>find_get_pages_range_tag</code>

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
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, int tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cbac0)
Location: mm/filemap.c:1867
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_nr_tag
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
ffffffff811cbac0-ffffffff811cbd2a: find_get_pages_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, int tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ec8d0)
Location: mm/filemap.c:1866
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_nr_tag
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
ffffffff811ec8d0-ffffffff811ecb4b: find_get_pages_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fcbd0)
Location: mm/filemap.c:1876
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_nr_tag
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
ffffffff811fcbd0-ffffffff811fce8d: find_get_pages_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81215050)
Location: mm/filemap.c:1927
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_nr_tag
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
ffffffff81215050-ffffffff8121530d: find_get_pages_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81222ec0)
Location: mm/filemap.c:1913
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_nr_tag
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
ffffffff81222ec0-ffffffff812231c1: find_get_pages_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812507e0)
Location: mm/filemap.c:1896
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_nr_tag
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
ffffffff812507e0-ffffffff81250aa6: find_get_pages_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125b260)
Location: mm/filemap.c:2095
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
ffffffff8125b260-ffffffff8125b555: find_get_pages_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125e620)
Location: mm/filemap.c:2204
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
ffffffff8125e620-ffffffff8125e842: find_get_pages_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2258
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
ffffffff81cb9eb0-ffffffff81cb9eec: find_get_pages_range_tag.cold (STB_LOCAL)
ffffffff8129aab0-ffffffff8129ad2b: find_get_pages_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2302
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
ffffffff81e6b388-ffffffff81e6b3d8: find_get_pages_range_tag.cold (STB_LOCAL)
ffffffff812f0e10-ffffffff812f10c1: find_get_pages_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2299
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
ffffffff82062098-ffffffff820620e8: find_get_pages_range_tag.cold (STB_LOCAL)
ffffffff8135ba40-ffffffff8135bcab: find_get_pages_range_tag (STB_GLOBAL)
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
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b0350)
Location: mm/filemap.c:1913
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_nr_tag
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
ffff8000102b0350-ffff8000102b0634: find_get_pages_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dcf7c)
Location: mm/filemap.c:1913
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_nr_tag
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
c04dcf7c-c04dd1f4: find_get_pages_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c0000000003656f0)
Location: mm/filemap.c:1913
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_nr_tag
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
c0000000003656f0-c000000000365b14: find_get_pages_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d6032)
Location: mm/filemap.c:1913
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_nr_tag
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
ffffffe0001d6032-ffffffe0001d62b8: find_get_pages_range_tag (STB_GLOBAL)
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
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121b510)
Location: mm/filemap.c:1913
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_nr_tag
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
ffffffff8121b510-ffffffff8121b811: find_get_pages_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120e700)
Location: mm/filemap.c:1913
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_nr_tag
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
ffffffff8120e700-ffffffff8120ea01: find_get_pages_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812192b0)
Location: mm/filemap.c:1913
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_nr_tag
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
ffffffff812192b0-ffffffff812195b1: find_get_pages_range_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int find_get_pages_range_tag(struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812283b0)
Location: mm/filemap.c:1913
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range_nr_tag
  - mm/swap.c:pagevec_lookup_range_tag
```
**Symbols:**

```
ffffffff812283b0-ffffffff812286ab: find_get_pages_range_tag (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int tag</code> ➡️ <code>xa_mark_t tag</code>
</li>
</ul>
</details>
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
