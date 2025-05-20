# Function: <code>ext4_new_meta_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8128f5c0)
Location: fs/ext4/balloc.c:628
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8128f5c0-ffffffff8128f6c0: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812bcaf0)
Location: fs/ext4/balloc.c:634
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff812bcaf0-ffffffff812bcbf0: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812d2140)
Location: fs/ext4/balloc.c:634
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff812d2140-ffffffff812d2240: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812e37b0)
Location: fs/ext4/balloc.c:634
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff812e37b0-ffffffff812e38be: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813081a0)
Location: fs/ext4/balloc.c:634
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813081a0-ffffffff813082ae: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813360a0)
Location: fs/ext4/balloc.c:643
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813360a0-ffffffff813361ae: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8134d320)
Location: fs/ext4/balloc.c:643
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8134d320-ffffffff8134d42f: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81375d20)
Location: fs/ext4/balloc.c:643
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81375d20-ffffffff81375e25: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8138df90)
Location: fs/ext4/balloc.c:651
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8138df90-ffffffff8138e095: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813d94b0)
Location: fs/ext4/balloc.c:653
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813d94b0-ffffffff813d95b5: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813eb140)
Location: fs/ext4/balloc.c:679
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813eb140-ffffffff813eb245: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813f1670)
Location: fs/ext4/balloc.c:679
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813f1670-ffffffff813f1775: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:685
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81cc8b39-ffffffff81cc8b75: ext4_new_meta_blocks.cold (STB_LOCAL)
ffffffff814436b0-ffffffff814437cf: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:686
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81e7b879-ffffffff81e7b8b5: ext4_new_meta_blocks.cold (STB_LOCAL)
ffffffff814bf510-ffffffff814bf64e: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:686
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8206c00a-ffffffff8206c046: ext4_new_meta_blocks.cold (STB_LOCAL)
ffffffff81557480-ffffffff815575be: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:728
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff820ebe7f-ffffffff820ebebb: ext4_new_meta_blocks.cold (STB_LOCAL)
ffffffff8158f300-ffffffff8158f43e: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:736
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff821c90e3-ffffffff821c911f: ext4_new_meta_blocks.cold (STB_LOCAL)
ffffffff815c8010-ffffffff815c814e: ext4_new_meta_blocks (STB_GLOBAL)
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
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffff8000104600d0)
Location: fs/ext4/balloc.c:651
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffff8000104600d0-ffff8000104601f4: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c06208e8)
Location: fs/ext4/balloc.c:651
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
c06208e8-c0620a34: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c00000000057c4b0)
Location: fs/ext4/balloc.c:651
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
c00000000057c4b0-c00000000057c618: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffe0002ef774)
Location: fs/ext4/balloc.c:651
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffe0002ef774-ffffffe0002ef85c: ext4_new_meta_blocks (STB_GLOBAL)
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
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81386570)
Location: fs/ext4/balloc.c:651
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81386570-ffffffff81386675: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81377000)
Location: fs/ext4/balloc.c:651
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81377000-ffffffff81377105: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81384040)
Location: fs/ext4/balloc.c:651
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81384040-ffffffff81384145: ext4_new_meta_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ext4_fsblk_t ext4_new_meta_blocks(handle_t *handle, struct inode *inode, ext4_fsblk_t goal, unsigned int flags, long unsigned int *count, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81397ba0)
Location: fs/ext4/balloc.c:651
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81397ba0-ffffffff81397ca5: ext4_new_meta_blocks (STB_GLOBAL)
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
