# Function: <code>bh_uptodate_or_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812443d0)
Location: fs/buffer.c:3376
Inline: True
Direct callers:
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/indirect.c:ext4_get_branch
```
**Symbols:**

```
ffffffff812443d0-ffffffff8124443f: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126c040)
Location: fs/buffer.c:3435
Inline: True
Direct callers:
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/indirect.c:ext4_get_branch
```
**Symbols:**

```
ffffffff8126c040-ffffffff8126c0ad: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127f3b0)
Location: fs/buffer.c:3469
Inline: True
Direct callers:
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/indirect.c:ext4_get_branch
```
**Symbols:**

```
ffffffff8127f3b0-ffffffff8127f41d: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128cc10)
Location: fs/buffer.c:3454
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff8128cc10-ffffffff8128cc79: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812af6b0)
Location: fs/buffer.c:3422
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff812af6b0-ffffffff812af719: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d7070)
Location: fs/buffer.c:3393
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff812d7070-ffffffff812d70dd: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ec7f0)
Location: fs/buffer.c:3405
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff812ec7f0-ffffffff812ec85d: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130def0)
Location: fs/buffer.c:3412
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff8130def0-ffffffff8130df63: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81320ef0)
Location: fs/buffer.c:3389
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff81320ef0-ffffffff81320f63: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135b670)
Location: fs/buffer.c:3400
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff8135b670-ffffffff8135b6f2: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81369c40)
Location: fs/buffer.c:3381
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff81369c40-ffffffff81369cc2: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136fde0)
Location: fs/buffer.c:3402
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff8136fde0-ffffffff8136fe62: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813be7a0)
Location: fs/buffer.c:3354
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff813be7a0-ffffffff813be822: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81445010)
Location: fs/buffer.c:3339
Inline: False
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff81445010-ffffffff814450af: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d4080)
Location: fs/buffer.c:2944
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
```
**Symbols:**

```
ffffffff814d4080-ffffffff814d411d: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150c040)
Location: fs/buffer.c:3082
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
```
**Symbols:**

```
ffffffff8150c040-ffffffff8150c0dd: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81540c40)
Location: fs/buffer.c:3042
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_load_superblock
```
**Symbols:**

```
ffffffff81540c40-ffffffff81540cdd: bh_uptodate_or_lock (STB_GLOBAL)
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
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103da480)
Location: fs/buffer.c:3389
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffff8000103da480-ffff8000103da56c: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b2fe4)
Location: fs/buffer.c:3389
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
c05b2fe4-c05b30c8: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004de760)
Location: fs/buffer.c:3389
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
c0000000004de760-c0000000004de878: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000292534)
Location: fs/buffer.c:3389
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffe000292534-ffffffe0002925c8: bh_uptodate_or_lock (STB_GLOBAL)
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
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813194d0)
Location: fs/buffer.c:3389
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff813194d0-ffffffff81319543: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130a090)
Location: fs/buffer.c:3389
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff8130a090-ffffffff8130a103: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81316fa0)
Location: fs/buffer.c:3389
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff81316fa0-ffffffff81317013: bh_uptodate_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int bh_uptodate_or_lock(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81328f40)
Location: fs/buffer.c:3389
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/resize.c:ext4_get_bitmap
```
**Symbols:**

```
ffffffff81328f40-ffffffff81328fa3: bh_uptodate_or_lock (STB_GLOBAL)
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
