# Function: <code>ext4_has_feature_extents</code>

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
In fs/ext4/file.c (ffffffff81291d94)
Location: fs/ext4/ext4.h:1711
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_fault
```
```
In fs/ext4/ialloc.c (ffffffff812949da)
Location: fs/ext4/ext4.h:1711
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8129b91c)
Location: fs/ext4/ext4.h:1711
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff812a12f6)
Location: fs/ext4/ext4.h:1711
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812a464d)
Location: fs/ext4/ext4.h:1711
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_link
```
```
In fs/ext4/super.c (ffffffff812bd795)
Location: fs/ext4/ext4.h:1711
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1711
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff812cc633)
Location: fs/ext4/ext4.h:1711
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/indirect.c (ffffffff812d8858)
Location: fs/ext4/ext4.h:1711
Inline: True
Inline callers:
  - fs/ext4/indirect.c:try_to_extend_transaction
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/xattr.c (ffffffff812de9d2)
Location: fs/ext4/ext4.h:1711
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/inline.c (ffffffff812dfa54)
Location: fs/ext4/ext4.h:1711
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/acl.c (ffffffff812e44b0)
Location: fs/ext4/ext4.h:1711
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/crypto_policy.c (ffffffff812e48e9)
Location: fs/ext4/ext4.h:1711
Inline: True
Inline callers:
  - fs/ext4/crypto_policy.c:ext4_process_policy
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
In fs/ext4/file.c (ffffffff812bf3d2)
Location: fs/ext4/ext4.h:1779
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_fault
```
```
In fs/ext4/ialloc.c (ffffffff812c1f9c)
Location: fs/ext4/ext4.h:1779
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812c9345)
Location: fs/ext4/ext4.h:1779
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff812cff5b)
Location: fs/ext4/ext4.h:1779
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812d3602)
Location: fs/ext4/ext4.h:1779
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
In fs/ext4/super.c (ffffffff812e0ebb)
Location: fs/ext4/ext4.h:1779
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1779
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff812fbf73)
Location: fs/ext4/ext4.h:1779
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/indirect.c (ffffffff8130871d)
Location: fs/ext4/ext4.h:1779
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/xattr.c (ffffffff8130e6c2)
Location: fs/ext4/ext4.h:1779
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/inline.c (ffffffff8130f6e7)
Location: fs/ext4/ext4.h:1779
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/acl.c (ffffffff813143c0)
Location: fs/ext4/ext4.h:1779
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
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
In fs/ext4/ialloc.c (ffffffff812d75e7)
Location: fs/ext4/ext4.h:1764
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812defcf)
Location: fs/ext4/ext4.h:1764
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff812e5d35)
Location: fs/ext4/ext4.h:1764
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812e9352)
Location: fs/ext4/ext4.h:1764
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
In fs/ext4/super.c (ffffffff812f69eb)
Location: fs/ext4/ext4.h:1764
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1764
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff81311f23)
Location: fs/ext4/ext4.h:1764
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/indirect.c (ffffffff8131e70d)
Location: fs/ext4/ext4.h:1764
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/xattr.c (ffffffff81324402)
Location: fs/ext4/ext4.h:1764
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/inline.c (ffffffff81325507)
Location: fs/ext4/ext4.h:1764
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/acl.c (ffffffff8132a3a0)
Location: fs/ext4/ext4.h:1764
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1769
Inline: True
```
```
In fs/ext4/file.c (ffffffff812f11b8)
Location: fs/ext4/ext4.h:1769
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff812f615c)
Location: fs/ext4/ext4.h:1769
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff812f783f)
Location: fs/ext4/ext4.h:1769
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff812f958f)
Location: fs/ext4/ext4.h:1769
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813031cb)
Location: fs/ext4/ext4.h:1769
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81308e2e)
Location: fs/ext4/ext4.h:1769
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff813139d3)
Location: fs/ext4/ext4.h:1769
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff81318b47)
Location: fs/ext4/ext4.h:1769
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
In fs/ext4/super.c (ffffffff8132b30b)
Location: fs/ext4/ext4.h:1769
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1729
Inline: True
```
```
In fs/ext4/file.c (ffffffff81315d64)
Location: fs/ext4/ext4.h:1729
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff8131a7f5)
Location: fs/ext4/ext4.h:1729
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff8131be6d)
Location: fs/ext4/ext4.h:1729
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff8131dbcf)
Location: fs/ext4/ext4.h:1729
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81327bb3)
Location: fs/ext4/ext4.h:1729
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8132dcb4)
Location: fs/ext4/ext4.h:1729
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff8133818c)
Location: fs/ext4/ext4.h:1729
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8133d2d4)
Location: fs/ext4/ext4.h:1729
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
In fs/ext4/super.c (ffffffff8134f775)
Location: fs/ext4/ext4.h:1729
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1732
Inline: True
```
```
In fs/ext4/file.c (ffffffff8134396c)
Location: fs/ext4/ext4.h:1732
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff8134852c)
Location: fs/ext4/ext4.h:1732
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff81349d39)
Location: fs/ext4/ext4.h:1732
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff8134bbb3)
Location: fs/ext4/ext4.h:1732
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8135580a)
Location: fs/ext4/ext4.h:1732
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8135c454)
Location: fs/ext4/ext4.h:1732
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff81366e38)
Location: fs/ext4/ext4.h:1732
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8136b87c)
Location: fs/ext4/ext4.h:1732
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
In fs/ext4/super.c (ffffffff8137dbc1)
Location: fs/ext4/ext4.h:1732
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1745
Inline: True
```
```
In fs/ext4/file.c (ffffffff8135baac)
Location: fs/ext4/ext4.h:1745
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff813606dc)
Location: fs/ext4/ext4.h:1745
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff81361ef9)
Location: fs/ext4/ext4.h:1745
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff81363cf3)
Location: fs/ext4/ext4.h:1745
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8136db3a)
Location: fs/ext4/ext4.h:1745
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813748c4)
Location: fs/ext4/ext4.h:1745
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff8137f2a8)
Location: fs/ext4/ext4.h:1745
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff81383d3c)
Location: fs/ext4/ext4.h:1745
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
In fs/ext4/super.c (ffffffff813963c1)
Location: fs/ext4/ext4.h:1745
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1765
Inline: True
```
```
In fs/ext4/file.c (ffffffff81384ad7)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff81389843)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff8138b2f9)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff8138d2f3)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8139715d)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8139e83e)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813a8728)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813ad4fe)
Location: fs/ext4/ext4.h:1765
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
In fs/ext4/super.c (ffffffff813c03ba)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1822
Inline: True
```
```
In fs/ext4/file.c (ffffffff8139d557)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff813a2172)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff813a3d49)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff813a5d53)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813afb8d)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813b75d9)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813c1615)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813c6432)
Location: fs/ext4/ext4.h:1822
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
In fs/ext4/super.c (ffffffff813d968a)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1919
Inline: True
```
```
In fs/ext4/file.c (ffffffff813e8c70)
Location: fs/ext4/ext4.h:1919
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff813ee255)
Location: fs/ext4/ext4.h:1919
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff813ef8d2)
Location: fs/ext4/ext4.h:1919
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inline.c (ffffffff813f22e3)
Location: fs/ext4/ext4.h:1919
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813fb99b)
Location: fs/ext4/ext4.h:1919
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81401811)
Location: fs/ext4/ext4.h:1919
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff8140d8f5)
Location: fs/ext4/ext4.h:1919
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff814128df)
Location: fs/ext4/ext4.h:1919
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
In fs/ext4/super.c (ffffffff81425ad7)
Location: fs/ext4/ext4.h:1919
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:2044
Inline: True
```
```
In fs/ext4/file.c (ffffffff813fc17e)
Location: fs/ext4/ext4.h:2044
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff81400897)
Location: fs/ext4/ext4.h:2044
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff8140202b)
Location: fs/ext4/ext4.h:2044
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inline.c (ffffffff81404a33)
Location: fs/ext4/ext4.h:2044
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8140e10b)
Location: fs/ext4/ext4.h:2044
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8141420c)
Location: fs/ext4/ext4.h:2044
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff81420d55)
Location: fs/ext4/ext4.h:2044
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff81425d7f)
Location: fs/ext4/ext4.h:2044
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
In fs/ext4/super.c (ffffffff8143d9c9)
Location: fs/ext4/ext4.h:2044
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:2053
Inline: True
```
```
In fs/ext4/file.c (ffffffff814025c0)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff81406d5b)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff81408429)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inline.c (ffffffff8140aff3)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff814144e0)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81419637)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff81427515)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8142c986)
Location: fs/ext4/ext4.h:2053
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
In fs/ext4/super.c (ffffffff81443809)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:2120
Inline: True
```
```
In fs/ext4/file.c (ffffffff81454c86)
Location: fs/ext4/ext4.h:2120
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff814595e9)
Location: fs/ext4/ext4.h:2120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff8145ae65)
Location: fs/ext4/ext4.h:2120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inline.c (ffffffff8145dc5d)
Location: fs/ext4/ext4.h:2120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81467860)
Location: fs/ext4/ext4.h:2120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8146c827)
Location: fs/ext4/ext4.h:2120
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff8147b195)
Location: fs/ext4/ext4.h:2120
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff81480886)
Location: fs/ext4/ext4.h:2120
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
In fs/ext4/super.c (ffffffff814975bb)
Location: fs/ext4/ext4.h:2120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:2122
Inline: True
```
```
In fs/ext4/file.c (ffffffff814d2465)
Location: fs/ext4/ext4.h:2122
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff814d6ffa)
Location: fs/ext4/ext4.h:2122
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff814d8be5)
Location: fs/ext4/ext4.h:2122
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inline.c (ffffffff814db470)
Location: fs/ext4/ext4.h:2122
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff814e7504)
Location: fs/ext4/ext4.h:2122
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff814eceef)
Location: fs/ext4/ext4.h:2122
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff814fd5f6)
Location: fs/ext4/ext4.h:2122
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff815037c3)
Location: fs/ext4/ext4.h:2122
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
In fs/ext4/super.c (ffffffff815233eb)
Location: fs/ext4/ext4.h:2122
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:2132
Inline: True
```
```
In fs/ext4/file.c (ffffffff8156afb1)
Location: fs/ext4/ext4.h:2132
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff8156fd7f)
Location: fs/ext4/ext4.h:2132
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff815719f5)
Location: fs/ext4/ext4.h:2132
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inline.c (ffffffff815740f0)
Location: fs/ext4/ext4.h:2132
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81580ec4)
Location: fs/ext4/ext4.h:2132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81586ca1)
Location: fs/ext4/ext4.h:2132
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff81597dc6)
Location: fs/ext4/ext4.h:2132
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8159e316)
Location: fs/ext4/ext4.h:2132
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
In fs/ext4/super.c (ffffffff815c05bb)
Location: fs/ext4/ext4.h:2132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:2126
Inline: True
```
```
In fs/ext4/file.c (ffffffff815a2e6a)
Location: fs/ext4/ext4.h:2126
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff815a7c00)
Location: fs/ext4/ext4.h:2126
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff815a9785)
Location: fs/ext4/ext4.h:2126
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inline.c (ffffffff815abf40)
Location: fs/ext4/ext4.h:2126
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff815b8474)
Location: fs/ext4/ext4.h:2126
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff815bd201)
Location: fs/ext4/ext4.h:2126
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff815ce838)
Location: fs/ext4/ext4.h:2126
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff815d4c26)
Location: fs/ext4/ext4.h:2126
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
In fs/ext4/super.c (ffffffff815f7d5d)
Location: fs/ext4/ext4.h:2126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:2144
Inline: True
```
```
In fs/ext4/file.c (ffffffff815dbb8a)
Location: fs/ext4/ext4.h:2144
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff815e0a18)
Location: fs/ext4/ext4.h:2144
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff815e2535)
Location: fs/ext4/ext4.h:2144
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
```
```
In fs/ext4/inline.c (ffffffff815e4ce0)
Location: fs/ext4/ext4.h:2144
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff815f1214)
Location: fs/ext4/ext4.h:2144
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff815f5fca)
Location: fs/ext4/ext4.h:2144
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff816070b8)
Location: fs/ext4/ext4.h:2144
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8160d2cf)
Location: fs/ext4/ext4.h:2144
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
In fs/ext4/super.c (ffffffff8163090d)
Location: fs/ext4/ext4.h:2144
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1822
Inline: True
```
```
In fs/ext4/file.c (ffff800010470a50)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffff800010475834)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffff8000104773c4)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffff80001047959c)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffff800010484658)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffff80001048d07c)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffff800010498ae4)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffff80001049df2c)
Location: fs/ext4/ext4.h:1822
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
In fs/ext4/super.c (ffff8000104ace20)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1822
Inline: True
```
```
In fs/ext4/ialloc.c (c0637024)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (c0638f68)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (c063ab50)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (c0645c2c)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (c064e97c)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (c065a6dc)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (c065fc10)
Location: fs/ext4/ext4.h:1822
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
In fs/ext4/super.c (c06754c8)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1822
Inline: True
```
```
In fs/ext4/file.c (c000000000591040)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (c000000000597434)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (c0000000005995dc)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (c00000000059ba24)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (c0000000005a993c)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (c0000000005b3c64)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (c0000000005c2e6c)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (c0000000005c9880)
Location: fs/ext4/ext4.h:1822
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
In fs/ext4/super.c (c0000000005e5120)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1822
Inline: True
```
```
In fs/ext4/file.c (ffffffe0002fcdcc)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffe000301286)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffe00030278a)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffe000303e72)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffe00030ca5a)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffe000312e74)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffe00031c9e4)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffe000320a9e)
Location: fs/ext4/ext4.h:1822
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
In fs/ext4/super.c (ffffffe000330114)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1822
Inline: True
```
```
In fs/ext4/file.c (ffffffff81395b37)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff8139a752)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff8139c329)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff8139e333)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813a816d)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813afbb9)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813b9bf5)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813bea12)
Location: fs/ext4/ext4.h:1822
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
In fs/ext4/super.c (ffffffff813d1c6a)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1822
Inline: True
```
```
In fs/ext4/file.c (ffffffff813865c7)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff8138b1e2)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff8138cdb9)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff8138edc3)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81398bfd)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813a0649)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813aa685)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813af4a2)
Location: fs/ext4/ext4.h:1822
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
In fs/ext4/super.c (ffffffff813c26ea)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1822
Inline: True
```
```
In fs/ext4/file.c (ffffffff81393497)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff81397fb2)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff81399b89)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff8139bb93)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813a59cd)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813ad419)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813b7455)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813bbff2)
Location: fs/ext4/ext4.h:1822
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
In fs/ext4/super.c (ffffffff813cf0fa)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/extents.c (0)
Location: fs/ext4/ext4.h:1822
Inline: True
```
```
In fs/ext4/file.c (ffffffff813a7527)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff813abd8e)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff813adc79)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff813b00b3)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813ba108)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813c1dd2)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813cc165)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813d0fa2)
Location: fs/ext4/ext4.h:1822
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
In fs/ext4/super.c (ffffffff813e442a)
Location: fs/ext4/ext4.h:1822
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_fill_super
```
</details>
</li>
</ul>

## Differences
