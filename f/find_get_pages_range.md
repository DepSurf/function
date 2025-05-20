# Function: <code>find_get_pages_range</code>

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
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ce6b0)
Location: mm/filemap.c:1702
Inline: False
Direct callers:
  - mm/filemap.c:filemap_range_has_page
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
ffffffff811ce6b0-ffffffff811ce8ed: find_get_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811f0260)
Location: mm/filemap.c:1701
Inline: False
Direct callers:
  - mm/filemap.c:filemap_range_has_page
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
ffffffff811f0260-ffffffff811f0483: find_get_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81202640)
Location: mm/filemap.c:1734
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
ffffffff81202640-ffffffff812028c0: find_get_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219930)
Location: mm/filemap.c:1793
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
ffffffff81219930-ffffffff81219b7b: find_get_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81227260)
Location: mm/filemap.c:1791
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
ffffffff81227260-ffffffff812274e4: find_get_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81253ad0)
Location: mm/filemap.c:1774
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
ffffffff81253ad0-ffffffff81253d8f: find_get_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125e8a0)
Location: mm/filemap.c:1973
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
ffffffff8125e8a0-ffffffff8125eba4: find_get_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81262fa0)
Location: mm/filemap.c:2095
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
ffffffff81262fa0-ffffffff812631b5: find_get_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2149
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
ffffffff81cb9fe3-ffffffff81cba009: find_get_pages_range.cold (STB_LOCAL)
ffffffff8129f690-ffffffff8129f8ec: find_get_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2181
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
ffffffff81e6b664-ffffffff81e6b69e: find_get_pages_range.cold (STB_LOCAL)
ffffffff812f65a0-ffffffff812f690b: find_get_pages_range (STB_GLOBAL)
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
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b4078)
Location: mm/filemap.c:1791
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
ffff8000102b4078-ffff8000102b4300: find_get_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e1880)
Location: mm/filemap.c:1791
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
c04e1880-c04e1ae8: find_get_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c00000000036b850)
Location: mm/filemap.c:1791
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
c00000000036b850-c00000000036bc48: find_get_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d99a0)
Location: mm/filemap.c:1791
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
ffffffe0001d99a0-ffffffe0001d9b92: find_get_pages_range (STB_GLOBAL)
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
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121f8b0)
Location: mm/filemap.c:1791
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
ffffffff8121f8b0-ffffffff8121fb34: find_get_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81212a60)
Location: mm/filemap.c:1791
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
ffffffff81212a60-ffffffff81212ce4: find_get_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121d650)
Location: mm/filemap.c:1791
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
ffffffff8121d650-ffffffff8121d8d4: find_get_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int find_get_pages_range(struct address_space *mapping, long unsigned int *start, long unsigned int end, unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122c6d0)
Location: mm/filemap.c:1791
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lookup_range
```
**Symbols:**

```
ffffffff8122c6d0-ffffffff8122c94f: find_get_pages_range (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
