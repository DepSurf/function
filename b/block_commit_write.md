# Function: <code>block_commit_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81243290)
Location: fs/buffer.c:2399
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff81243290-ffffffff812432a2: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126e83f)
Location: fs/buffer.c:2455
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/iomap.c:iomap_page_mkwrite_actor
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff8126b370-ffffffff8126b382: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81281a5f)
Location: fs/buffer.c:2496
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/iomap.c:iomap_page_mkwrite_actor
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff8127e4b0-ffffffff8127e4c2: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128f212)
Location: fs/buffer.c:2490
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/iomap.c:iomap_page_mkwrite_actor
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff8128c180-ffffffff8128c192: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b1e12)
Location: fs/buffer.c:2450
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/iomap.c:iomap_page_mkwrite_actor
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff812aeb10-ffffffff812aeb22: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d9d62)
Location: fs/buffer.c:2421
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/iomap.c:iomap_page_mkwrite_actor
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff812d6660-ffffffff812d6672: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ef252)
Location: fs/buffer.c:2433
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff812ebae0-ffffffff812ebaf2: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81310aa9)
Location: fs/buffer.c:2430
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff8130d1f0-ffffffff8130d202: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81323a89)
Location: fs/buffer.c:2430
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff813201c0-ffffffff813201d2: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135e179)
Location: fs/buffer.c:2474
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff8135a3b0-ffffffff8135a3c2: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136bc99)
Location: fs/buffer.c:2473
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff813684d0-ffffffff813684e2: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813725c9)
Location: fs/buffer.c:2494
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff8136eee0-ffffffff8136eef2: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813c1609)
Location: fs/buffer.c:2473
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff813bd4f0-ffffffff813bd502: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81448496)
Location: fs/buffer.c:2472
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff81446e50-ffffffff81446e6c: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d7073)
Location: fs/buffer.c:2460
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff814d5c20-ffffffff814d5c3c: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150a440)
Location: fs/buffer.c:2601
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff8150a440-ffffffff8150a4c2: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153eff0)
Location: fs/buffer.c:2569
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff8153eff0-ffffffff8153f06f: block_commit_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103dcdd8)
Location: fs/buffer.c:2430
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffff8000103d9108-ffff8000103d9150: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b62e8)
Location: fs/buffer.c:2430
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
c05b1e9c-c05b1ebc: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004e2450)
Location: fs/buffer.c:2430
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
c0000000004dcc90-c0000000004dccc4: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000294ffc)
Location: fs/buffer.c:2430
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffe0002918c8-ffffffe000291904: block_commit_write (STB_GLOBAL)
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
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131c069)
Location: fs/buffer.c:2430
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff813187a0-ffffffff813187b2: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130cc09)
Location: fs/buffer.c:2430
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81309390-ffffffff813093a2: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81319b39)
Location: fs/buffer.c:2430
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81316270-ffffffff81316282: block_commit_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int block_commit_write(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132b7f4)
Location: fs/buffer.c:2430
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81327fa0-ffffffff81327fb2: block_commit_write (STB_GLOBAL)
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
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
