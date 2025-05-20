# Function: <code>mark_buffer_dirty_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81242b10)
Location: fs/buffer.c:603
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81242b10-ffffffff81242bb0: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126ae30)
Location: fs/buffer.c:597
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8126ae30-ffffffff8126aecb: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127df60)
Location: fs/buffer.c:598
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8127df60-ffffffff8127dffb: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128bb00)
Location: fs/buffer.c:595
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8128bb00-ffffffff8128bba5: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ae6b0)
Location: fs/buffer.c:574
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff812ae6b0-ffffffff812ae755: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d7630)
Location: fs/buffer.c:543
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff812d7630-ffffffff812d76d5: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812eb990)
Location: fs/buffer.c:544
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff812eb990-ffffffff812eba38: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130d080)
Location: fs/buffer.c:545
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8130d080-ffffffff8130d128: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81320050)
Location: fs/buffer.c:545
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81320050-ffffffff813200f8: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135a090)
Location: fs/buffer.c:571
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8135a090-ffffffff8135a13d: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813681b0)
Location: fs/buffer.c:570
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff813681b0-ffffffff8136825d: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136ec70)
Location: fs/buffer.c:570
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8136ec70-ffffffff8136ed1a: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813c0340)
Location: fs/buffer.c:570
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff813c0340-ffffffff813c03ed: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81446500)
Location: fs/buffer.c:570
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81446500-ffffffff814465cb: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d55f0)
Location: fs/buffer.c:570
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff814d55f0-ffffffff814d56bb: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff815083e0)
Location: fs/buffer.c:681
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff815083e0-ffffffff815084ab: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153d190)
Location: fs/buffer.c:669
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8153d190-ffffffff8153d25b: mark_buffer_dirty_inode (STB_GLOBAL)
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
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d8bd0)
Location: fs/buffer.c:545
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffff8000103d8bd0-ffff8000103d8ccc: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b1a88)
Location: fs/buffer.c:545
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
c05b1a88-c05b1b2c: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dc490)
Location: fs/buffer.c:545
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
c0000000004dc490-c0000000004dc5cc: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000291732)
Location: fs/buffer.c:545
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffe000291732-ffffffe000291804: mark_buffer_dirty_inode (STB_GLOBAL)
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
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81318630)
Location: fs/buffer.c:545
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81318630-ffffffff813186d8: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81309220)
Location: fs/buffer.c:545
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81309220-ffffffff813092c8: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81316100)
Location: fs/buffer.c:545
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81316100-ffffffff813161a8: mark_buffer_dirty_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head *bh, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81327e30)
Location: fs/buffer.c:545
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat32_ent_put
  - fs/fat/fatent.c:fat16_ent_put
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81327e30-ffffffff81327edb: mark_buffer_dirty_inode (STB_GLOBAL)
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
