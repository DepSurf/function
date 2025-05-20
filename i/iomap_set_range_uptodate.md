# Function: <code>iomap_set_range_uptodate</code>

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
void iomap_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81323430)
Location: fs/iomap.c:206
Inline: False
Direct callers:
  - fs/iomap.c:iomap_write_end
  - fs/iomap.c:iomap_read_page_sync
  - fs/iomap.c:iomap_readpage_actor
  - fs/iomap.c:iomap_read_end_io
```
**Symbols:**

```
ffffffff81323430-ffffffff813234ed: iomap_set_range_uptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iomap_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134b4d0)
Location: fs/iomap/buffered-io.c:121
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
**Symbols:**

```
ffffffff8134b4d0-ffffffff8134b58d: iomap_set_range_uptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iomap_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81363780)
Location: fs/iomap/buffered-io.c:121
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
**Symbols:**

```
ffffffff81363780-ffffffff8136384c: iomap_set_range_uptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void iomap_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813aaca0)
Location: fs/iomap/buffered-io.c:163
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
**Symbols:**

```
ffffffff813aaca0-ffffffff813aacd6: iomap_set_range_uptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iomap_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bc4f0)
Location: fs/iomap/buffered-io.c:161
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_read_page_end_io
```
**Symbols:**

```
ffffffff813bc4f0-ffffffff813bc526: iomap_set_range_uptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iomap_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c3240)
Location: fs/iomap/buffered-io.c:161
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
**Symbols:**

```
ffffffff813c3240-ffffffff813c3276: iomap_set_range_uptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void iomap_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81412bc0)
Location: fs/iomap/buffered-io.c:161
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
**Symbols:**

```
ffffffff81412bc0-ffffffff81412bf6: iomap_set_range_uptodate (STB_LOCAL)
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
In fs/iomap/buffered-io.c (ffffffff8148a2fe)
Location: fs/iomap/buffered-io.c:154
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
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
In fs/iomap/buffered-io.c (ffffffff8151dcf0)
Location: fs/iomap/buffered-io.c:162
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
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
In fs/iomap/buffered-io.c (ffffffff81555e5f)
Location: fs/iomap/buffered-io.c:162
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iomap_set_range_uptodate(struct folio *folio, size_t off, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8158b210)
Location: fs/iomap/buffered-io.c:72
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_read_inline_data
```
**Symbols:**

```
ffffffff8158b210-ffffffff8158b280: iomap_set_range_uptodate (STB_LOCAL)
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
void iomap_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042ae30)
Location: fs/iomap/buffered-io.c:121
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
**Symbols:**

```
ffff80001042ae30-ffff80001042af98: iomap_set_range_uptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iomap_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f2c14)
Location: fs/iomap/buffered-io.c:121
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
**Symbols:**

```
c05f2c14-c05f2d40: iomap_set_range_uptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iomap_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053a5b0)
Location: fs/iomap/buffered-io.c:121
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
**Symbols:**

```
c00000000053a5b0-c00000000053a758: iomap_set_range_uptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void iomap_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c7bc4)
Location: fs/iomap/buffered-io.c:121
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
**Symbols:**

```
ffffffe0002c7bc4-ffffffe0002c7cb6: iomap_set_range_uptodate (STB_LOCAL)
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
void iomap_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135bd60)
Location: fs/iomap/buffered-io.c:121
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
**Symbols:**

```
ffffffff8135bd60-ffffffff8135be2c: iomap_set_range_uptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iomap_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134ca00)
Location: fs/iomap/buffered-io.c:121
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
**Symbols:**

```
ffffffff8134ca00-ffffffff8134cacc: iomap_set_range_uptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iomap_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81359830)
Location: fs/iomap/buffered-io.c:121
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
**Symbols:**

```
ffffffff81359830-ffffffff813598fc: iomap_set_range_uptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iomap_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136cf20)
Location: fs/iomap/buffered-io.c:121
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
**Symbols:**

```
ffffffff8136cf20-ffffffff8136cfec: iomap_set_range_uptodate (STB_LOCAL)
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
