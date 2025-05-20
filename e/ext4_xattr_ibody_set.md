# Function: <code>ext4_xattr_ibody_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff812dccf0)
Location: fs/ext4/xattr.c:1046
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff812dccf0-ffffffff812dcd6c: ext4_xattr_ibody_set.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8130c750)
Location: fs/ext4/xattr.c:1117
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff8130c750-ffffffff8130c7cf: ext4_xattr_ibody_set.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81322670)
Location: fs/ext4/xattr.c:1123
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff81322670-ffffffff813226ef: ext4_xattr_ibody_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8133bfc0)
Location: fs/ext4/xattr.c:2178
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff8133bfc0-ffffffff8133c04a: ext4_xattr_ibody_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813604c0)
Location: fs/ext4/xattr.c:2214
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813604c0-ffffffff8136054a: ext4_xattr_ibody_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8138ed20)
Location: fs/ext4/xattr.c:2230
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff8138ed20-ffffffff8138edaa: ext4_xattr_ibody_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a72e0)
Location: fs/ext4/xattr.c:2225
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813a72e0-ffffffff813a736a: ext4_xattr_ibody_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d1b70)
Location: fs/ext4/xattr.c:2226
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813d1b70-ffffffff813d1bfa: ext4_xattr_ibody_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813eb250)
Location: fs/ext4/xattr.c:2226
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813eb250-ffffffff813eb2da: ext4_xattr_ibody_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81438860)
Location: fs/ext4/xattr.c:2213
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff81438860-ffffffff814388ea: ext4_xattr_ibody_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81451390)
Location: fs/ext4/xattr.c:2217
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff81451390-ffffffff8145141a: ext4_xattr_ibody_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81456ac0)
Location: fs/ext4/xattr.c:2217
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff81456ac0-ffffffff81456b4a: ext4_xattr_ibody_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814ac140)
Location: fs/ext4/xattr.c:2200
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff814ac140-ffffffff814ac1ca: ext4_xattr_ibody_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81534060)
Location: fs/ext4/xattr.c:2214
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff81534060-ffffffff8153414e: ext4_xattr_ibody_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815d2540)
Location: fs/ext4/xattr.c:2233
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff815d2540-ffffffff815d262e: ext4_xattr_ibody_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8160a020)
Location: fs/ext4/xattr.c:2276
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff8160a020-ffffffff8160a10e: ext4_xattr_ibody_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81642d70)
Location: fs/ext4/xattr.c:2276
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff81642d70-ffffffff81642e5e: ext4_xattr_ibody_set (STB_GLOBAL)
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
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c3c28)
Location: fs/ext4/xattr.c:2226
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffff8000104c3c28-ffff8000104c3d40: ext4_xattr_ibody_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c06880a4)
Location: fs/ext4/xattr.c:2226
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
c06880a4-c0688168: ext4_xattr_ibody_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005fb950)
Location: fs/ext4/xattr.c:2226
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
c0000000005fb950-c0000000005fba58: ext4_xattr_ibody_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffe00033ec2a)
Location: fs/ext4/xattr.c:2226
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffe00033ec2a-ffffffe00033ecce: ext4_xattr_ibody_set (STB_LOCAL)
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
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e3830)
Location: fs/ext4/xattr.c:2226
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813e3830-ffffffff813e38ba: ext4_xattr_ibody_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d42b0)
Location: fs/ext4/xattr.c:2226
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813d42b0-ffffffff813d433a: ext4_xattr_ibody_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e0bb0)
Location: fs/ext4/xattr.c:2226
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813e0bb0-ffffffff813e0c3a: ext4_xattr_ibody_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_set(handle_t *handle, struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f5fd0)
Location: fs/ext4/xattr.c:2226
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813f5fd0-ffffffff813f605a: ext4_xattr_ibody_set (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>handle_t *handle</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, i, is</code> ➡️ <code>handle, inode, i, is</code>
</li>
</ul>
</details>
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
