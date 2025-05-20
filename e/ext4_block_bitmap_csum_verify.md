# Function: <code>ext4_block_bitmap_csum_verify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81290650)
Location: fs/ext4/bitmap.c:56
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
**Symbols:**

```
ffffffff81290650-ffffffff81290776: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff812bdb70)
Location: fs/ext4/bitmap.c:56
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
**Symbols:**

```
ffffffff812bdb70-ffffffff812bdc97: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff812d31c0)
Location: fs/ext4/bitmap.c:56
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
**Symbols:**

```
ffffffff812d31c0-ffffffff812d32e7: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff812e4710)
Location: fs/ext4/bitmap.c:56
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
**Symbols:**

```
ffffffff812e4710-ffffffff812e47de: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81309140)
Location: fs/ext4/bitmap.c:57
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
**Symbols:**

```
ffffffff81309140-ffffffff8130920e: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81337070)
Location: fs/ext4/bitmap.c:57
Inline: False
```
**Symbols:**

```
ffffffff81337070-ffffffff8133713e: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff8134e2f0)
Location: fs/ext4/bitmap.c:57
Inline: False
```
**Symbols:**

```
ffffffff8134e2f0-ffffffff8134e3be: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81376cb0)
Location: fs/ext4/bitmap.c:57
Inline: False
```
**Symbols:**

```
ffffffff81376cb0-ffffffff81376d77: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff8138ef20)
Location: fs/ext4/bitmap.c:57
Inline: False
```
**Symbols:**

```
ffffffff8138ef20-ffffffff8138efe7: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff813da4c0)
Location: fs/ext4/bitmap.c:57
Inline: False
```
**Symbols:**

```
ffffffff813da4c0-ffffffff813da580: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff813ec190)
Location: fs/ext4/bitmap.c:57
Inline: False
```
**Symbols:**

```
ffffffff813ec190-ffffffff813ec250: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff813f26c0)
Location: fs/ext4/bitmap.c:57
Inline: False
```
**Symbols:**

```
ffffffff813f26c0-ffffffff813f2781: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff814446a0)
Location: fs/ext4/bitmap.c:57
Inline: False
```
**Symbols:**

```
ffffffff814446a0-ffffffff81444761: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff814c05e0)
Location: fs/ext4/bitmap.c:57
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
**Symbols:**

```
ffffffff814c05e0-ffffffff814c06c8: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81558670)
Location: fs/ext4/bitmap.c:57
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
**Symbols:**

```
ffffffff81558670-ffffffff81558758: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff815904c0)
Location: fs/ext4/bitmap.c:57
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
**Symbols:**

```
ffffffff815904c0-ffffffff815905a9: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff815c9200)
Location: fs/ext4/bitmap.c:57
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
**Symbols:**

```
ffffffff815c9200-ffffffff815c92e9: ext4_block_bitmap_csum_verify (STB_GLOBAL)
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
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffff800010461728)
Location: fs/ext4/bitmap.c:57
Inline: False
```
**Symbols:**

```
ffff800010461728-ffff8000104617e4: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (c0621bd8)
Location: fs/ext4/bitmap.c:57
Inline: False
```
**Symbols:**

```
c0621bd8-c0621cb0: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (c00000000057dce0)
Location: fs/ext4/bitmap.c:57
Inline: False
```
**Symbols:**

```
c00000000057dce0-c00000000057de24: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffe0002f0702)
Location: fs/ext4/bitmap.c:57
Inline: False
```
**Symbols:**

```
ffffffe0002f0702-ffffffe0002f07bc: ext4_block_bitmap_csum_verify (STB_GLOBAL)
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
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81387500)
Location: fs/ext4/bitmap.c:57
Inline: False
```
**Symbols:**

```
ffffffff81387500-ffffffff813875c7: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81377f90)
Location: fs/ext4/bitmap.c:57
Inline: False
```
**Symbols:**

```
ffffffff81377f90-ffffffff81378057: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81384fd0)
Location: fs/ext4/bitmap.c:57
Inline: False
```
**Symbols:**

```
ffffffff81384fd0-ffffffff81385097: ext4_block_bitmap_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_block_bitmap_csum_verify(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81398b50)
Location: fs/ext4/bitmap.c:57
Inline: False
```
**Symbols:**

```
ffffffff81398b50-ffffffff81398c17: ext4_block_bitmap_csum_verify (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>ext4_group_t group</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, group, gdp, bh</code> ➡️ <code>sb, gdp, bh</code>
</li>
</ul>
</details>
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
