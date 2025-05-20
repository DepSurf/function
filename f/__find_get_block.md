# Function: <code>__find_get_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81243af0)
Location: fs/buffer.c:1365
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff81243af0-ffffffff81243bfe: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126c580)
Location: fs/buffer.c:1355
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff8126c580-ffffffff8126c681: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127fa10)
Location: fs/buffer.c:1355
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff8127fa10-ffffffff8127fc5b: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128cdc0)
Location: fs/buffer.c:1350
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff8128cdc0-ffffffff8128d068: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812afa60)
Location: fs/buffer.c:1310
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff812afa60-ffffffff812afd4b: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1281
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff812daea1-ffffffff812daf02: __find_get_block.cold.61 (STB_LOCAL)
ffffffff812d7d00-ffffffff812d7f99: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff812ece46)
Location: fs/buffer.c:1289
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff812f0381-ffffffff812f03cb: __find_get_block.cold.64 (STB_LOCAL)
ffffffff812ecd40-ffffffff812ed00a: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff8130e5f7)
Location: fs/buffer.c:1290
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff81311c68-ffffffff81311cad: __find_get_block.cold (STB_LOCAL)
ffffffff8130e4f0-ffffffff8130e7be: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff81321617)
Location: fs/buffer.c:1290
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff81324c75-ffffffff81324cba: __find_get_block.cold (STB_LOCAL)
ffffffff81321510-ffffffff813217de: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135b870)
Location: fs/buffer.c:1323
Inline: True
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:write_boundary_block
  - fs/ext4/ialloc.c:recently_deleted
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff8135b870-ffffffff8135b911: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81369e40)
Location: fs/buffer.c:1322
Inline: True
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:write_boundary_block
  - fs/ext4/ialloc.c:recently_deleted
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff81369e40-ffffffff81369ecf: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81370b70)
Location: fs/buffer.c:1327
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff81370b70-ffffffff81370bff: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813c0770)
Location: fs/buffer.c:1302
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff813c0770-ffffffff813c09a6: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814452c0)
Location: fs/buffer.c:1301
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff814452c0-ffffffff81445371: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d4210)
Location: fs/buffer.c:1301
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff814d4210-ffffffff814d42c1: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150c430)
Location: fs/buffer.c:1413
Inline: True
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:write_boundary_block
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff8150c430-ffffffff8150c4e1: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81541070)
Location: fs/buffer.c:1395
Inline: True
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:write_boundary_block
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff81541070-ffffffff81541121: __find_get_block (STB_GLOBAL)
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
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d9d68)
Location: fs/buffer.c:1290
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffff8000103d9d68-ffff8000103da154: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b32ec)
Location: fs/buffer.c:1290
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:write_boundary_block
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
c05b32ec-c05b36c4: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dec00)
Location: fs/buffer.c:1290
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
c0000000004dec00-c0000000004df120: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000292b22)
Location: fs/buffer.c:1290
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffe000292b22-ffffffe000292e34: __find_get_block (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff81319bf7)
Location: fs/buffer.c:1290
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff8131d255-ffffffff8131d29a: __find_get_block.cold (STB_LOCAL)
ffffffff81319af0-ffffffff81319dbe: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff8130a7a6)
Location: fs/buffer.c:1290
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff8130ddf5-ffffffff8130de3a: __find_get_block.cold (STB_LOCAL)
ffffffff8130a6b0-ffffffff8130a952: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff813176c7)
Location: fs/buffer.c:1290
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff8131ad25-ffffffff8131ad6a: __find_get_block.cold (STB_LOCAL)
ffffffff813175c0-ffffffff8131788e: __find_get_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct buffer_head *__find_get_block(struct block_device *bdev, sector_t block, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff813292cc)
Location: fs/buffer.c:1290
Inline: True
Direct callers:
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:write_boundary_block
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/fat/dir.c:fat__get_entry
```
**Symbols:**

```
ffffffff8132c9cb-ffffffff8132ca0b: __find_get_block.cold (STB_LOCAL)
ffffffff813291b0-ffffffff8132948b: __find_get_block (STB_GLOBAL)
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
