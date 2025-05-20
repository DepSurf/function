# Function: <code>ext4_get_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81299110)
Location: fs/ext4/inode.c:745
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81299110-ffffffff81299128: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c66d4)
Location: fs/ext4/inode.c:766
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff812c6300-ffffffff812c6318: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dbf1d)
Location: fs/ext4/inode.c:780
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff812dbb60-ffffffff812dbb78: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813007df)
Location: fs/ext4/inode.c:786
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81300400-ffffffff81300418: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81325034)
Location: fs/ext4/inode.c:796
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81324c20-ffffffff81324c38: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81353287)
Location: fs/ext4/inode.c:797
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81352e70-ffffffff81352e88: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136b3b4)
Location: fs/ext4/inode.c:797
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff8136afa0-ffffffff8136afb8: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813948cf)
Location: fs/ext4/inode.c:805
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff813944d0-ffffffff813944e8: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ad24f)
Location: fs/ext4/inode.c:814
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff813ace50-ffffffff813ace68: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f9282)
Location: fs/ext4/inode.c:793
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff813f90c0-ffffffff813f90d8: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140b94c)
Location: fs/ext4/inode.c:807
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff8140b790-ffffffff8140b7a8: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81411b1f)
Location: fs/ext4/inode.c:808
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff81411940-ffffffff81411958: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814649e1)
Location: fs/ext4/inode.c:808
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff814647f0-ffffffff81464808: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e3f86)
Location: fs/ext4/inode.c:816
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff814e3df0-ffffffff814e3e14: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157d51c)
Location: fs/ext4/inode.c:822
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff8157d310-ffffffff8157d334: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b493a)
Location: fs/ext4/inode.c:777
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff815b46c0-ffffffff815b46e4: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815ed77a)
Location: fs/ext4/inode.c:779
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff815ed4d0-ffffffff815ed4f4: ext4_get_block (STB_GLOBAL)
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
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010481950)
Location: fs/ext4/inode.c:814
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffff8000104815a8-ffff8000104815f8: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0642ac8)
Location: fs/ext4/inode.c:814
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
c064275c-c0642798: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a6070)
Location: fs/ext4/inode.c:814
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
c0000000005a5ca0-c0000000005a5cc0: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030a4fc)
Location: fs/ext4/inode.c:814
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffe00030a252-ffffffe00030a296: ext4_get_block (STB_GLOBAL)
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
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a582f)
Location: fs/ext4/inode.c:814
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff813a5430-ffffffff813a5448: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813962bf)
Location: fs/ext4/inode.c:814
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff81395ec0-ffffffff81395ed8: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a308f)
Location: fs/ext4/inode.c:814
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff813a2c90-ffffffff813a2ca8: ext4_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b776f)
Location: fs/ext4/inode.c:814
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff813b7370-ffffffff813b7388: ext4_get_block (STB_GLOBAL)
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
