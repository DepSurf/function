# Function: <code>ext4_xattr_ibody_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff812de370)
Location: fs/ext4/xattr.c:978
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
**Symbols:**

```
ffffffff812de370-ffffffff812de423: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8130dfb0)
Location: fs/ext4/xattr.c:1050
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
**Symbols:**

```
ffffffff8130dfb0-ffffffff8130e076: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81323d30)
Location: fs/ext4/xattr.c:1056
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
**Symbols:**

```
ffffffff81323d30-ffffffff81323df6: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8133d900)
Location: fs/ext4/xattr.c:2111
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
**Symbols:**

```
ffffffff8133d900-ffffffff8133d9bd: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81361ee0)
Location: fs/ext4/xattr.c:2147
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
**Symbols:**

```
ffffffff81361ee0-ffffffff81361f9d: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81390750)
Location: fs/ext4/xattr.c:2178
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff81390750-ffffffff8139081b: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a9330)
Location: fs/ext4/xattr.c:2173
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813a9330-ffffffff813a93fb: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d35a0)
Location: fs/ext4/xattr.c:2174
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813d35a0-ffffffff813d3665: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813ecc80)
Location: fs/ext4/xattr.c:2174
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813ecc80-ffffffff813ecd45: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81439ac0)
Location: fs/ext4/xattr.c:2161
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff81439ac0-ffffffff81439b91: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814525d0)
Location: fs/ext4/xattr.c:2165
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff814525d0-ffffffff814526a1: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81457f60)
Location: fs/ext4/xattr.c:2165
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff81457f60-ffffffff81458031: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814ac060)
Location: fs/ext4/xattr.c:2172
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff814ac060-ffffffff814ac131: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81533f50)
Location: fs/ext4/xattr.c:2185
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff81533f50-ffffffff81534059: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815d2420)
Location: fs/ext4/xattr.c:2204
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff815d2420-ffffffff815d2529: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81609f00)
Location: fs/ext4/xattr.c:2247
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff81609f00-ffffffff8160a00a: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81642c50)
Location: fs/ext4/xattr.c:2247
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff81642c50-ffffffff81642d5a: ext4_xattr_ibody_find (STB_GLOBAL)
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
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c5ba0)
Location: fs/ext4/xattr.c:2174
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffff8000104c5ba0-ffff8000104c5c80: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0689c00)
Location: fs/ext4/xattr.c:2174
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
c0689c00-c0689ce4: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005fdba0)
Location: fs/ext4/xattr.c:2174
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
c0000000005fdba0-c0000000005fdce8: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffe000340230)
Location: fs/ext4/xattr.c:2174
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffe000340230-ffffffe0003402e8: ext4_xattr_ibody_find (STB_GLOBAL)
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
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e5260)
Location: fs/ext4/xattr.c:2174
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813e5260-ffffffff813e5325: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d5ce0)
Location: fs/ext4/xattr.c:2174
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813d5ce0-ffffffff813d5da5: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e25e0)
Location: fs/ext4/xattr.c:2174
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813e25e0-ffffffff813e26a5: ext4_xattr_ibody_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ibody_find(struct inode *inode, struct ext4_xattr_info *i, struct ext4_xattr_ibody_find *is);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f79f0)
Location: fs/ext4/xattr.c:2174
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813f79f0-ffffffff813f7ab5: ext4_xattr_ibody_find (STB_GLOBAL)
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
