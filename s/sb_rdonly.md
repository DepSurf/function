# Function: <code>sb_rdonly</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (0)
Location: include/linux/fs.h:1889
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/fs.h:1889
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/fs.h:1889
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/fs.h:1889
Inline: True
```
```
In fs/sync.c (0)
Location: include/linux/fs.h:1889
Inline: True
```
```
In fs/proc_namespace.c (0)
Location: include/linux/fs.h:1889
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/fs.h:1889
Inline: True
```
```
In fs/quota/quota.c (ffffffff812e95da)
Location: include/linux/fs.h:1889
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
```
In fs/ext4/ext4_jbd2.c (0)
Location: include/linux/fs.h:1889
Inline: True
```
```
In fs/ext4/file.c (0)
Location: include/linux/fs.h:1889
Inline: True
```
```
In fs/ext4/fsync.c (0)
Location: include/linux/fs.h:1889
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/fs.h:1889
Inline: True
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/fs.h:1889
Inline: True
```
```
In fs/ext4/super.c (ffffffff81359251)
Location: include/linux/fs.h:1889
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
```
```
In fs/fat/fatent.c (0)
Location: include/linux/fs.h:1889
Inline: True
```
```
In fs/fat/inode.c (ffffffff8137fcbc)
Location: include/linux/fs.h:1889
Inline: True
```
```
In fs/fat/misc.c (0)
Location: include/linux/fs.h:1889
Inline: True
```
```
In fs/ecryptfs/main.c (0)
Location: include/linux/fs.h:1889
Inline: True
```
```
In fs/ecryptfs/kthread.c (0)
Location: include/linux/fs.h:1889
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/fs.h:1889
Inline: True
```
```
In security/integrity/evm/evm_main.c (0)
Location: include/linux/fs.h:1889
Inline: True
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
In init/do_mounts.c (ffffffff826cd727)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In fs/super.c (ffffffff8129c522)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:do_remount_sb
  - fs/super.c:do_remount_sb
```
```
In fs/namei.c (ffffffff812a79e2)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/namespace.c (ffffffff812c132d)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (ffffffff812d22b5)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffffffff812e4052)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffffffff81313dd5)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
```
```
In fs/quota/quota.c (ffffffff81316290)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8133883a)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff81343d27)
Location: include/linux/fs.h:1909
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff8134580b)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81348f23)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/mmp.c (ffffffff81367580)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff81387aaf)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/fat/fatent.c (ffffffff813aaff5)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - fs/fat/fatent.c:mark_fsinfo_dirty
```
```
In fs/fat/inode.c (ffffffff813ae18c)
Location: include/linux/fs.h:1909
Inline: True
```
```
In fs/fat/misc.c (ffffffff813b07fd)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffffffff813b5967)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffffffff813bd786)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffffffff813c426f)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readdir
```
```
In security/integrity/evm/evm_main.c (ffffffff814569f6)
Location: include/linux/fs.h:1909
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (ffffffff82883705)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In fs/super.c (ffffffff812b1662)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:do_remount_sb
  - fs/super.c:do_remount_sb
```
```
In fs/namei.c (ffffffff812bca82)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/namespace.c (ffffffff812d65bc)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (ffffffff812e7695)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffffffff812f8cd2)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffffffff8132ad65)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
```
```
In fs/quota/quota.c (ffffffff8132d213)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8134faea)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff8135be67)
Location: include/linux/fs.h:1991
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff8135d95e)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff813610e3)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff8136d47b)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (ffffffff81374777)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mmp.c (ffffffff8137fa00)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813a0613)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/fat/fatent.c (ffffffff813c3d75)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/fat/fatent.c:mark_fsinfo_dirty
```
```
In fs/fat/inode.c (ffffffff813c769c)
Location: include/linux/fs.h:1991
Inline: True
```
```
In fs/fat/misc.c (ffffffff813c9e5d)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffffffff813ceec4)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffffffff813d6dc6)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffffffff813dddb9)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (ffffffff81473e8e)
Location: include/linux/fs.h:1991
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (ffffffff8289a726)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In fs/super.c (ffffffff812ce3a2)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (ffffffff812d9584)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/namespace.c (ffffffff812f4ab7)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (ffffffff81305f45)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffffffff813192f2)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffffffff81352974)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
```
```
In fs/quota/quota.c (ffffffff81354996)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81378777)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff81384f40)
Location: include/linux/fs.h:1997
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff81386b0c)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff8138a17b)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff81396a6b)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (ffffffff8139d25f)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (ffffffff813a8e5b)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813caf6d)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/fat/fatent.c (ffffffff813ee505)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/fat/fatent.c:mark_fsinfo_dirty
```
```
In fs/fat/inode.c (ffffffff813f10fd)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff813f49dd)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffffffff813f9b6f)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffffffff814017a2)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffffffff81409da8)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (ffffffff814a1ba4)
Location: include/linux/fs.h:1997
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (ffffffff8289d705)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In fs/super.c (ffffffff812dfe52)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (ffffffff812eb094)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/namespace.c (ffffffff81306665)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (ffffffff81318fc5)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffffffff8132c122)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffffffff8136acf4)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
```
```
In fs/quota/quota.c (ffffffff8136cd06)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81390b37)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/ext4/file.c (ffffffff8139d9dc)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff8139f55c)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff813a2bbf)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff813af49b)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (ffffffff813b5ccf)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (ffffffff813c1d7b)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813e421a)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/fat/fatent.c (ffffffff814084d5)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/fatent.c:mark_fsinfo_dirty
```
```
In fs/fat/inode.c (ffffffff8140afdd)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8140e8ad)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffffffff81413a3f)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffffffff8141b692)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffffffff8142339e)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (ffffffff814bc874)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (ffffffff82cc3d27)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In fs/super.c (ffffffff8131778d)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (ffffffff81326886)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:may_o_create
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/namespace.c (ffffffff8133b8e1)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/namespace.c:mnt_already_visible
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (ffffffff81352c35)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffffffff81365a04)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffffffff813b335b)
Location: include/linux/fs.h:2045
Inline: True
```
```
In fs/quota/quota.c (ffffffff813b4ba0)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813dc1f7)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff813e8a71)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/fsync.c (ffffffff813eb465)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff813eeced)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff813fb50b)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (ffffffff814016a8)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (ffffffff8140dfc1)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8143167b)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/fat/fatent.c (ffffffff81457477)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/inode.c (ffffffff814591aa)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8145c698)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffffffff81461bdf)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffffffff8146a182)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffffffff814728f7)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (ffffffff8151d114)
Location: include/linux/fs.h:2045
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (ffffffff82fafe52)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In fs/super.c (ffffffff813229ed)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (ffffffff81331cfb)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:may_o_create
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/namespace.c (ffffffff81347781)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/namespace.c:mnt_already_visible
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (ffffffff8135f515)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffffffff813728d4)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffffffff813c494b)
Location: include/linux/fs.h:2015
Inline: True
```
```
In fs/quota/quota.c (ffffffff813c65c0)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813edc87)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff813fb012)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/fsync.c (ffffffff813fd693)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81401462)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff8140dc3b)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (ffffffff81414098)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (ffffffff81421451)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8144a495)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/fat/fatent.c (ffffffff81473837)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/inode.c (ffffffff814754fa)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81bede47)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffffffff8147d74f)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffffffff81484bf2)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffffffff8148d297)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (ffffffff8153a02f)
Location: include/linux/fs.h:2015
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (ffffffff831b9eb5)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In fs/super.c (ffffffff81328aad)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (ffffffff813349fa)
Location: include/linux/fs.h:2221
Inline: True
```
```
In fs/namespace.c (ffffffff81352a8d)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (ffffffff81366005)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffffffff81379285)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffffffff813cb6fb)
Location: include/linux/fs.h:2221
Inline: True
```
```
In fs/quota/quota.c (ffffffff813cd21d)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813f4267)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff814014e2)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/fsync.c (ffffffff81403aa3)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff814079a2)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff81413dfd)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (ffffffff8141a307)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (ffffffff81427b8e)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8144fe09)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/fat/fatent.c (ffffffff81479287)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/inode.c (ffffffff8147af6a)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81bdff51)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffffffff814832f6)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffffffff8148a6a2)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffffffff81492997)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (ffffffff815426e0)
Location: include/linux/fs.h:2221
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (ffffffff8329a0fd)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - init/do_mounts.c:do_mount_root
```
```
In fs/super.c (ffffffff8137607d)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (ffffffff8138233a)
Location: include/linux/fs.h:2275
Inline: True
```
```
In fs/namespace.c (ffffffff813a0e9e)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (ffffffff813b5010)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffffffff813c5de5)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffffffff8141c7ab)
Location: include/linux/fs.h:2275
Inline: True
```
```
In fs/quota/quota.c (ffffffff8141e4dd)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffffffff814463a7)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff81453a62)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/fsync.c (ffffffff81456273)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff8145a24f)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff8146717d)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (ffffffff8146d4fb)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (ffffffff8147b86e)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff814a6a86)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/fat/fatent.c (ffffffff814d074f)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/inode.c (ffffffff814d258a)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81cd05e1)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffffffff814daa76)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffffffff814e1ea2)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffffffff814ea377)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (ffffffff815a25ef)
Location: include/linux/fs.h:2275
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (ffffffff834483bb)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - init/do_mounts.c:do_mount_root
```
```
In fs/super.c (ffffffff813f503c)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (ffffffff814017ee)
Location: include/linux/fs.h:2165
Inline: True
```
```
In fs/namespace.c (ffffffff814246e9)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (ffffffff81439ce5)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffffffff8144d075)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffffffff814920be)
Location: include/linux/fs.h:2165
Inline: True
```
```
In fs/quota/quota.c (ffffffff81496069)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffffffff814c24f5)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff814d0f33)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/fsync.c (ffffffff814d3c70)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff814d7f54)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff814e6d2d)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (ffffffff814ef695)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_overhead
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (ffffffff814fdd5e)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8152b425)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/fat/fatent.c (ffffffff8155d283)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/inode.c (ffffffff8155f54c)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81e83844)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffffffff815683e4)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffffffff815700e0)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffffffff81578f46)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (ffffffff81648c9c)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (ffffffff83e61fec)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - init/do_mounts.c:do_mount_root
```
```
In fs/super.c (ffffffff8147e1ec)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (ffffffff8148b8ee)
Location: include/linux/fs.h:2299
Inline: True
```
```
In fs/namespace.c (ffffffff814b0f48)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (ffffffff814c8045)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffffffff814db635)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffffffff81525d54)
Location: include/linux/fs.h:2299
Inline: True
```
```
In fs/quota/quota.c (ffffffff81529fc9)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8155a755)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff81569973)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/fsync.c (ffffffff8156c8c0)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81570cd4)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff8158053b)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (ffffffff81589945)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_overhead
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (ffffffff8159854f)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff815ca455)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/fat/fatent.c (ffffffff815ff2c3)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/inode.c (ffffffff8160180c)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81604c1f)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffffffff8160bd5e)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffffffff81614fd0)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffffffff8161e556)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (ffffffff81701a75)
Location: include/linux/fs.h:2299
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (ffffffff8368240c)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - init/do_mounts.c:do_mount_root
```
```
In fs/super.c (ffffffff814b319c)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (ffffffff814bf98e)
Location: include/linux/fs.h:1988
Inline: True
```
```
In fs/namespace.c (ffffffff814e5f88)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (ffffffff814fe275)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffffffff8150fbd5)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffffffff8155e224)
Location: include/linux/fs.h:1988
Inline: True
```
```
In fs/quota/quota.c (ffffffff815625a3)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81592575)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff815a1763)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/fsync.c (ffffffff815a475d)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff815a8a56)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff815b7afb)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (ffffffff815c0165)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_overhead
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (ffffffff815cf01f)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff81602d1f)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/fat/fatent.c (ffffffff816372a3)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/inode.c (ffffffff816396fc)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8163cb2f)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffffffff81643c3b)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffffffff8164d04d)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffffffff8165697e)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (ffffffff8173bb0f)
Location: include/linux/fs.h:1988
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (ffffffff838b149c)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - init/do_mounts.c:do_mount_root
```
```
In fs/super.c (ffffffff814e4cab)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (ffffffff814f1e7e)
Location: include/linux/fs.h:2211
Inline: True
```
```
In fs/namespace.c (ffffffff81519db8)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:mnt_get_write_access
```
```
In fs/sync.c (ffffffff81532e75)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffffffff815440cc)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffffffff815948e4)
Location: include/linux/fs.h:2211
Inline: True
```
```
In fs/quota/quota.c (ffffffff81598c93)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffffffff815cb295)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff815da513)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/fsync.c (ffffffff815dd5a0)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ioctl.c (ffffffff815f8f05)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_overhead
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff8162dd1f)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:update_super_work
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/fat/fatent.c (ffffffff81670793)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/inode.c (ffffffff81672bec)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8167609f)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffffffff8167d1cb)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffffffff8168657d)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffffffff816901fe)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (ffffffff8177ca14)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (ffff800011431838)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In fs/super.c (ffff800010386b9c)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (ffff800010394774)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/namespace.c (ffff8000103b9c0c)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (ffff8000103cff58)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffff8000103e7874)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffff800010433c9c)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
```
```
In fs/quota/quota.c (ffff800010436b1c)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffff800010463518)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/ext4/file.c (ffff800010470f40)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/ext4/fsync.c (ffff800010472964)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffff800010476350)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffff800010483dc0)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (ffff80001048a6cc)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (ffff8000104993d8)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffff8000104bd8d4)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/fat/fatent.c (ffff8000104e89b8)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/fatent.c:mark_fsinfo_dirty
```
```
In fs/fat/inode.c (ffff8000104eb9fc)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffff8000104ef558)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffff8000104f4f20)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffff8000104fcae4)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffff800010506840)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (ffff8000105b53d0)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (c1501860)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In fs/super.c (c056f420)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (c0579c54)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/namespace.c (c05975dc)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (c05ab30c)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (c05bf3f8)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (c05fa5e0)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
```
```
In fs/quota/quota.c (c05fe81c)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (c0623bcc)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/ext4/file.c (c0631cb4)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/ext4/fsync.c (c0633dac)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (c0637d30)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (c06453e0)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (c064c944)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (c065af90)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (c0681228)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/fat/fatent.c (c06a6860)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/fatent.c:mark_fsinfo_dirty
```
```
In fs/fat/inode.c (c06a9ca0)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (c06acff8)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (c06b27d0)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (c06ba140)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (c06c28f0)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (c0764564)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (c000000001344bf8)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In fs/super.c (c00000000047cba4)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (c00000000048b180)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/namespace.c (c0000000004b7290)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (c0000000004d2480)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (c0000000004edfa4)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (c000000000543b30)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
```
```
In fs/quota/quota.c (c000000000549194)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (c00000000058058c)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (c000000000591740)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/ext4/fsync.c (c0000000005937e4)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (c0000000005982f8)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (c0000000005a8e74)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (c0000000005b1a80)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (c0000000005c37e8)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (c0000000005f3a60)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/fat/fatent.c (c000000000626630)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/fatent.c:mark_fsinfo_dirty
```
```
In fs/fat/inode.c (c00000000062a3f8)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (c00000000062e7f4)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (c0000000006357c4)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (c00000000063fb70)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (c00000000064bbac)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (c000000000738a6c)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (ffffffe0000014da)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In fs/super.c (ffffffe0002593e8)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (ffffffe000263268)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/namespace.c (ffffffe00027bede)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (ffffffe00028c2aa)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffffffe00029c734)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffffffe0002cf520)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
```
```
In fs/quota/quota.c (ffffffe0002d125c)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffffffe0002f1ed4)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/ext4/file.c (ffffffe0002fd2e8)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/ext4/fsync.c (ffffffe0002fe804)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffe000301c5e)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffe00030c386)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (ffffffe000311ab8)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (ffffffe00031cf86)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffe0003393f6)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/fat/fatent.c (ffffffe000359f0a)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/fatent.c:mark_fsinfo_dirty
```
```
In fs/fat/inode.c (ffffffe00035c290)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffe00035f4c6)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffffffe000363fc6)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffffffe00036b198)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffffffe000372a2e)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (ffffffe0003fc332)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (ffffffff8288b705)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In fs/super.c (ffffffff812d8432)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (ffffffff812e3674)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/namespace.c (ffffffff812fec45)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (ffffffff813115a5)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffffffff81324702)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffffffff813632d4)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
```
```
In fs/quota/quota.c (ffffffff813652e6)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81389117)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/ext4/file.c (ffffffff81395fbc)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff81397b3c)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff8139b19f)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff813a7a7b)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (ffffffff813ae2af)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (ffffffff813ba35b)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813dc7fa)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/fat/fatent.c (ffffffff81400ab5)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/fatent.c:mark_fsinfo_dirty
```
```
In fs/fat/inode.c (ffffffff814035bd)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81406e8d)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffffffff8140c01f)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffffffff81413c72)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffffffff8141b97e)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (ffffffff814b4e54)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (ffffffff82889682)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In fs/super.c (ffffffff812c90b2)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (ffffffff812d42b4)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/namespace.c (ffffffff812ef865)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (ffffffff813021b5)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffffffff813152a2)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffffffff81353f74)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
```
```
In fs/quota/quota.c (ffffffff81355f86)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81379ba7)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/ext4/file.c (ffffffff81386a4c)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff813885cc)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff8138bc2f)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff8139850b)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (ffffffff8139ed3f)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (ffffffff813aadeb)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813cd27a)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/fat/fatent.c (ffffffff813f1535)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/fatent.c:mark_fsinfo_dirty
```
```
In fs/fat/inode.c (ffffffff813f403d)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff813f790d)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffffffff813fca9f)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffffffff814046f2)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffffffff8140c3fe)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (ffffffff814a5874)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (ffffffff8289e705)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In fs/super.c (ffffffff812d6242)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (ffffffff812e1484)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/namespace.c (ffffffff812fca35)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (ffffffff8130f395)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffffffff813221d2)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffffffff81360da4)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
```
```
In fs/quota/quota.c (ffffffff81362db6)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81386a77)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/ext4/file.c (ffffffff8139391c)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff8139549c)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff813989ff)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff813a52db)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (ffffffff813abb0f)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (ffffffff813b7bbb)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813d9c9a)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/fat/fatent.c (ffffffff813fde35)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/fatent.c:mark_fsinfo_dirty
```
```
In fs/fat/inode.c (ffffffff8140093d)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8140420d)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffffffff8140939f)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffffffff81410ff2)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffffffff81417b1e)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (ffffffff814b0ee4)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
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
In init/do_mounts.c (ffffffff8289e70a)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In fs/super.c (ffffffff812e6e02)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:do_emergency_remount_callback
  - fs/super.c:reconfigure_super
  - fs/super.c:reconfigure_super
```
```
In fs/namei.c (ffffffff812f0a64)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/namespace.c (ffffffff8130dd90)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
```
```
In fs/sync.c (ffffffff81320b95)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/sync.c:sync_inodes_one_sb
```
```
In fs/proc_namespace.c (ffffffff81333f32)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/quota/dquot.c (ffffffff81372d24)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
```
```
In fs/quota/quota.c (ffffffff81376466)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8139a748)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/ext4/file.c (ffffffff813a79ac)
Location: include/linux/fs.h:2031
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff813a95bc)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff813ace1a)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/inode.c (ffffffff813b9a1b)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ioctl.c (ffffffff813c04af)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (ffffffff813cc8be)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813eef7a)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_force_commit
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_seq_options_show
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/fat/fatent.c (ffffffff81413ae5)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/fatent.c:mark_fsinfo_dirty
```
```
In fs/fat/inode.c (ffffffff814169ad)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81419e70)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fat/misc.c:__fat_fs_error
```
```
In fs/ecryptfs/main.c (ffffffff8141f05f)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/ecryptfs/kthread.c (ffffffff81426c62)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/fuse/dir.c (ffffffff8142e90e)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In security/integrity/evm/evm_main.c (ffffffff814c9964)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
</details>
</li>
</ul>

## Differences
