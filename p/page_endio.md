# Function: <code>page_endio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void page_endio(struct page *page, int rw, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118d8d0)
Location: mm/filemap.c:849
Inline: True
Direct callers:
  - fs/mpage.c:mpage_end_io
  - drivers/block/brd.c:brd_rw_page
```
**Symbols:**

```
ffffffff8118d8d0-ffffffff8118d91f: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a0500)
Location: mm/filemap.c:890
Inline: True
Direct callers:
  - fs/mpage.c:mpage_end_io
  - drivers/block/brd.c:brd_rw_page
```
**Symbols:**

```
ffffffff811a0500-ffffffff811a055f: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811af6d0)
Location: mm/filemap.c:993
Inline: True
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff811af6d0-ffffffff811af750: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b6580)
Location: mm/filemap.c:1119
Inline: True
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff811b6580-ffffffff811b6628: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ca900)
Location: mm/filemap.c:1241
Inline: True
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff811ca900-ffffffff811ca9a8: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eb950)
Location: mm/filemap.c:1241
Inline: True
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff811eb950-ffffffff811eb9f8: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fc4d0)
Location: mm/filemap.c:1294
Inline: True
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff811fc4d0-ffffffff811fc57a: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81213bf0)
Location: mm/filemap.c:1342
Inline: True
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff81213bf0-ffffffff81213c8b: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812213c0)
Location: mm/filemap.c:1351
Inline: True
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff812213c0-ffffffff812214c6: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124f400)
Location: mm/filemap.c:1326
Inline: False
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff8124f400-ffffffff8124f4c3: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81259da0)
Location: mm/filemap.c:1511
Inline: False
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff81259da0-ffffffff81259e68: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125dfe0)
Location: mm/filemap.c:1561
Inline: False
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff8125dfe0-ffffffff8125e0a8: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129a700)
Location: mm/filemap.c:1616
Inline: False
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff8129a700-ffffffff8129a7ce: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f1e80)
Location: mm/filemap.c:1660
Inline: False
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff812f1e80-ffffffff812f2028: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135bcc0)
Location: mm/filemap.c:1628
Inline: False
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff8135bcc0-ffffffff8135bdbe: page_endio (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b0880)
Location: mm/filemap.c:1351
Inline: True
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffff8000102b0880-ffff8000102b0a64: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04db5f4)
Location: mm/filemap.c:1351
Inline: True
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
c04db5f4-c04db750: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000363250)
Location: mm/filemap.c:1351
Inline: True
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
c000000000363250-c000000000363484: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d4bbc)
Location: mm/filemap.c:1351
Inline: True
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffffffe0001d4bbc-ffffffe0001d4cf8: page_endio (STB_GLOBAL)
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
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219a10)
Location: mm/filemap.c:1351
Inline: True
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff81219a10-ffffffff81219b16: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120cc20)
Location: mm/filemap.c:1351
Inline: True
Direct callers:
  - fs/mpage.c:mpage_end_io
  - drivers/nvdimm/pmem.c:pmem_rw_page
```
**Symbols:**

```
ffffffff8120cc20-ffffffff8120cd26: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812177b0)
Location: mm/filemap.c:1351
Inline: True
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff812177b0-ffffffff812178b6: page_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void page_endio(struct page *page, bool is_write, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226860)
Location: mm/filemap.c:1351
Inline: True
Direct callers:
  - fs/mpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff81226860-ffffffff8122697b: page_endio (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool is_write</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
</ul>
</details>
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
