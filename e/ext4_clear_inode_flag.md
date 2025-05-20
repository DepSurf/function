# Function: <code>ext4_clear_inode_flag</code>

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
In fs/ext4/dir.c (ffffffff8129158e)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inode.c (ffffffff8129b56f)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
```
In fs/ext4/ioctl.c (ffffffff812a095f)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812a19f4)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/extents.c (ffffffff812c31b4)
Location: fs/ext4/ext4.h:1504
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff812ccece)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/inline.c (ffffffff812df8d9)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
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
In fs/ext4/dir.c (ffffffff812bead6)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inode.c (ffffffff812cd728)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/ioctl.c (ffffffff812ceea8)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/namei.c (ffffffff812d7a89)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/extents.c (ffffffff812f2b9f)
Location: fs/ext4/ext4.h:1581
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff812fc80c)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/inline.c (ffffffff8130f719)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
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
In fs/ext4/dir.c (ffffffff812d4142)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inode.c (ffffffff812e34e8)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/ioctl.c (ffffffff812e4caf)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/namei.c (ffffffff812ed679)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/extents.c (ffffffff81308b6f)
Location: fs/ext4/ext4.h:1586
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff813127bc)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/inline.c (ffffffff81325539)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
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
In fs/ext4/dir.c (ffffffff812e5bbd)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff812e7336)
Location: fs/ext4/ext4.h:1591
Inline: True
```
```
In fs/ext4/inline.c (ffffffff812f95c1)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813076d5)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/ioctl.c (ffffffff81308625)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff81314255)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff8131d293)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffff8130a5d1)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8130bd36)
Location: fs/ext4/ext4.h:1551
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8131dc01)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8132c328)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/ioctl.c (ffffffff8132d075)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff81338a15)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff813418b3)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffff81338585)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81339441)
Location: fs/ext4/ext4.h:1554
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8134bbe4)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8135aa0f)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/ioctl.c (ffffffff8135b693)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff81366f50)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff8136eabe)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffff8134f81b)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81351051)
Location: fs/ext4/ext4.h:1567
Inline: True
```
```
In fs/ext4/inline.c (ffffffff81363d24)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81372ccf)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/ioctl.c (ffffffff81373913)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff8137f3c6)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff81386f4e)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffff8137843f)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81379e2a)
Location: fs/ext4/ext4.h:1584
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8138d325)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8139c11d)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/ioctl.c (ffffffff8139cf07)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff813a8839)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff813b10ec)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffff81390804)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8139234a)
Location: fs/ext4/ext4.h:1629
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813a5d85)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813b4c2d)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/ioctl.c (ffffffff813b5987)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff813c173f)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff813c9f11)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffff813dbdd2)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813f193f)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff814000d4)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
```
In fs/ext4/ioctl.c (ffffffff814011f4)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff8140da34)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff81415879)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffff813ed318)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8140446b)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81412852)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
```
In fs/ext4/ioctl.c (ffffffff81413ab4)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff81420e80)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff81429293)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffff813f397b)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8140aa4e)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81418cb2)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
```
In fs/ext4/ioctl.c (ffffffff81419d4e)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff81427639)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff8142fd96)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffff81445a3e)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8145d6a8)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8146bed9)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
```
In fs/ext4/ioctl.c (ffffffff8146cf3e)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff8147b2b6)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff814843e6)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffff814c20e3)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff814db8bd)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff814ebd76)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/ioctl.c (ffffffff814ec8eb)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff814fd771)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff81507232)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffff8155a346)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff815742ae)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81585ac6)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/ioctl.c (ffffffff8158666f)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff81597f49)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff815a1cf5)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffff81592117)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff815ac0fe)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff815bc457)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/ioctl.c (ffffffff815bcdac)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff815cea00)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff815d867a)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffff815cae87)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff815e4e93)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff815f5237)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/ioctl.c (ffffffff815f5b85)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff81607280)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff81610cbe)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffff800010463080)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffff800010464b8c)
Location: fs/ext4/ext4.h:1629
Inline: True
```
```
In fs/ext4/inline.c (ffff8000104795ec)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffff80001048931c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/ioctl.c (ffff80001048abd8)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffff800010498bbc)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffff8000104a1a9c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (c062388c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (c06255e8)
Location: fs/ext4/ext4.h:1629
Inline: True
```
```
In fs/ext4/inline.c (c063af24)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (c064b8bc)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/ioctl.c (c064c17c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (c065a7bc)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (c0663c64)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (c0000000005800dc)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (c00000000058275c)
Location: fs/ext4/ext4.h:1629
Inline: True
```
```
In fs/ext4/inline.c (c00000000059ba7c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (c0000000005b0344)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/ioctl.c (c0000000005b150c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (c0000000005c3018)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (c0000000005ce5f8)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffe0002f1c6a)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffe0002f3370)
Location: fs/ext4/ext4.h:1629
Inline: True
```
```
In fs/ext4/inline.c (ffffffe000303e9c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffe000310bec)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/ioctl.c (ffffffe000311728)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffe00031cab6)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffe0003239ec)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffff81388de4)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8138a92a)
Location: fs/ext4/ext4.h:1629
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8139e365)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813ad20d)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/ioctl.c (ffffffff813adf67)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff813b9d1f)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff813c24f1)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffff81379874)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8137b3ba)
Location: fs/ext4/ext4.h:1629
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8138edf5)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8139dc9d)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/ioctl.c (ffffffff8139e9f7)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff813aa7af)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff813b2f81)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffff81386744)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8138828a)
Location: fs/ext4/ext4.h:1629
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8139bbc5)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813aaa6d)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/ioctl.c (ffffffff813ab7c7)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff813b757f)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff813bf9a1)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/dir.c (ffffffff8139a431)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8139bf8a)
Location: fs/ext4/ext4.h:1629
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813b00e5)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813bf3bd)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/ioctl.c (ffffffff813c0167)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff813cc28f)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/namei.c (ffffffff813d4a81)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
</details>
</li>
</ul>

## Differences
