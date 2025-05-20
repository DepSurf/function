# Function: <code>iomap_iop_set_range_uptodate</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iomap_iop_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813aabc0)
Location: fs/iomap/buffered-io.c:139
Inline: False
```
**Symbols:**

```
ffffffff813aabc0-ffffffff813aac9b: iomap_iop_set_range_uptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iomap_iop_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bc410)
Location: fs/iomap/buffered-io.c:145
Inline: False
```
**Symbols:**

```
ffffffff813bc410-ffffffff813bc4e4: iomap_iop_set_range_uptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iomap_iop_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c3160)
Location: fs/iomap/buffered-io.c:145
Inline: False
```
**Symbols:**

```
ffffffff813c3160-ffffffff813c3235: iomap_iop_set_range_uptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void iomap_iop_set_range_uptodate(struct page *page, unsigned int off, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:145
Inline: False
```
**Symbols:**

```
ffffffff81412ad0-ffffffff81412bbc: iomap_iop_set_range_uptodate (STB_LOCAL)
ffffffff81cc7898-ffffffff81cc790c: iomap_iop_set_range_uptodate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void iomap_iop_set_range_uptodate(struct folio *folio, struct iomap_page *iop, size_t off, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:139
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
**Symbols:**

```
ffffffff81488f40-ffffffff81489083: iomap_iop_set_range_uptodate (STB_LOCAL)
ffffffff81e79efc-ffffffff81e79f7d: iomap_iop_set_range_uptodate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void iomap_iop_set_range_uptodate(struct folio *folio, struct iomap_page *iop, size_t off, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:147
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
**Symbols:**

```
ffffffff8151cbb0-ffffffff8151ccc3: iomap_iop_set_range_uptodate (STB_LOCAL)
ffffffff8206ae3b-ffffffff8206aec4: iomap_iop_set_range_uptodate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void iomap_iop_set_range_uptodate(struct folio *folio, struct iomap_page *iop, size_t off, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:147
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
**Symbols:**

```
ffffffff81554d90-ffffffff81554e92: iomap_iop_set_range_uptodate (STB_LOCAL)
ffffffff820eada2-ffffffff820eae1e: iomap_iop_set_range_uptodate.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param added. </b>
<code>struct iomap_page *iop</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param reordered. </b>
<code>page, off, len</code> ➡️ <code>folio, iop, off, len</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int off</code> ➡️ <code>size_t off</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int len</code> ➡️ <code>size_t len</code>
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
</ul>
