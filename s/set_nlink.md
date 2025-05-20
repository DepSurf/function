# Function: <code>set_nlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81227790)
Location: fs/inode.c:305
Inline: True
Direct callers:
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:make_empty_dir_inode
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/devpts/inode.c:devpts_mount
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff81227790-ffffffff812277d3: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124ff20)
Location: fs/inode.c:312
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/devpts/inode.c:devpts_mount
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff8124ff20-ffffffff8124ff63: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81262fc0)
Location: fs/inode.c:314
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff81262fc0-ffffffff81263003: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81270860)
Location: fs/inode.c:315
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff81270860-ffffffff812708a0: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812931a0)
Location: fs/inode.c:315
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff812931a0-ffffffff812931e0: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8e10)
Location: fs/inode.c:317
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff812b8e10-ffffffff812b8e4e: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cdf50)
Location: fs/inode.c:317
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff812cdf50-ffffffff812cdf8f: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ead90)
Location: fs/inode.c:330
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff812ead90-ffffffff812eadce: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fc8c0)
Location: fs/inode.c:334
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff812fc8c0-ffffffff812fc8fe: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81335160)
Location: fs/inode.c:335
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/kernfs/inode.c:kernfs_refresh_inode
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff81335160-ffffffff8133519e: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81340ad0)
Location: fs/inode.c:336
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/kernfs/inode.c:kernfs_refresh_inode
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff81340ad0-ffffffff81340b0e: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81346f50)
Location: fs/inode.c:336
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/kernfs/inode.c:kernfs_refresh_inode
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff81346f50-ffffffff81346f8e: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813949b0)
Location: fs/inode.c:340
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/kernfs/inode.c:kernfs_refresh_inode
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff813949b0-ffffffff813949ee: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81416b90)
Location: fs/inode.c:364
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/kernfs/inode.c:kernfs_refresh_inode
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff81416b90-ffffffff81416be2: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a2020)
Location: fs/inode.c:362
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/kernfs/inode.c:kernfs_refresh_inode
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff814a2020-ffffffff814a2072: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d71b0)
Location: fs/inode.c:362
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/kernfs/inode.c:kernfs_refresh_inode
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff814d71b0-ffffffff814d7202: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81509530)
Location: fs/inode.c:363
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/kernfs/inode.c:kernfs_refresh_inode
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff81509530-ffffffff81509582: set_nlink (STB_GLOBAL)
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
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103acb38)
Location: fs/inode.c:334
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffff8000103acb38-ffff8000103acbe4: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058d69c)
Location: fs/inode.c:334
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
c058d69c-c058d700: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a7940)
Location: fs/inode.c:334
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
c0000000004a7940-c0000000004a79a8: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000271870)
Location: fs/inode.c:334
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffe000271870-ffffffe0002718cc: set_nlink (STB_GLOBAL)
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
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4ea0)
Location: fs/inode.c:334
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff812f4ea0-ffffffff812f4ede: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e5ac0)
Location: fs/inode.c:334
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff812e5ac0-ffffffff812e5afe: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f2cb0)
Location: fs/inode.c:334
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff812f2cb0-ffffffff812f2cee: set_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void set_nlink(struct inode *inode, unsigned int nlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813043c0)
Location: fs/inode.c:334
Inline: True
Direct callers:
  - fs/libfs.c:make_empty_dir_inode
  - fs/libfs.c:simple_fill_super
  - fs/stack.c:fsstack_copy_attr_all
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/generic.c:proc_getattr
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
**Symbols:**

```
ffffffff813043c0-ffffffff813043fe: set_nlink (STB_GLOBAL)
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
