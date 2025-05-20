# Function: <code>__block_write_begin_int</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126dcf0)
Location: fs/buffer.c:1950
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
  - fs/iomap.c:iomap_page_mkwrite_actor
  - fs/iomap.c:iomap_write_begin
```
**Symbols:**

```
ffffffff8126dcf0-ffffffff8126e2c4: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81280f40)
Location: fs/buffer.c:1992
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
  - fs/iomap.c:iomap_page_mkwrite_actor
  - fs/iomap.c:iomap_write_begin
```
**Symbols:**

```
ffffffff81280f40-ffffffff812814fe: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128e830)
Location: fs/buffer.c:1989
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
  - fs/iomap.c:iomap_page_mkwrite_actor
```
**Symbols:**

```
ffffffff8128e830-ffffffff8128ed43: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b1420)
Location: fs/buffer.c:1949
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
  - fs/iomap.c:iomap_page_mkwrite_actor
```
**Symbols:**

```
ffffffff812b1420-ffffffff812b1914: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d9280)
Location: fs/buffer.c:1920
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
  - fs/iomap.c:iomap_page_mkwrite_actor
```
**Symbols:**

```
ffffffff812d9280-ffffffff812d983f: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ee750)
Location: fs/buffer.c:1929
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
```
**Symbols:**

```
ffffffff812ee750-ffffffff812eed23: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1930
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
```
**Symbols:**

```
ffffffff81311d78-ffffffff81311d9f: __block_write_begin_int.cold (STB_LOCAL)
ffffffff8130ff40-ffffffff8131053e: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81322f10)
Location: fs/buffer.c:1930
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
```
**Symbols:**

```
ffffffff81322f10-ffffffff81323519: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135db00)
Location: fs/buffer.c:1974
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
```
**Symbols:**

```
ffffffff8135db00-ffffffff8135df77: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136b6f0)
Location: fs/buffer.c:1973
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
```
**Symbols:**

```
ffffffff8136b6f0-ffffffff8136ba93: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81372000)
Location: fs/buffer.c:1993
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
```
**Symbols:**

```
ffffffff81372000-ffffffff813723ca: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, const struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1972
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_begin
```
**Symbols:**

```
ffffffff81cc486b-ffffffff81cc489d: __block_write_begin_int.cold (STB_LOCAL)
ffffffff813c1030-ffffffff813c1401: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __block_write_begin_int(struct folio *folio, loff_t pos, unsigned int len, get_block_t *get_block, const struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1968
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_begin
```
**Symbols:**

```
ffffffff81e77267-ffffffff81e7729b: __block_write_begin_int.cold (STB_LOCAL)
ffffffff81447cf0-ffffffff814480ba: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __block_write_begin_int(struct folio *folio, loff_t pos, unsigned int len, get_block_t *get_block, const struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1953
Inline: False
Direct callers:
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_begin
```
**Symbols:**

```
ffffffff820692a4-ffffffff820692d7: __block_write_begin_int.cold (STB_LOCAL)
ffffffff814d68a0-ffffffff814d6c51: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __block_write_begin_int(struct folio *folio, loff_t pos, unsigned int len, get_block_t *get_block, const struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2090
Inline: False
Direct callers:
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_begin
```
**Symbols:**

```
ffffffff820e8c97-ffffffff820e8d00: __block_write_begin_int.cold (STB_LOCAL)
ffffffff8150ceb0-ffffffff8150d2cf: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __block_write_begin_int(struct folio *folio, loff_t pos, unsigned int len, get_block_t *get_block, const struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2068
Inline: False
Direct callers:
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_begin
```
**Symbols:**

```
ffffffff821c58eb-ffffffff821c5932: __block_write_begin_int.cold (STB_LOCAL)
ffffffff81541ab0-ffffffff81541e8d: __block_write_begin_int (STB_GLOBAL)
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
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103dc128)
Location: fs/buffer.c:1930
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
```
**Symbols:**

```
ffff8000103dc128-ffff8000103dc864: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b5428)
Location: fs/buffer.c:1930
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
```
**Symbols:**

```
c05b5428-c05b5cc8: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004e1560)
Location: fs/buffer.c:1930
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
```
**Symbols:**

```
c0000000004e1560-c0000000004e1d50: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe0002945ae)
Location: fs/buffer.c:1930
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
```
**Symbols:**

```
ffffffe0002945ae-ffffffe000294b4c: __block_write_begin_int (STB_GLOBAL)
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
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131b4f0)
Location: fs/buffer.c:1930
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
```
**Symbols:**

```
ffffffff8131b4f0-ffffffff8131baf9: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130c090)
Location: fs/buffer.c:1930
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
```
**Symbols:**

```
ffffffff8130c090-ffffffff8130c699: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81318fc0)
Location: fs/buffer.c:1930
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
```
**Symbols:**

```
ffffffff81318fc0-ffffffff813195c9: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __block_write_begin_int(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132abf0)
Location: fs/buffer.c:1930
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
```
**Symbols:**

```
ffffffff8132abf0-ffffffff8132b233: __block_write_begin_int (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct iomap *iomap</code> ➡️ <code>const struct iomap *iomap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
