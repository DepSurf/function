# Function: <code>ext4_has_feature_quota</code>

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
In fs/ext4/file.c (0)
Location: fs/ext4/ext4.h:1700
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ext4.h:1700
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81295f86)
Location: fs/ext4/ext4.h:1700
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/namei.c (0)
Location: fs/ext4/ext4.h:1700
Inline: True
```
```
In fs/ext4/super.c (ffffffff812ac73a)
Location: fs/ext4/ext4.h:1700
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/extents.c (ffffffff812c6692)
Location: fs/ext4/ext4.h:1700
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/migrate.c (ffffffff812cc36a)
Location: fs/ext4/ext4.h:1700
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: fs/ext4/ext4.h:1700
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: fs/ext4/ext4.h:1700
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: fs/ext4/ext4.h:1700
Inline: True
```
```
In fs/ext4/crypto_policy.c (0)
Location: fs/ext4/ext4.h:1700
Inline: True
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
In fs/ext4/file.c (0)
Location: fs/ext4/ext4.h:1768
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ext4.h:1768
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812c3558)
Location: fs/ext4/ext4.h:1768
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:1768
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: fs/ext4/ext4.h:1768
Inline: True
```
```
In fs/ext4/super.c (ffffffff812e0f8b)
Location: fs/ext4/ext4.h:1768
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:parse_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/extents.c (ffffffff812f638a)
Location: fs/ext4/ext4.h:1768
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/migrate.c (ffffffff812fbcc3)
Location: fs/ext4/ext4.h:1768
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: fs/ext4/ext4.h:1768
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: fs/ext4/ext4.h:1768
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: fs/ext4/ext4.h:1768
Inline: True
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
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ext4.h:1753
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812d8be8)
Location: fs/ext4/ext4.h:1753
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:1753
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: fs/ext4/ext4.h:1753
Inline: True
```
```
In fs/ext4/super.c (ffffffff812f6abb)
Location: fs/ext4/ext4.h:1753
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/extents.c (ffffffff8130c33a)
Location: fs/ext4/ext4.h:1753
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/migrate.c (ffffffff81311c73)
Location: fs/ext4/ext4.h:1753
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: fs/ext4/ext4.h:1753
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: fs/ext4/ext4.h:1753
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: fs/ext4/ext4.h:1753
Inline: True
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
In fs/ext4/extents.c (ffffffff812eab96)
Location: fs/ext4/ext4.h:1758
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (0)
Location: fs/ext4/ext4.h:1758
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: fs/ext4/ext4.h:1758
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812fce88)
Location: fs/ext4/ext4.h:1758
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:1758
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff813136c4)
Location: fs/ext4/ext4.h:1758
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: fs/ext4/ext4.h:1758
Inline: True
```
```
In fs/ext4/super.c (ffffffff8132b024)
Location: fs/ext4/ext4.h:1758
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (ffffffff8133d79a)
Location: fs/ext4/ext4.h:1758
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffff8130f639)
Location: fs/ext4/ext4.h:1718
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (0)
Location: fs/ext4/ext4.h:1718
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: fs/ext4/ext4.h:1718
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81321788)
Location: fs/ext4/ext4.h:1718
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ext4.h:1718
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff81337e84)
Location: fs/ext4/ext4.h:1718
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: fs/ext4/ext4.h:1718
Inline: True
```
```
In fs/ext4/super.c (ffffffff8134f494)
Location: fs/ext4/ext4.h:1718
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (ffffffff81361d7a)
Location: fs/ext4/ext4.h:1718
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffff8133affe)
Location: fs/ext4/ext4.h:1721
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff81343993)
Location: fs/ext4/ext4.h:1721
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff81349e27)
Location: fs/ext4/ext4.h:1721
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inode.c (ffffffff81355835)
Location: fs/ext4/ext4.h:1721
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8135cc0a)
Location: fs/ext4/ext4.h:1721
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff81366777)
Location: fs/ext4/ext4.h:1721
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8136b89e)
Location: fs/ext4/ext4.h:1721
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff8137d902)
Location: fs/ext4/ext4.h:1721
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (ffffffff813905da)
Location: fs/ext4/ext4.h:1721
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffff81352380)
Location: fs/ext4/ext4.h:1734
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff8135bad3)
Location: fs/ext4/ext4.h:1734
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff81361fe7)
Location: fs/ext4/ext4.h:1734
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inode.c (ffffffff8136db65)
Location: fs/ext4/ext4.h:1734
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81375055)
Location: fs/ext4/ext4.h:1734
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff8137ebc7)
Location: fs/ext4/ext4.h:1734
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff81383d5e)
Location: fs/ext4/ext4.h:1734
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff81396102)
Location: fs/ext4/ext4.h:1734
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (ffffffff813a91ba)
Location: fs/ext4/ext4.h:1734
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffff8137bcbe)
Location: fs/ext4/ext4.h:1754
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff81384b90)
Location: fs/ext4/ext4.h:1754
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff8138b403)
Location: fs/ext4/ext4.h:1754
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inode.c (ffffffff81397189)
Location: fs/ext4/ext4.h:1754
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8139e73d)
Location: fs/ext4/ext4.h:1754
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff813a84c8)
Location: fs/ext4/ext4.h:1754
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813ad520)
Location: fs/ext4/ext4.h:1754
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff813c00b3)
Location: fs/ext4/ext4.h:1754
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (ffffffff813d342f)
Location: fs/ext4/ext4.h:1754
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffff8139418e)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff8139d610)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff813a3e53)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inode.c (ffffffff813afbb9)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813b74d5)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff813c10d7)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813c6454)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff813d9383)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (ffffffff813ecb0f)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffff813e00ac)
Location: fs/ext4/ext4.h:1907
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff813e8d17)
Location: fs/ext4/ext4.h:1907
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff813ef8f4)
Location: fs/ext4/ext4.h:1907
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inode.c (ffffffff813fba7c)
Location: fs/ext4/ext4.h:1907
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81400aad)
Location: fs/ext4/ext4.h:1907
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff8140d695)
Location: fs/ext4/ext4.h:1907
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff814128fb)
Location: fs/ext4/ext4.h:1907
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_whiteout_for_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff814257d3)
Location: fs/ext4/ext4.h:1907
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (ffffffff814399df)
Location: fs/ext4/ext4.h:1907
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffff813f1965)
Location: fs/ext4/ext4.h:2032
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff813fc22f)
Location: fs/ext4/ext4.h:2032
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff81402044)
Location: fs/ext4/ext4.h:2032
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inode.c (ffffffff8140e11f)
Location: fs/ext4/ext4.h:2032
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff814133bd)
Location: fs/ext4/ext4.h:2032
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff81420af5)
Location: fs/ext4/ext4.h:2032
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff81425d9b)
Location: fs/ext4/ext4.h:2032
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_whiteout_for_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff8143d153)
Location: fs/ext4/ext4.h:2032
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (ffffffff814524df)
Location: fs/ext4/ext4.h:2032
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffff813f7de5)
Location: fs/ext4/ext4.h:2041
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff81402674)
Location: fs/ext4/ext4.h:2041
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff81408442)
Location: fs/ext4/ext4.h:2041
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inode.c (ffffffff8141450a)
Location: fs/ext4/ext4.h:2041
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8141962d)
Location: fs/ext4/ext4.h:2041
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/migrate.c (ffffffff814272b0)
Location: fs/ext4/ext4.h:2041
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8142cbaa)
Location: fs/ext4/ext4.h:2041
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff81442f93)
Location: fs/ext4/ext4.h:2041
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (ffffffff81457e6f)
Location: fs/ext4/ext4.h:2041
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffff8144a503)
Location: fs/ext4/ext4.h:2107
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff81454d39)
Location: fs/ext4/ext4.h:2107
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff8145ae7e)
Location: fs/ext4/ext4.h:2107
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inode.c (ffffffff8146788a)
Location: fs/ext4/ext4.h:2107
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8146c81d)
Location: fs/ext4/ext4.h:2107
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/migrate.c (ffffffff8147af69)
Location: fs/ext4/ext4.h:2107
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff81480adc)
Location: fs/ext4/ext4.h:2107
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff81496c3e)
Location: fs/ext4/ext4.h:2107
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (ffffffff814abf53)
Location: fs/ext4/ext4.h:2107
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/orphan.c (ffffffff814b1da3)
Location: fs/ext4/ext4.h:2107
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
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
In fs/ext4/extents.c (ffffffff814c6a04)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff814d2539)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff814d8bfe)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inode.c (ffffffff814e7600)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff814ece92)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/migrate.c (ffffffff814fd38c)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff815037d7)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff81521ba0)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_apply_options
```
```
In fs/ext4/xattr.c (ffffffff81533e43)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/orphan.c (ffffffff8153a98e)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
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
In fs/ext4/extents.c (ffffffff8155f004)
Location: fs/ext4/ext4.h:2119
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff8156b08a)
Location: fs/ext4/ext4.h:2119
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff81571a0e)
Location: fs/ext4/ext4.h:2119
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inode.c (ffffffff81580fc0)
Location: fs/ext4/ext4.h:2119
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81586d0e)
Location: fs/ext4/ext4.h:2119
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/migrate.c (ffffffff81597b7c)
Location: fs/ext4/ext4.h:2119
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8159e32e)
Location: fs/ext4/ext4.h:2119
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff815be6ae)
Location: fs/ext4/ext4.h:2119
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_apply_options
```
```
In fs/ext4/xattr.c (ffffffff815d2303)
Location: fs/ext4/ext4.h:2119
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/orphan.c (ffffffff815d8f21)
Location: fs/ext4/ext4.h:2119
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
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
In fs/ext4/extents.c (ffffffff81596dc7)
Location: fs/ext4/ext4.h:2113
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff815a2f43)
Location: fs/ext4/ext4.h:2113
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff815a979e)
Location: fs/ext4/ext4.h:2113
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inode.c (ffffffff815b8570)
Location: fs/ext4/ext4.h:2113
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff815bd26e)
Location: fs/ext4/ext4.h:2113
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/migrate.c (ffffffff815ce5e9)
Location: fs/ext4/ext4.h:2113
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff815d4c3e)
Location: fs/ext4/ext4.h:2113
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff815f53be)
Location: fs/ext4/ext4.h:2113
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_apply_options
```
```
In fs/ext4/xattr.c (ffffffff81609de3)
Location: fs/ext4/ext4.h:2113
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/orphan.c (ffffffff81610abe)
Location: fs/ext4/ext4.h:2113
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
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
In fs/ext4/extents.c (ffffffff815cfa77)
Location: fs/ext4/ext4.h:2131
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff815dbc63)
Location: fs/ext4/ext4.h:2131
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff815e254e)
Location: fs/ext4/ext4.h:2131
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inode.c (ffffffff815f1310)
Location: fs/ext4/ext4.h:2131
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff815f6037)
Location: fs/ext4/ext4.h:2131
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/migrate.c (ffffffff81606e69)
Location: fs/ext4/ext4.h:2131
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8160d2e7)
Location: fs/ext4/ext4.h:2131
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff8162dd0e)
Location: fs/ext4/ext4.h:2131
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_apply_options
```
```
In fs/ext4/xattr.c (ffffffff81642b33)
Location: fs/ext4/ext4.h:2131
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/orphan.c (ffffffff8164987e)
Location: fs/ext4/ext4.h:2131
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
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
In fs/ext4/extents.c (ffff800010466ec4)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffff800010470b04)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffff8000104774c8)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inode.c (ffff800010484684)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffff80001048cf8c)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffff800010498858)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffff80001049df48)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffff8000104acaa8)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (ffff8000104c59ec)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (c06279ec)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/indirect.c (c0638f74)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inode.c (c0645c50)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (c064e87c)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (c0659e80)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (c065fc2c)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (c0675180)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (c0689a74)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (c00000000058504c)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (c000000000591120)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (c000000000599740)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inode.c (c0000000005a996c)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (c0000000005b3b3c)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (c0000000005c2890)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (c0000000005c98a8)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (c0000000005e4c04)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (c0000000005fd920)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffe0002f4e4a)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffe0002fcdcc)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffe000302880)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inode.c (ffffffe00030ca7a)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffe000312e68)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffe00031c852)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffe000320aba)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffe00032fe0a)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (ffffffe0003400e4)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffff8138c76e)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff81395bf0)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff8139c433)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inode.c (ffffffff813a8199)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813afab5)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff813b96b7)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813bea34)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff813d1963)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (ffffffff813e50ef)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffff8137d1fe)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff81386680)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff8138cec3)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inode.c (ffffffff81398c29)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813a0545)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff813aa147)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813af4c4)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff813c23e3)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (ffffffff813d5b6f)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffff8138a0ce)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff81393550)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff81399c93)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inode.c (ffffffff813a59f9)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813ad315)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff813b6f17)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813bc014)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff813cedf3)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (ffffffff813e246f)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffff8139ddfe)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff813a75e0)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff813add83)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inode.c (ffffffff813ba134)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813c1cce)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff813cbc27)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813d0fc4)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff813e4123)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_mark_dquot_dirty
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
```
In fs/ext4/xattr.c (ffffffff813f787f)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
</details>
</li>
</ul>

## Differences
