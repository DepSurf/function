# Function: <code>memblock_free_pages</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828b8c59)
Location: mm/page_alloc.c:1380
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffff828b8c59-ffffffff828b8d1b: memblock_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828d5dcb)
Location: mm/page_alloc.c:1490
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffff828d5dcb-ffffffff828d5ddd: memblock_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828de23f)
Location: mm/page_alloc.c:1477
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffff828de23f-ffffffff828de251: memblock_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82cfb739)
Location: mm/page_alloc.c:1536
Inline: False
Direct callers:
  - mm/memblock.c:free_low_memory_core_early
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffff82cfb739-ffffffff82cfb74b: memblock_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82fe812e)
Location: mm/page_alloc.c:1619
Inline: False
Direct callers:
  - mm/memblock.c:free_low_memory_core_early
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffff82fe812e-ffffffff82fe8140: memblock_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff831f292a)
Location: mm/page_alloc.c:1654
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffff831f292a-ffffffff831f293c: memblock_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff832d87da)
Location: mm/page_alloc.c:1740
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffff832d87da-ffffffff832d87ec: memblock_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8348cd4a)
Location: mm/page_alloc.c:1723
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_late
```
**Symbols:**

```
ffffffff8348cd4a-ffffffff8348cd66: memblock_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff83ebeb50)
Location: mm/page_alloc.c:1804
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_late
```
**Symbols:**

```
ffffffff83ebeb50-ffffffff83ebeb6c: memblock_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff836e2df0)
Location: mm/mm_init.c:2577
Inline: False
Direct callers:
  - mm/memblock.c:free_low_memory_core_early
  - mm/memblock.c:memblock_free_late
```
**Symbols:**

```
ffffffff836e2df0-ffffffff836e2e0c: memblock_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff83915680)
Location: mm/mm_init.c:2565
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_late
```
**Symbols:**

```
ffffffff83915680-ffffffff8391569c: memblock_free_pages (STB_GLOBAL)
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
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800011456ed4)
Location: mm/page_alloc.c:1477
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffff800011456ed4-ffff800011456f08: memblock_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c1531838)
Location: mm/page_alloc.c:1477
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
c1531838-c1531858: memblock_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000013800e4)
Location: mm/page_alloc.c:1477
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
c0000000013800e4-c0000000013800fc: memblock_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe000015ac4)
Location: mm/page_alloc.c:1477
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffe000015ac4-ffffffe000015af6: memblock_free_pages (STB_GLOBAL)
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
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828c70f3)
Location: mm/page_alloc.c:1477
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffff828c70f3-ffffffff828c7105: memblock_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828bf818)
Location: mm/page_alloc.c:1477
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffff828bf818-ffffffff828bf82a: memblock_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828d9e73)
Location: mm/page_alloc.c:1477
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffff828d9e73-ffffffff828d9e85: memblock_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memblock_free_pages(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828df294)
Location: mm/page_alloc.c:1477
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffff828df294-ffffffff828df2a6: memblock_free_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
