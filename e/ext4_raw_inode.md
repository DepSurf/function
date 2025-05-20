# Function: <code>ext4_raw_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81299d4b)
Location: fs/ext4/ext4.h:2022
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
```
In fs/ext4/xattr.c (ffffffff812dcd2a)
Location: fs/ext4/ext4.h:2022
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/inline.c (ffffffff812df5ad)
Location: fs/ext4/ext4.h:2022
Inline: True
Inline callers:
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c9392)
Location: fs/ext4/ext4.h:2096
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:2096
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff8130e454)
Location: fs/ext4/ext4.h:2096
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_listxattr
```
```
In fs/ext4/inline.c (ffffffff81312a75)
Location: fs/ext4/ext4.h:2096
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812def7e)
Location: fs/ext4/ext4.h:2081
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:2081
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813241c8)
Location: fs/ext4/ext4.h:2081
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_listxattr
```
```
In fs/ext4/inline.c (ffffffff813289f7)
Location: fs/ext4/ext4.h:2081
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
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
In fs/ext4/inline.c (ffffffff812fc832)
Location: fs/ext4/ext4.h:2101
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff812fd226)
Location: fs/ext4/ext4.h:2101
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:2101
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff8133dcd6)
Location: fs/ext4/ext4.h:2101
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
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
In fs/ext4/inline.c (ffffffff81321092)
Location: fs/ext4/ext4.h:2061
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff81321b06)
Location: fs/ext4/ext4.h:2061
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:2061
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813622b6)
Location: fs/ext4/ext4.h:2061
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
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
In fs/ext4/inline.c (ffffffff8134f16d)
Location: fs/ext4/ext4.h:2062
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff8134fb45)
Location: fs/ext4/ext4.h:2062
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:2062
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813919aa)
Location: fs/ext4/ext4.h:2062
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
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
In fs/ext4/inline.c (ffffffff8136731d)
Location: fs/ext4/ext4.h:2075
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff81367d35)
Location: fs/ext4/ext4.h:2075
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:2075
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813aa5be)
Location: fs/ext4/ext4.h:2075
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
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
In fs/ext4/inline.c (ffffffff813906b3)
Location: fs/ext4/ext4.h:2099
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff81391015)
Location: fs/ext4/ext4.h:2099
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:2099
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813d47d5)
Location: fs/ext4/ext4.h:2099
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
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
In fs/ext4/inline.c (ffffffff813a9113)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff813a9a2a)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:2157
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813edeb5)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
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
In fs/ext4/inline.c (ffffffff813f505d)
Location: fs/ext4/ext4.h:2255
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff813f5b6e)
Location: fs/ext4/ext4.h:2255
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff81400a50)
Location: fs/ext4/ext4.h:2255
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff8143ad79)
Location: fs/ext4/ext4.h:2255
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_xattr_ibody_list
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
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
In fs/ext4/inline.c (ffffffff814077fc)
Location: fs/ext4/ext4.h:2380
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff8140833e)
Location: fs/ext4/ext4.h:2380
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff81413360)
Location: fs/ext4/ext4.h:2380
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff814538e9)
Location: fs/ext4/ext4.h:2380
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_xattr_ibody_list
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
```
In fs/ext4/fast_commit.c (ffffffff814552f9)
Location: fs/ext4/ext4.h:2380
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
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
In fs/ext4/inline.c (ffffffff8140dc6b)
Location: fs/ext4/ext4.h:2432
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff8140e64e)
Location: fs/ext4/ext4.h:2432
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff814195d0)
Location: fs/ext4/ext4.h:2432
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/xattr.c (ffffffff81459209)
Location: fs/ext4/ext4.h:2432
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
```
In fs/ext4/fast_commit.c (ffffffff8145aa39)
Location: fs/ext4/ext4.h:2432
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
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
In fs/ext4/inline.c (ffffffff81460b34)
Location: fs/ext4/ext4.h:2502
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff8146139e)
Location: fs/ext4/ext4.h:2502
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8146c7c0)
Location: fs/ext4/ext4.h:2502
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/xattr.c (ffffffff814ad323)
Location: fs/ext4/ext4.h:2502
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
```
In fs/ext4/fast_commit.c (ffffffff814aec5d)
Location: fs/ext4/ext4.h:2502
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
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
In fs/ext4/inline.c (ffffffff814df50e)
Location: fs/ext4/ext4.h:2507
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_read_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff814dfe6b)
Location: fs/ext4/ext4.h:2507
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff814ece38)
Location: fs/ext4/ext4.h:2507
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/xattr.c (ffffffff815353ce)
Location: fs/ext4/ext4.h:2507
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
```
In fs/ext4/fast_commit.c (ffffffff81537b67)
Location: fs/ext4/ext4.h:2507
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
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
In fs/ext4/inline.c (ffffffff8157862b)
Location: fs/ext4/ext4.h:2517
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_read_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff81579147)
Location: fs/ext4/ext4.h:2517
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff81586c5c)
Location: fs/ext4/ext4.h:2517
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/xattr.c (ffffffff815d380a)
Location: fs/ext4/ext4.h:2517
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
```
In fs/ext4/fast_commit.c (ffffffff815d5ce1)
Location: fs/ext4/ext4.h:2517
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
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
In fs/ext4/inline.c (ffffffff815afb32)
Location: fs/ext4/ext4.h:2511
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_read_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff815b0596)
Location: fs/ext4/ext4.h:2511
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff815bd1bc)
Location: fs/ext4/ext4.h:2511
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/xattr.c (ffffffff8160b3c1)
Location: fs/ext4/ext4.h:2511
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
```
In fs/ext4/fast_commit.c (ffffffff8160d896)
Location: fs/ext4/ext4.h:2511
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
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
In fs/ext4/inline.c (ffffffff815e88e7)
Location: fs/ext4/ext4.h:2529
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_read_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff815e9386)
Location: fs/ext4/ext4.h:2529
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff815f5f85)
Location: fs/ext4/ext4.h:2529
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/xattr.c (ffffffff81644181)
Location: fs/ext4/ext4.h:2529
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
```
In fs/ext4/fast_commit.c (ffffffff81646656)
Location: fs/ext4/ext4.h:2529
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
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
In fs/ext4/inline.c (ffff80001047caa0)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffff80001047d680)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:2157
Inline: True
```
```
In fs/ext4/xattr.c (ffff8000104c5ee0)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
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
In fs/ext4/inline.c (c063e578)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (c063f2a4)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (c064e834)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/xattr.c (c068ae68)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
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
In fs/ext4/inline.c (c0000000005a05b8)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_get_inline_xattr_pos
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (c0000000005a1dc0)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:2157
Inline: True
```
```
In fs/ext4/xattr.c (c0000000005ff3bc)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
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
In fs/ext4/inline.c (ffffffe0003069bc)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffe000307354)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:2157
Inline: True
```
```
In fs/ext4/xattr.c (ffffffe00034116a)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
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
In fs/ext4/inline.c (ffffffff813a16f3)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff813a200a)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:2157
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813e6495)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
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
In fs/ext4/inline.c (ffffffff81392183)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff81392a9a)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:2157
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813d6f15)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
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
In fs/ext4/inline.c (ffffffff8139ef53)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff8139f86a)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:2157
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813e3815)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
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
In fs/ext4/inline.c (ffffffff813b34c3)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff813b3f2a)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:2157
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813f8c25)
Location: fs/ext4/ext4.h:2157
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
</details>
</li>
</ul>

## Differences
