# Function: <code>iput</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81227e80)
Location: fs/inode.c:1489
Inline: True
Direct callers:
  - kernel/cgroup.c:__cgroup_procs_write
  - kernel/trace/trace_uprobe.c:free_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_delete
  - fs/dcache.c:d_instantiate_no_diralias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_instantiate_unique
  - fs/dcache.c:d_make_root
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_add_ci
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/bad_inode.c:iget_failed
  - fs/libfs.c:mount_pseudo
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/utimes.c:utimes_common
  - fs/utimes.c:utimes_common
  - fs/nsfs.c:ns_get_path
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/aio.c:SyS_io_setup
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_pid_make_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/devpts/inode.c:devpts_del_ref
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/file.c:fuse_release_end
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:mqueue_get_inode
  - ipc/mqueue.c:SyS_mq_unlink
  - security/selinux/hooks.c:sb_finish_set_opts
  - net/socket.c:sock_release
```
**Symbols:**

```
ffffffff81227e80-ffffffff812280c0: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812505c0)
Location: fs/inode.c:1498
Inline: True
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:free_trace_uprobe
  - kernel/events/core.c:free_filters_list
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_instantiate_no_diralias
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/libfs.c:mount_pseudo
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/utimes.c:utimes_common
  - fs/utimes.c:utimes_common
  - fs/nsfs.c:ns_get_path
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_forget
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_pid_make_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/file.c:fuse_release_end
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - net/socket.c:sock_release
```
**Symbols:**

```
ffffffff812505c0-ffffffff812507ef: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81263660)
Location: fs/inode.c:1527
Inline: True
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:free_trace_uprobe
  - kernel/events/core.c:free_filters_list
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_instantiate_no_diralias
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/libfs.c:mount_pseudo_xattr
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/utimes.c:utimes_common
  - fs/utimes.c:utimes_common
  - fs/nsfs.c:__ns_get_path
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_forget
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_pid_make_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/file.c:fuse_release_end
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - net/socket.c:sock_release
```
**Symbols:**

```
ffffffff81263660-ffffffff8126388f: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81271020)
Location: fs/inode.c:1527
Inline: True
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:free_trace_uprobe
  - kernel/events/core.c:free_filters_list
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_instantiate_no_diralias
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/libfs.c:mount_pseudo_xattr
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/utimes.c:utimes_common
  - fs/utimes.c:utimes_common
  - fs/nsfs.c:__ns_get_path
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bdev_unhash_inode
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/file.c:fuse_release_end
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - net/socket.c:sock_release
```
**Symbols:**

```
ffffffff81271020-ffffffff81271234: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81293940)
Location: fs/inode.c:1527
Inline: True
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:free_trace_uprobe
  - kernel/events/core.c:free_filters_list
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_instantiate_no_diralias
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/libfs.c:mount_pseudo_xattr
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/utimes.c:utimes_common
  - fs/utimes.c:utimes_common
  - fs/nsfs.c:__ns_get_path
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bdev_unhash_inode
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/file.c:fuse_release_end
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - net/socket.c:sock_release
```
**Symbols:**

```
ffffffff81293940-ffffffff81293b5e: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b9c70)
Location: fs/inode.c:1518
Inline: True
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/libfs.c:mount_pseudo_xattr
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bdev_unhash_inode
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/file.c:fuse_release_end
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - net/socket.c:__sock_release
```
**Symbols:**

```
ffffffff812b9c70-ffffffff812b9e7e: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cebe0)
Location: fs/inode.c:1559
Inline: True
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/libfs.c:mount_pseudo_xattr
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bdev_unhash_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/file.c:fuse_release_end
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - net/socket.c:__sock_release
```
**Symbols:**

```
ffffffff812cebe0-ffffffff812cedee: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812ebce2)
Location: fs/inode.c:1572
Inline: True
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bdev_unhash_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/file.c:fuse_release_end
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:__sock_release
```
**Symbols:**

```
ffffffff812ecf9d-ffffffff812ecfcb: iput.cold (STB_LOCAL)
ffffffff812ebb00-ffffffff812ebce4: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fd630)
Location: fs/inode.c:1583
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bdev_unhash_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:__sock_release
```
**Symbols:**

```
ffffffff812fd630-ffffffff812fd83e: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff813373df)
Location: fs/inode.c:1664
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:get_pipe_inode
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:vfs_setxattr
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/utimes.c:utimes_common
  - fs/utimes.c:utimes_common
  - fs/nsfs.c:__ns_get_path
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_acquire
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/crypto/keyring.c:evict_dentries_for_decrypted_inodes
  - fs/crypto/keyring.c:evict_dentries_for_decrypted_inodes
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
  - fs/quota/dquot.c:add_dquot_ref
  - fs/quota/dquot.c:add_dquot_ref
  - fs/quota/dquot.c:add_dquot_ref
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_get_journal
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_bools
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
ffffffff813369f0-ffffffff81336ab1: iput.part.0 (STB_LOCAL)
ffffffff81336ac0-ffffffff81336ae1: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff81342d1f)
Location: fs/inode.c:1665
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:get_pipe_inode
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:vfs_setxattr
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/nsfs.c:__ns_get_path
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get_no_open
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bdev_alloc
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/crypto/keyring.c:evict_dentries_for_decrypted_inodes
  - fs/crypto/keyring.c:evict_dentries_for_decrypted_inodes
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
  - fs/quota/dquot.c:add_dquot_ref
  - fs/quota/dquot.c:add_dquot_ref
  - fs/quota/dquot.c:add_dquot_ref
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_get_journal
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_del_range
  - fs/ext4/fast_commit.c:ext4_fc_replay_del_range
  - fs/ext4/fast_commit.c:ext4_fc_replay_add_range
  - fs/ext4/fast_commit.c:ext4_fc_replay_add_range
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_unlink
  - fs/ext4/fast_commit.c:ext4_fc_replay_unlink
  - fs/ext4/fast_commit.c:ext4_fc_replay_unlink
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_bools
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81342350-ffffffff813423f6: iput.part.0 (STB_LOCAL)
ffffffff81342400-ffffffff81342421: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81348740)
Location: fs/inode.c:1672
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:vfs_setxattr
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/nsfs.c:__ns_get_path
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get_no_open
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bdev_alloc
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/landlock/fs.c:release_inode
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81348740-ffffffff813487ff: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813962d0)
Location: fs/inode.c:1676
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:vfs_setxattr
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/nsfs.c:__ns_get_path
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/landlock/fs.c:release_inode
  - block/bdev.c:iterate_bdevs
  - block/bdev.c:iterate_bdevs
  - block/bdev.c:blkdev_get_no_open
  - block/bdev.c:blkdev_get_no_open
  - block/bdev.c:bdev_alloc
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partitions/core.c:part_release
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff813962d0-ffffffff81396482: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814176d0)
Location: fs/inode.c:1757
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:vfs_setxattr
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/nsfs.c:__ns_get_path
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/landlock/fs.c:release_inode
  - block/bdev.c:sync_bdevs
  - block/bdev.c:sync_bdevs
  - block/bdev.c:blkdev_get_no_open
  - block/bdev.c:bdev_alloc
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partitions/core.c:part_release
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:put_dax
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/mptcp/protocol.c:mptcp_v6_destroy
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff814176d0-ffffffff81417926: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a2e50)
Location: fs/inode.c:1759
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:vfs_setxattr
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/nsfs.c:__ns_get_path
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/landlock/fs.c:release_inode
  - block/bdev.c:sync_bdevs
  - block/bdev.c:sync_bdevs
  - block/bdev.c:blkdev_get_no_open
  - block/bdev.c:bdev_alloc
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partitions/core.c:part_release
  - drivers/dax/super.c:fs_put_dax
  - drivers/dax/super.c:fs_put_dax
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/mptcp/protocol.c:mptcp_destroy
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff814a2e50-ffffffff814a30a6: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d7fa0)
Location: fs/inode.c:1803
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:vfs_setxattr
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/nsfs.c:__ns_get_path
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/landlock/fs.c:release_inode
  - block/bdev.c:sync_bdevs
  - block/bdev.c:sync_bdevs
  - block/bdev.c:blkdev_get_no_open
  - block/bdev.c:bdev_alloc
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partitions/core.c:part_release
  - drivers/dax/super.c:fs_put_dax
  - drivers/dax/super.c:fs_put_dax
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/mptcp/protocol.c:mptcp_destroy
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff814d7fa0-ffffffff814d81f5: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8150a780)
Location: fs/inode.c:1751
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
  - fs/xattr.c:vfs_setxattr
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:ext4_get_journal_inode
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/landlock/fs.c:release_inode
  - block/bdev.c:sync_bdevs
  - block/bdev.c:sync_bdevs
  - block/bdev.c:blkdev_get_no_open
  - block/bdev.c:bdev_alloc
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partitions/core.c:part_release
  - drivers/dax/super.c:fs_put_dax
  - drivers/dax/super.c:fs_put_dax
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/gpu/drm/drm_drv.c:drm_dev_init_release
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff8150a780-ffffffff8150a9d5: iput (STB_GLOBAL)
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
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ae0c8)
Location: fs/inode.c:1583
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bdev_unhash_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__arm64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:__sock_release
```
**Symbols:**

```
ffff8000103ae0c8-ffff8000103ae330: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058e244)
Location: fs/inode.c:1583
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_get_inode
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/utimes.c:utimes_common
  - fs/utimes.c:utimes_common
  - fs/nsfs.c:__ns_get_path
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bdev_unhash_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:__sock_release
```
**Symbols:**

```
c058e244-c058e4cc: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a91d0)
Location: fs/inode.c:1583
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bdev_unhash_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:__sock_release
```
**Symbols:**

```
c0000000004a91d0-c0000000004a9530: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000272978)
Location: fs/inode.c:1583
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_get_inode
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bdev_unhash_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:__sock_release
```
**Symbols:**

```
ffffffe000272978-ffffffe000272c54: iput (STB_GLOBAL)
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
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f5c10)
Location: fs/inode.c:1583
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bdev_unhash_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:__sock_release
```
**Symbols:**

```
ffffffff812f5c10-ffffffff812f5e1e: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e6830)
Location: fs/inode.c:1583
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bdev_unhash_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:__sock_release
```
**Symbols:**

```
ffffffff812e6830-ffffffff812e6a3e: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f3a20)
Location: fs/inode.c:1583
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bdev_unhash_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:__sock_release
```
**Symbols:**

```
ffffffff812f3a20-ffffffff812f3c2e: iput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void iput(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81304e40)
Location: fs/inode.c:1583
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - mm/shmem.c:shmem_fh_to_dentry
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:chmod_common
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:dentry_unlink_inode
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:inode_lru_isolate
  - fs/bad_inode.c:iget_failed
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bdev_unhash_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/aio.c:aio_setup_ring
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_d_iput
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_nfs_get_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_show
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:__sock_release
```
**Symbols:**

```
ffffffff81304e40-ffffffff81305064: iput (STB_GLOBAL)
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
