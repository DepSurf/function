# Function: <code>ext4_read_block_bitmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812902c0)
Location: fs/ext4/balloc.c:509
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
```
**Symbols:**

```
ffffffff812902c0-ffffffff81290307: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812bd7e0)
Location: fs/ext4/balloc.c:512
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff812bd7e0-ffffffff812bd827: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812d2e30)
Location: fs/ext4/balloc.c:512
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff812d2e30-ffffffff812d2e77: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812e4440)
Location: fs/ext4/balloc.c:512
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff812e4440-ffffffff812e4487: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81308e70)
Location: fs/ext4/balloc.c:513
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff81308e70-ffffffff81308eb7: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81336d90)
Location: fs/ext4/balloc.c:522
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff81336d90-ffffffff81336de1: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8134e010)
Location: fs/ext4/balloc.c:522
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff8134e010-ffffffff8134e061: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813769d0)
Location: fs/ext4/balloc.c:522
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff813769d0-ffffffff81376a1b: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8138ec40)
Location: fs/ext4/balloc.c:530
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff8138ec40-ffffffff8138ec8b: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813da1e0)
Location: fs/ext4/balloc.c:532
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff813da1e0-ffffffff813da23d: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813ebeb0)
Location: fs/ext4/balloc.c:544
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff813ebeb0-ffffffff813ebf0f: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813f23f0)
Location: fs/ext4/balloc.c:544
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff813f23f0-ffffffff813f243d: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff814443c0)
Location: fs/ext4/balloc.c:544
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff814443c0-ffffffff8144440d: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff814c0290)
Location: fs/ext4/balloc.c:545
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff814c0290-ffffffff814c02e3: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff815582d0)
Location: fs/ext4/balloc.c:545
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff815582d0-ffffffff81558323: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81590040)
Location: fs/ext4/balloc.c:587
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff81590040-ffffffff81590093: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff815c8bd0)
Location: fs/ext4/balloc.c:595
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_context
```
**Symbols:**

```
ffffffff815c8bd0-ffffffff815c8c23: ext4_read_block_bitmap (STB_GLOBAL)
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
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffff800010461150)
Location: fs/ext4/balloc.c:530
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffff800010461150-ffff8000104611f4: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c0621824)
Location: fs/ext4/balloc.c:530
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
c0621824-c0621894: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c00000000057d870)
Location: fs/ext4/balloc.c:530
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
c00000000057d870-c00000000057d908: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffe0002f0448)
Location: fs/ext4/balloc.c:530
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffe0002f0448-ffffffe0002f04a8: ext4_read_block_bitmap (STB_GLOBAL)
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
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81387220)
Location: fs/ext4/balloc.c:530
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff81387220-ffffffff8138726b: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81377cb0)
Location: fs/ext4/balloc.c:530
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff81377cb0-ffffffff81377cfb: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81384cf0)
Location: fs/ext4/balloc.c:530
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff81384cf0-ffffffff81384d3b: ext4_read_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct buffer_head *ext4_read_block_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81398870)
Location: fs/ext4/balloc.c:530
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff81398870-ffffffff813988bb: ext4_read_block_bitmap (STB_GLOBAL)
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
