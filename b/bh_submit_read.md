# Function: <code>bh_submit_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81246940)
Location: fs/buffer.c:3394
Inline: True
Direct callers:
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/indirect.c:ext4_get_branch
```
**Symbols:**

```
ffffffff81246940-ffffffff812469c6: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126f8a0)
Location: fs/buffer.c:3453
Inline: True
Direct callers:
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/indirect.c:ext4_get_branch
```
**Symbols:**

```
ffffffff8126f8a0-ffffffff8126f929: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81282aa0)
Location: fs/buffer.c:3487
Inline: True
Direct callers:
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/indirect.c:ext4_get_branch
```
**Symbols:**

```
ffffffff81282aa0-ffffffff81282b29: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81290190)
Location: fs/buffer.c:3472
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff81290190-ffffffff81290219: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b2ea0)
Location: fs/buffer.c:3440
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff812b2ea0-ffffffff812b2f29: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812dad90)
Location: fs/buffer.c:3411
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff812dad90-ffffffff812dae19: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812f0270)
Location: fs/buffer.c:3423
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff812f0270-ffffffff812f02f9: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81311b40)
Location: fs/buffer.c:3430
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff81311b40-ffffffff81311bcd: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81324b60)
Location: fs/buffer.c:3407
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff81324b60-ffffffff81324bed: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135b3a0)
Location: fs/buffer.c:3418
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff8135b3a0-ffffffff8135b43e: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813694c0)
Location: fs/buffer.c:3399
Inline: True
```
**Symbols:**

```
ffffffff813694c0-ffffffff8136955e: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136f9b0)
Location: fs/buffer.c:3420
Inline: True
```
**Symbols:**

```
ffffffff8136f9b0-ffffffff8136fa4e: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813be5b0)
Location: fs/buffer.c:3372
Inline: True
```
**Symbols:**

```
ffffffff813be5b0-ffffffff813be64e: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81444790)
Location: fs/buffer.c:3357
Inline: False
```
**Symbols:**

```
ffffffff81444790-ffffffff81444830: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103de188)
Location: fs/buffer.c:3407
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffff8000103de188-ffff8000103de268: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b74fc)
Location: fs/buffer.c:3407
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
c05b74fc-c05b75e0: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004e3e20)
Location: fs/buffer.c:3407
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
c0000000004e3e20-c0000000004e3f4c: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000295f6e)
Location: fs/buffer.c:3407
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffe000295f6e-ffffffe000296038: bh_submit_read (STB_GLOBAL)
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
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131d140)
Location: fs/buffer.c:3407
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff8131d140-ffffffff8131d1cd: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130dce0)
Location: fs/buffer.c:3407
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff8130dce0-ffffffff8130dd6d: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131ac10)
Location: fs/buffer.c:3407
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff8131ac10-ffffffff8131ac9d: bh_submit_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int bh_submit_read(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132c8c0)
Location: fs/buffer.c:3407
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff8132c8c0-ffffffff8132c943: bh_submit_read (STB_GLOBAL)
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
