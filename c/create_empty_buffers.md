# Function: <code>create_empty_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81243890)
Location: fs/buffer.c:1588
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81243890-ffffffff81243946: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126b980)
Location: fs/buffer.c:1578
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff8126b980-ffffffff8126ba85: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127eac0)
Location: fs/buffer.c:1578
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff8127eac0-ffffffff8127ebc5: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128c9b0)
Location: fs/buffer.c:1573
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:create_page_buffers
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff8128c9b0-ffffffff8128ca9c: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812aef00)
Location: fs/buffer.c:1533
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:create_page_buffers
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff812aef00-ffffffff812aefef: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d73c0)
Location: fs/buffer.c:1504
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:create_page_buffers
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff812d73c0-ffffffff812d74c1: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ec8d0)
Location: fs/buffer.c:1512
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:create_page_buffers
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff812ec8d0-ffffffff812ec9d4: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130e070)
Location: fs/buffer.c:1513
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:create_page_buffers
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff8130e070-ffffffff8130e17e: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81321090)
Location: fs/buffer.c:1513
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff81321090-ffffffff8132119e: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135ab70)
Location: fs/buffer.c:1557
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:create_page_buffers
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff8135ab70-ffffffff8135ac7d: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813689b0)
Location: fs/buffer.c:1556
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:create_page_buffers
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff813689b0-ffffffff81368abd: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136fe70)
Location: fs/buffer.c:1576
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:create_page_buffers
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff8136fe70-ffffffff8136ff77: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813be9d0)
Location: fs/buffer.c:1555
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:create_page_buffers
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff813be9d0-ffffffff813beade: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81445380)
Location: fs/buffer.c:1553
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:create_page_buffers
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff81445380-ffffffff814455c6: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d4c00)
Location: fs/buffer.c:1538
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:create_page_buffers
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff814d4c00-ffffffff814d4e4e: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150a2c0)
Location: fs/buffer.c:1694
Inline: False
Direct callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff8150a2c0-ffffffff8150a336: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct buffer_head *create_empty_buffers(struct folio *folio, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153ecf0)
Location: fs/buffer.c:1644
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff8153ecf0-ffffffff8153eda9: create_empty_buffers (STB_GLOBAL)
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
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d9300)
Location: fs/buffer.c:1513
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:create_page_buffers
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffff8000103d9300-ffff8000103d9500: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b2098)
Location: fs/buffer.c:1513
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:create_page_buffers
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
c05b2098-c05b2230: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dd370)
Location: fs/buffer.c:1513
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:create_page_buffers
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
c0000000004dd370-c0000000004dd5f0: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000292814)
Location: fs/buffer.c:1513
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:create_page_buffers
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffe000292814-ffffffe000292972: create_empty_buffers (STB_GLOBAL)
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
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81319670)
Location: fs/buffer.c:1513
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff81319670-ffffffff8131977e: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130a230)
Location: fs/buffer.c:1513
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff8130a230-ffffffff8130a33e: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81317140)
Location: fs/buffer.c:1513
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff81317140-ffffffff8131724e: create_empty_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void create_empty_buffers(struct page *page, long unsigned int blocksize, long unsigned int b_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813284f0)
Location: fs/buffer.c:1513
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff813284f0-ffffffff813285fc: create_empty_buffers (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>struct buffer_head *</code>
</li>
</ul>
</details>
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
