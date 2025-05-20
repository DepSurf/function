# Function: <code>ext4_quota_capable</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f195b)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff813fc18c)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff8140203e)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inode.c (ffffffff8140e119)
Location: fs/ext4/ext4.h:3393
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
In fs/ext4/ioctl.c (ffffffff814133b3)
Location: fs/ext4/ext4.h:3393
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff8142084e)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff81425d95)
Location: fs/ext4/ext4.h:3393
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
In fs/ext4/super.c (ffffffff8143e7fe)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
```
```
In fs/ext4/xattr.c (ffffffff814524d5)
Location: fs/ext4/ext4.h:3393
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
In fs/ext4/extents.c (ffffffff813f7ddb)
Location: fs/ext4/ext4.h:3458
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff814025ce)
Location: fs/ext4/ext4.h:3458
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff8140843c)
Location: fs/ext4/ext4.h:3458
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inode.c (ffffffff81414500)
Location: fs/ext4/ext4.h:3458
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
In fs/ext4/ioctl.c (ffffffff81419623)
Location: fs/ext4/ext4.h:3458
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/migrate.c (ffffffff81426ffe)
Location: fs/ext4/ext4.h:3458
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8142c994)
Location: fs/ext4/ext4.h:3458
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
In fs/ext4/super.c (ffffffff8144492e)
Location: fs/ext4/ext4.h:3458
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
```
```
In fs/ext4/xattr.c (ffffffff81457e65)
Location: fs/ext4/ext4.h:3458
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
In fs/ext4/extents.c (ffffffff8144a2b9)
Location: fs/ext4/ext4.h:3528
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff81454c94)
Location: fs/ext4/ext4.h:3528
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff8145ae78)
Location: fs/ext4/ext4.h:3528
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inode.c (ffffffff81467880)
Location: fs/ext4/ext4.h:3528
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
In fs/ext4/ioctl.c (ffffffff8146c813)
Location: fs/ext4/ext4.h:3528
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/migrate.c (ffffffff8147ac8e)
Location: fs/ext4/ext4.h:3528
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff81480894)
Location: fs/ext4/ext4.h:3528
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
In fs/ext4/super.c (ffffffff81498760)
Location: fs/ext4/ext4.h:3528
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
```
```
In fs/ext4/xattr.c (ffffffff814abf49)
Location: fs/ext4/ext4.h:3528
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffff814c69fa)
Location: fs/ext4/ext4.h:3491
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff814d247a)
Location: fs/ext4/ext4.h:3491
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff814d8bf8)
Location: fs/ext4/ext4.h:3491
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inode.c (ffffffff814e7524)
Location: fs/ext4/ext4.h:3491
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
In fs/ext4/ioctl.c (ffffffff814ece88)
Location: fs/ext4/ext4.h:3491
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/migrate.c (ffffffff814fd0c4)
Location: fs/ext4/ext4.h:3491
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff815037d1)
Location: fs/ext4/ext4.h:3491
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
In fs/ext4/super.c (ffffffff81523230)
Location: fs/ext4/ext4.h:3491
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff81533e39)
Location: fs/ext4/ext4.h:3491
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffff8155effa)
Location: fs/ext4/ext4.h:3506
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff8156afc2)
Location: fs/ext4/ext4.h:3506
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff81571a08)
Location: fs/ext4/ext4.h:3506
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inode.c (ffffffff81580ee4)
Location: fs/ext4/ext4.h:3506
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
In fs/ext4/ioctl.c (ffffffff81586c9b)
Location: fs/ext4/ext4.h:3506
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/migrate.c (ffffffff81597882)
Location: fs/ext4/ext4.h:3506
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8159e328)
Location: fs/ext4/ext4.h:3506
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
In fs/ext4/super.c (ffffffff815c03f3)
Location: fs/ext4/ext4.h:3506
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff815d22f9)
Location: fs/ext4/ext4.h:3506
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffff81596dbd)
Location: fs/ext4/ext4.h:3485
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff815a2e7b)
Location: fs/ext4/ext4.h:3485
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff815a9798)
Location: fs/ext4/ext4.h:3485
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inode.c (ffffffff815b8494)
Location: fs/ext4/ext4.h:3485
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
In fs/ext4/ioctl.c (ffffffff815bd1fb)
Location: fs/ext4/ext4.h:3485
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/migrate.c (ffffffff815ce2ba)
Location: fs/ext4/ext4.h:3485
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff815d4c38)
Location: fs/ext4/ext4.h:3485
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
In fs/ext4/super.c (ffffffff815f7b72)
Location: fs/ext4/ext4.h:3485
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff81609dd9)
Location: fs/ext4/ext4.h:3485
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/extents.c (ffffffff815cfa6d)
Location: fs/ext4/ext4.h:3505
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
```
```
In fs/ext4/file.c (ffffffff815dbb9b)
Location: fs/ext4/ext4.h:3505
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/indirect.c (ffffffff815e2548)
Location: fs/ext4/ext4.h:3505
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inode.c (ffffffff815f1234)
Location: fs/ext4/ext4.h:3505
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
In fs/ext4/ioctl.c (ffffffff815f5fc4)
Location: fs/ext4/ext4.h:3505
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/migrate.c (ffffffff81606b3a)
Location: fs/ext4/ext4.h:3505
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8160d2e1)
Location: fs/ext4/ext4.h:3505
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
In fs/ext4/super.c (ffffffff81630722)
Location: fs/ext4/ext4.h:3505
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff81642b29)
Location: fs/ext4/ext4.h:3505
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
