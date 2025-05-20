# Function: <code>do_read_cache_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118e1b0)
Location: mm/filemap.c:2238
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:read_cache_page_gfp
```
**Symbols:**

```
ffffffff8118e1b0-ffffffff8118e355: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a1370)
Location: mm/filemap.c:2361
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffffffff811a1370-ffffffff811a1658: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b0f70)
Location: mm/filemap.c:2477
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffffffff811b0f70-ffffffff811b14ce: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b83d0)
Location: mm/filemap.c:2611
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffffffff811b83d0-ffffffff811b8886: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ccb50)
Location: mm/filemap.c:2781
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffffffff811ccb50-ffffffff811cd0cc: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811edc50)
Location: mm/filemap.c:2781
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffffffff811edc50-ffffffff811ee1f6: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ff200)
Location: mm/filemap.c:2758
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffffffff811ff200-ffffffff811ff993: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81216240)
Location: mm/filemap.c:2802
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffffffff81216240-ffffffff81216a64: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81223b50)
Location: mm/filemap.c:2756
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffffffff81223b50-ffffffff81224374: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81252b60)
Location: mm/filemap.c:2757
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffffffff81252b60-ffffffff81252fdd: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125d730)
Location: mm/filemap.c:3074
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffffffff8125d730-ffffffff8125dba1: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81260500)
Location: mm/filemap.c:3321
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffffffff81260500-ffffffff81260948: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129cef0)
Location: mm/filemap.c:3434
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffffffff8129cef0-ffffffff8129d334: do_read_cache_page (STB_LOCAL)
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
In mm/filemap.c (ffffffff812f4497)
Location: mm/filemap.c:3597
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
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
In mm/filemap.c (ffffffff8135e595)
Location: mm/filemap.c:3591
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
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
In mm/filemap.c (ffffffff81391335)
Location: mm/filemap.c:3759
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
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
In mm/filemap.c (ffffffff813bb0b4)
Location: mm/filemap.c:3766
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
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
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b1578)
Location: mm/filemap.c:2756
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffff8000102b1578-ffff8000102b19a4: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dded8)
Location: mm/filemap.c:2756
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
c04dded8-c04de634: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000366d60)
Location: mm/filemap.c:2756
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
c000000000366d60-c0000000003677e8: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d6ca4)
Location: mm/filemap.c:2756
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffffffe0001d6ca4-ffffffe0001d72fa: do_read_cache_page (STB_LOCAL)
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
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121c1a0)
Location: mm/filemap.c:2756
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffffffff8121c1a0-ffffffff8121c9c4: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120f390)
Location: mm/filemap.c:2756
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffffffff8120f390-ffffffff8120fba8: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219f40)
Location: mm/filemap.c:2756
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffffffff81219f40-ffffffff8121a764: do_read_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *do_read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81229030)
Location: mm/filemap.c:2756
Inline: False
Direct callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
```
**Symbols:**

```
ffffffff81229030-ffffffff81229834: do_read_cache_page (STB_LOCAL)
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
