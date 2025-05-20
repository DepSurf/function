# Function: <code>__ext4_journal_get_create_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff812cbd00)
Location: fs/ext4/ext4_jbd2.c:239
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
**Symbols:**

```
ffffffff812cbd00-ffffffff812cbd6b: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff812fb630)
Location: fs/ext4/ext4_jbd2.c:239
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
**Symbols:**

```
ffffffff812fb630-ffffffff812fb69b: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813115e0)
Location: fs/ext4/ext4_jbd2.c:239
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
**Symbols:**

```
ffffffff813115e0-ffffffff8131164b: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff812e64f0)
Location: fs/ext4/ext4_jbd2.c:250
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff812e64f0-ffffffff812e6550: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff8130af00)
Location: fs/ext4/ext4_jbd2.c:251
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8130af00-ffffffff8130af60: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81338e70)
Location: fs/ext4/ext4_jbd2.c:244
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81338e70-ffffffff81338eda: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81350120)
Location: fs/ext4/ext4_jbd2.c:244
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81350120-ffffffff8135018a: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81378dc0)
Location: fs/ext4/ext4_jbd2.c:244
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81378dc0-ffffffff81378e2d: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81391180)
Location: fs/ext4/ext4_jbd2.c:244
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81391180-ffffffff813911ed: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813dca10)
Location: fs/ext4/ext4_jbd2.c:306
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813dca10-ffffffff813dca7d: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813ee450)
Location: fs/ext4/ext4_jbd2.c:306
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813ee450-ffffffff813ee4bd: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813f4a10)
Location: fs/ext4/ext4_jbd2.c:306
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813f4a10-ffffffff813f4a7d: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct super_block *sb, struct buffer_head *bh, enum ext4_journal_trigger_type trigger_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81446bf0)
Location: fs/ext4/ext4_jbd2.c:314
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81446bf0-ffffffff81446cc8: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct super_block *sb, struct buffer_head *bh, enum ext4_journal_trigger_type trigger_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff814c2ed0)
Location: fs/ext4/ext4_jbd2.c:314
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff814c2ed0-ffffffff814c2fd3: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct super_block *sb, struct buffer_head *bh, enum ext4_journal_trigger_type trigger_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff8155b250)
Location: fs/ext4/ext4_jbd2.c:319
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8155b250-ffffffff8155b353: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct super_block *sb, struct buffer_head *bh, enum ext4_journal_trigger_type trigger_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81593070)
Location: fs/ext4/ext4_jbd2.c:319
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81593070-ffffffff81593173: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct super_block *sb, struct buffer_head *bh, enum ext4_journal_trigger_type trigger_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff815cbd60)
Location: fs/ext4/ext4_jbd2.c:318
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff815cbd60-ffffffff815cbe63: __ext4_journal_get_create_access (STB_GLOBAL)
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
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffff800010463cc8)
Location: fs/ext4/ext4_jbd2.c:244
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffff800010463cc8-ffff800010463d6c: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (c06242cc)
Location: fs/ext4/ext4_jbd2.c:244
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
c06242cc-c0624344: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (c000000000580f80)
Location: fs/ext4/ext4_jbd2.c:244
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
c000000000580f80-c000000000581020: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffe0002f2464)
Location: fs/ext4/ext4_jbd2.c:244
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffe0002f2464-ffffffe0002f24cc: __ext4_journal_get_create_access (STB_GLOBAL)
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
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81389760)
Location: fs/ext4/ext4_jbd2.c:244
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81389760-ffffffff813897cd: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff8137a1f0)
Location: fs/ext4/ext4_jbd2.c:244
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8137a1f0-ffffffff8137a25d: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813870c0)
Location: fs/ext4/ext4_jbd2.c:244
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813870c0-ffffffff8138712d: __ext4_journal_get_create_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char *where, unsigned int line, handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff8139ada0)
Location: fs/ext4/ext4_jbd2.c:244
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8139ada0-ffffffff8139ae0d: __ext4_journal_get_create_access (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct super_block *sb</code>
</li>
<li>
<b>Param added. </b>
<code>enum ext4_journal_trigger_type trigger_type</code>
</li>
<li>
<b>Param reordered. </b>
<code>where, line, handle, bh</code> ➡️ <code>where, line, handle, sb, bh, trigger_type</code>
</li>
</ul>
</details>
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
