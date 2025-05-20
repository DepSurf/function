# Function: <code>__block_write_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81245110)
Location: fs/buffer.c:1905
Inline: False
Direct callers:
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:nobh_write_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
**Symbols:**

```
ffffffff81245110-ffffffff8124558c: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126f1dc)
Location: fs/buffer.c:2036
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff8126e2d0-ffffffff8126e2e3: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812823e4)
Location: fs/buffer.c:2077
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff81281500-ffffffff81281513: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128fa61)
Location: fs/buffer.c:2074
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff8128ed50-ffffffff8128ed63: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b274e)
Location: fs/buffer.c:2034
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff812b1920-ffffffff812b1933: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812da709)
Location: fs/buffer.c:2005
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff812d9840-ffffffff812d9853: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812efbe9)
Location: fs/buffer.c:2014
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff812eed30-ffffffff812eed43: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81311479)
Location: fs/buffer.c:2015
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff81310540-ffffffff81310553: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81324459)
Location: fs/buffer.c:2015
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff81323520-ffffffff81323533: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135e464)
Location: fs/buffer.c:2059
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:cont_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff8135df80-ffffffff8135df93: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136beed)
Location: fs/buffer.c:2058
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:cont_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_page_mkwrite
```
**Symbols:**

```
ffffffff8136baa0-ffffffff8136bab3: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8137281d)
Location: fs/buffer.c:2078
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:cont_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_page_mkwrite
```
**Symbols:**

```
ffffffff813723d0-ffffffff813723e3: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813c187e)
Location: fs/buffer.c:2057
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:cont_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_page_mkwrite
```
**Symbols:**

```
ffffffff813c1410-ffffffff813c1423: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8144852d)
Location: fs/buffer.c:2053
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_page_mkwrite
```
**Symbols:**

```
ffffffff814480c0-ffffffff8144812b: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d6fe1)
Location: fs/buffer.c:2038
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_page_mkwrite
```
**Symbols:**

```
ffffffff814d6c70-ffffffff814d6cdb: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150d537)
Location: fs/buffer.c:2175
Inline: True
Inline callers:
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_page_mkwrite
```
**Symbols:**

```
ffffffff8150d2e0-ffffffff8150d362: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff815420d7)
Location: fs/buffer.c:2149
Inline: True
Inline callers:
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_page_mkwrite
```
**Symbols:**

```
ffffffff81541ea0-ffffffff81541f1f: __block_write_begin (STB_GLOBAL)
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
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103dd7f8)
Location: fs/buffer.c:2015
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffff8000103dc868-ffff8000103dc8b8: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b6cc0)
Location: fs/buffer.c:2015
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
c05b5cc8-c05b5d04: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004e3200)
Location: fs/buffer.c:2015
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
c0000000004e1d50-c0000000004e1d68: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe0002957a0)
Location: fs/buffer.c:2015
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffe000294b4c-ffffffe000294b90: __block_write_begin (STB_GLOBAL)
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
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131ca39)
Location: fs/buffer.c:2015
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff8131bb00-ffffffff8131bb13: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130d5d9)
Location: fs/buffer.c:2015
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff8130c6a0-ffffffff8130c6b3: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131a509)
Location: fs/buffer.c:2015
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff813195d0-ffffffff813195e3: __block_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132c207)
Location: fs/buffer.c:2015
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff8132b240-ffffffff8132b253: __block_write_begin (STB_GLOBAL)
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
