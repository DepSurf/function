# Function: <code>ext4_write_unlock_xattr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813249f9)
Location: fs/ext4/xattr.h:130
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/ext4/inline.c (ffffffff81328b99)
Location: fs/ext4/xattr.h:130
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812fcb8b)
Location: fs/ext4/xattr.h:143
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff81303253)
Location: fs/ext4/xattr.h:143
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff8133dc6a)
Location: fs/ext4/xattr.h:143
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813213eb)
Location: fs/ext4/xattr.h:144
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff81327c46)
Location: fs/ext4/xattr.h:144
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff8136224a)
Location: fs/ext4/xattr.h:144
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8134f40a)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff8135589d)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff813909c1)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813675ba)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff8136dbcd)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff813a95a1)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81390969)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff813971f5)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff813d3d86)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a93c9)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff813afc25)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff813ed466)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813f5328)
Location: fs/ext4/xattr.h:156
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff813fba30)
Location: fs/ext4/xattr.h:156
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff8143a224)
Location: fs/ext4/xattr.h:156
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81407ac8)
Location: fs/ext4/xattr.h:156
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff8140e19c)
Location: fs/ext4/xattr.h:156
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff81452d53)
Location: fs/ext4/xattr.h:156
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8140df38)
Location: fs/ext4/xattr.h:156
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff81414579)
Location: fs/ext4/xattr.h:156
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff81458583)
Location: fs/ext4/xattr.h:156
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81460df8)
Location: fs/ext4/xattr.h:156
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff814678f9)
Location: fs/ext4/xattr.h:156
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff814ac68a)
Location: fs/ext4/xattr.h:156
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814df7f9)
Location: fs/ext4/xattr.h:169
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff814e7596)
Location: fs/ext4/xattr.h:169
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff81534812)
Location: fs/ext4/xattr.h:169
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8157893d)
Location: fs/ext4/xattr.h:169
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff81580f56)
Location: fs/ext4/xattr.h:169
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff815d2d3f)
Location: fs/ext4/xattr.h:169
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815afedd)
Location: fs/ext4/xattr.h:169
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff815b8506)
Location: fs/ext4/xattr.h:169
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff8160a81e)
Location: fs/ext4/xattr.h:169
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815e8c8d)
Location: fs/ext4/xattr.h:169
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff815f12a6)
Location: fs/ext4/xattr.h:169
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff816435bb)
Location: fs/ext4/xattr.h:169
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffff80001047ccd0)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffff8000104846f0)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffff8000104c5f90)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063e778)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (c0645cc4)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (c0689fb0)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c0000000005a0854)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (c0000000005a99f4)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (c0000000005fe418)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffe000306b3e)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffe00030cad6)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffe000340528)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a19a9)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff813a8205)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff813e5a46)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81392439)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff81398c95)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff813d64c6)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139f209)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff813a5a65)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff813e2dc6)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813b3779)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
```
In fs/ext4/inode.c (ffffffff813ba1a0)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
```
In fs/ext4/xattr.c (ffffffff813f81d6)
Location: fs/ext4/xattr.h:155
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
</ul>

## Differences
