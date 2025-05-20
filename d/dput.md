# Function: <code>dput</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81223810)
Location: fs/dcache.c:749
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_mount
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_rename2
  - fs/file_table.c:__fput
  - fs/super.c:mount_fs
  - fs/namei.c:lookup_real
  - fs/namei.c:lookup_real
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_down
  - fs/namei.c:follow_mount
  - fs/namei.c:done_path_create
  - fs/namei.c:done_path_create
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:unlazy_walk
  - fs/namei.c:unlazy_walk
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:trailing_symlink
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_dotdot
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:nd_jump_link
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_add_ci
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:drop_mountpoint
  - fs/namespace.c:SyS_oldumount
  - fs/libfs.c:dcache_dir_close
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/nsfs.c:ns_get_path
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:devpts_get_priv
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_unlink
  - security/inode.c:securityfs_create_file
  - security/inode.c:securityfs_remove
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:common_lsm_audit
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff81223810-ffffffff81223a27: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124be70)
Location: fs/dcache.c:751
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_mount
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/super.c:mount_fs
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:unlazy_walk
  - fs/namei.c:unlazy_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:drop_mountpoint
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/nsfs.c:ns_get_path
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_mount
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:failed_creating
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:common_lsm_audit
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff8124be70-ffffffff8124c0da: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125ee50)
Location: fs/dcache.c:751
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_mount
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/super.c:mount_fs
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:unlazy_walk
  - fs/namei.c:unlazy_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:drop_mountpoint
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/nsfs.c:__ns_get_path
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:failed_creating
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:common_lsm_audit
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff8125ee50-ffffffff8125f0ba: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff8126db46)
Location: fs/dcache.c:785
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_mount
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/super.c:mount_fs
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:path_lookupat
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:drop_mountpoint
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/nsfs.c:__ns_get_path
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:debugfs_lookup
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:common_lsm_audit
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aafs_create
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff8126c810-ffffffff8126c9e3: dput.part.23 (STB_LOCAL)
ffffffff8126c9f0-ffffffff8126ca07: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812905e6)
Location: fs/dcache.c:797
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_invalidate
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_mount
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/super.c:mount_fs
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:path_lookupat
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_invalidate
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:drop_mountpoint
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/nsfs.c:__ns_get_path
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:debugfs_lookup
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:common_lsm_audit
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff8128eb60-ffffffff8128ed39: dput.part.22 (STB_LOCAL)
ffffffff8128ed40-ffffffff8128ed57: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812b7a21)
Location: fs/dcache.c:827
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_mount
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/super.c:mount_fs
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:drop_mountpoint
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:debugfs_lookup
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:dump_common_audit_data
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812b5df0-ffffffff812b5f04: dput.part.34 (STB_LOCAL)
ffffffff812b5f10-ffffffff812b5f20: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812ccb81)
Location: fs/dcache.c:840
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_mount
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/super.c:mount_fs
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:drop_mountpoint
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:debugfs_lookup
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:dump_common_audit_data
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812cb370-ffffffff812cb484: dput.part.33 (STB_LOCAL)
ffffffff812cb490-ffffffff812cb4a0: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:840
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/debugfs/inode.c:debugfs_lookup
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:dump_common_audit_data
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812e9e06-ffffffff812e9e2c: dput.cold (STB_LOCAL)
ffffffff812e7880-ffffffff812e7b7b: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f9420)
Location: fs/dcache.c:840
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/super.c:vfs_get_super
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/debugfs/inode.c:debugfs_lookup
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:dump_common_audit_data
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812f9420-ffffffff812f970f: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81332a50)
Location: fs/dcache.c:859
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_tmpfile
  - fs/namei.c:do_tmpfile
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:atomic_open
  - fs/namei.c:atomic_open
  - fs/namei.c:atomic_open
  - fs/namei.c:path_pts
  - fs/namei.c:path_pts
  - fs/namei.c:path_pts
  - fs/namei.c:lookup_positive_unlocked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:follow_dotdot
  - fs/namei.c:follow_dotdot
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:choose_mountpoint
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:unlazy_child
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:find_next_child
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/nsfs.c:__ns_get_path
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/crypto/keyring.c:evict_dentries_for_decrypted_inodes
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:create_default_group
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:mknod_ptmx
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_parent
  - fs/ext4/fsync.c:ext4_sync_parent
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup_interpose
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_perm_files
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:dump_common_audit_data
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - security/apparmor/apparmorfs.c:aafs_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff81332a50-ffffffff81332bb5: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133dfb0)
Location: fs/dcache.c:866
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/bpf/inode.c:bpf_iter_link_pin_kernel
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_tmpfile
  - fs/namei.c:do_tmpfile
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:atomic_open
  - fs/namei.c:atomic_open
  - fs/namei.c:atomic_open
  - fs/namei.c:path_pts
  - fs/namei.c:path_pts
  - fs/namei.c:path_pts
  - fs/namei.c:lookup_positive_unlocked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:follow_dotdot
  - fs/namei.c:follow_dotdot
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:choose_mountpoint
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:unlazy_child
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:path_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:find_next_child
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/nsfs.c:__ns_get_path
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/keyring.c:evict_dentries_for_decrypted_inodes
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:create_default_group
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:mknod_ptmx
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_parent
  - fs/ext4/fsync.c:ext4_sync_parent
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup_interpose
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_perm_files
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:dump_common_audit_data
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - security/apparmor/apparmorfs.c:aafs_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff8133dfb0-ffffffff8133e127: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813443a0)
Location: fs/dcache.c:869
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:path_pts
  - fs/namei.c:path_pts
  - fs/namei.c:path_pts
  - fs/namei.c:lookup_positive_unlocked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:path_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:dcache_dir_close
  - fs/nsfs.c:__ns_get_path
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:create_default_group
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff813443a0-ffffffff81344517: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81391e90)
Location: fs/dcache.c:869
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:path_pts
  - fs/namei.c:path_pts
  - fs/namei.c:path_pts
  - fs/namei.c:lookup_positive_unlocked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:path_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:dcache_dir_close
  - fs/nsfs.c:__ns_get_path
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:create_default_group
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff81391e90-ffffffff81392007: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814138d0)
Location: fs/dcache.c:894
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:path_pts
  - fs/namei.c:path_pts
  - fs/namei.c:path_pts
  - fs/namei.c:lookup_positive_unlocked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:path_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:dcache_dir_close
  - fs/nsfs.c:__ns_get_path
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:create_default_group
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:__ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:check_access_path_dual
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff814138d0-ffffffff81413be3: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149ecd0)
Location: fs/dcache.c:894
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/super.c:vfs_get_super
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:path_pts
  - fs/namei.c:path_pts
  - fs/namei.c:path_pts
  - fs/namei.c:lookup_positive_unlocked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:path_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:dcache_dir_close
  - fs/nsfs.c:__ns_get_path
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:create_default_group
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:__ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff8149ecd0-ffffffff8149efe3: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d3ff0)
Location: fs/dcache.c:894
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/super.c:vfs_get_super
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:path_pts
  - fs/namei.c:path_pts
  - fs/namei.c:path_pts
  - fs/namei.c:lookup_positive_unlocked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_one_qstr_excl
  - fs/namei.c:lookup_dcache
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:path_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:dcache_dir_close
  - fs/nsfs.c:__ns_get_path
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:create_default_group
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:__ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff814d3ff0-ffffffff814d4303: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff815066d0)
Location: fs/dcache.c:833
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:path_pts
  - fs/namei.c:path_pts
  - fs/namei.c:path_pts
  - fs/namei.c:lookup_positive_unlocked
  - fs/namei.c:__kern_path_locked
  - fs/namei.c:__kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_one_qstr_excl
  - fs/namei.c:lookup_dcache
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:path_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:offset_iterate_dir
  - fs/libfs.c:offset_iterate_dir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:dcache_dir_close
  - fs/nsfs.c:__ns_get_path
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:create_default_group
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:__ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/event_inode.c:eventfs_remove_events_dir
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff815066d0-ffffffff81506875: dput (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a7880)
Location: fs/dcache.c:840
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/super.c:vfs_get_super
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/debugfs/inode.c:debugfs_lookup
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__arm64_sys_mq_unlink
  - ipc/mqueue.c:__arm64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:dump_common_audit_data
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffff8000103a7880-ffff8000103a7c90: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c05898cc)
Location: fs/dcache.c:840
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/super.c:vfs_get_super
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:kern_path_locked
  - fs/namei.c:path_lookupat
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/nsfs.c:__ns_get_path
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:detach_groups
  - fs/configfs/dir.c:detach_groups
  - fs/configfs/dir.c:detach_attrs
  - fs/configfs/dir.c:configfs_remove_dir
  - fs/configfs/dir.c:configfs_remove_dir
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/debugfs/inode.c:debugfs_lookup
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:dump_common_audit_data
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
c05898cc-c0589c84: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a2910)
Location: fs/dcache.c:840
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/super.c:vfs_get_super
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/debugfs/inode.c:debugfs_lookup
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:dump_common_audit_data
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
c0000000004a2910-c0000000004a2eb4: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026dff8)
Location: fs/dcache.c:840
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/super.c:vfs_get_super
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:path_lookupat
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/debugfs/inode.c:debugfs_lookup
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:dump_common_audit_data
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffe00026dff8-ffffffe00026e2e8: dput (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f1a00)
Location: fs/dcache.c:840
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/super.c:vfs_get_super
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/debugfs/inode.c:debugfs_lookup
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:dump_common_audit_data
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812f1a00-ffffffff812f1cef: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e2630)
Location: fs/dcache.c:840
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/super.c:vfs_get_super
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/debugfs/inode.c:debugfs_lookup
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:dump_common_audit_data
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812e2630-ffffffff812e291f: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ef810)
Location: fs/dcache.c:840
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/super.c:vfs_get_super
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/debugfs/inode.c:debugfs_lookup
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:dump_common_audit_data
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812ef810-ffffffff812efaff: dput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dput(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81300ce0)
Location: fs/dcache.c:840
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - fs/file_table.c:__fput
  - fs/super.c:vfs_get_super
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:__lookup_hash
  - fs/namei.c:lookup_dcache
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:cleanup_mnt
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:dcache_dir_close
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:fc_drop_locked
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/symlink.c:configfs_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/debugfs/inode.c:debugfs_lookup
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_unlink
  - security/commoncap.c:cap_inode_getsecurity
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/lsm_audit.c:dump_common_audit_data
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff81300ce0-ffffffff81300fcd: dput (STB_GLOBAL)
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
