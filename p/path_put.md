# Function: <code>path_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812164e0)
Location: fs/namei.c:488
Inline: True
Inline callers:
  - fs/namei.c:done_path_create
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:follow_managed
  - fs/namei.c:trailing_symlink
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_create
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_unlinkat
  - fs/namei.c:nd_jump_link
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
Direct callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/shmem.c:__shmem_file_setup
  - fs/open.c:do_sys_truncate
  - fs/open.c:do_dentry_open
  - fs/open.c:SyS_access
  - fs/open.c:SyS_access
  - fs/open.c:SyS_access
  - fs/open.c:SyS_access
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_lchown
  - fs/stat.c:vfs_fstatat
  - fs/stat.c:SyS_readlink
  - fs/stat.c:SyS_readlink
  - fs/pipe.c:create_pipe_files
  - fs/namespace.c:lock_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:set_fs_root
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:free_fs_struct
  - fs/statfs.c:user_statfs
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
  - fs/aio.c:SyS_io_setup
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/quota/quota.c:SyS_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/mqueue.c:SyS_mq_open
  - security/keys/big_key.c:big_key_free_preparse
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/path.c:aa_path_name
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_new_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/socket.c:sock_alloc_file
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812164e0-ffffffff81216501: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81245e80)
Location: fs/namei.c:498
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_set_addr_filter
  - mm/shmem.c:__shmem_file_setup
  - fs/open.c:do_dentry_open
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
  - fs/open.c:SyS_access
  - fs/open.c:SyS_access
  - fs/open.c:SyS_access
  - fs/open.c:do_sys_truncate
  - fs/stat.c:SyS_readlink
  - fs/stat.c:SyS_readlink
  - fs/stat.c:SyS_readlink
  - fs/stat.c:vfs_fstatat
  - fs/pipe.c:create_pipe_files
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/quota/quota.c:SyS_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/mqueue.c:SyS_mq_open
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/path.c:aa_path_name
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/socket.c:sock_alloc_file
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff8123d310-ffffffff8123d331: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81258dd8)
Location: fs/namei.c:498
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_set_addr_filter
  - mm/shmem.c:__shmem_file_setup
  - fs/open.c:do_dentry_open
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
  - fs/open.c:SyS_access
  - fs/open.c:SyS_access
  - fs/open.c:SyS_access
  - fs/open.c:do_sys_truncate
  - fs/stat.c:SyS_readlink
  - fs/stat.c:SyS_readlink
  - fs/stat.c:vfs_fstatat
  - fs/pipe.c:create_pipe_files
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/quota/quota.c:SyS_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/mqueue.c:SyS_mq_open
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/path.c:aa_path_name
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/socket.c:sock_alloc_file
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff812500b0-ffffffff812500d1: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81264f13)
Location: fs/namei.c:498
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/open.c:do_dentry_open
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
  - fs/open.c:SyS_access
  - fs/open.c:SyS_access
  - fs/open.c:SyS_access
  - fs/stat.c:SyS_readlink
  - fs/stat.c:SyS_readlink
  - fs/stat.c:vfs_statx
  - fs/pipe.c:create_pipe_files
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/quota/quota.c:SyS_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/path.c:aa_path_name
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/socket.c:sock_alloc_file
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff8125c000-ffffffff8125c021: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812877a3)
Location: fs/namei.c:498
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_fill_ns_link_info
  - fs/open.c:do_dentry_open
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
  - fs/open.c:SyS_access
  - fs/open.c:SyS_access
  - fs/open.c:SyS_access
  - fs/stat.c:SyS_readlink
  - fs/stat.c:SyS_readlink
  - fs/stat.c:vfs_statx
  - fs/pipe.c:create_pipe_files
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/quota/quota.c:SyS_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/path.c:aa_path_name
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/socket.c:sock_alloc_file
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff8127e3c0-ffffffff8127e3e1: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ac835)
Location: fs/namei.c:482
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:free_trace_uprobe
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:free_filters_list
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/pipe.c:create_pipe_files
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/path.c:aa_path_name
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/socket.c:sock_alloc_file
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff812a5160-ffffffff812a5181: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c1935)
Location: fs/namei.c:482
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:free_filters_list
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/path.c:aa_path_name
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff812ba2d0-ffffffff812ba2f1: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dde92)
Location: fs/namei.c:480
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:free_filters_list
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff812d6ec0-ffffffff812d6ee1: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ef9b2)
Location: fs/namei.c:480
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:free_filters_list
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff812e8a30-ffffffff812e8a51: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81327c9b)
Location: fs/namei.c:494
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_tmpfile
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:follow_dotdot
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:choose_mountpoint
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_do_get
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_fill_ns_link_info
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/exec.c:kernel_read_file_from_path_initns
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__do_sys_fspick
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_exit
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_open_file
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81320be0-ffffffff81320c04: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81334787)
Location: fs/namei.c:494
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_tmpfile
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:follow_dotdot
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:choose_mountpoint
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_do_get
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_fill_ns_link_info
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__do_sys_fspick
  - fs/init.c:init_utimes
  - fs/init.c:init_link
  - fs/init.c:init_stat
  - fs/init.c:init_eaccess
  - fs/init.c:init_chmod
  - fs/init.c:init_chown
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/init.c:init_mount
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/block_dev.c:lookup_bdev
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_exit
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_open_file
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff8132c170-ffffffff8132c194: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8133a874)
Location: fs/namei.c:544
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_fill_ns_link_info
  - kernel/events/core.c:_perf_ioctl
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__do_sys_fspick
  - fs/init.c:init_utimes
  - fs/init.c:init_link
  - fs/init.c:init_stat
  - fs/init.c:init_eaccess
  - fs/init.c:init_chmod
  - fs/init.c:init_chown
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/init.c:init_mount
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/block_dev.c:lookup_bdev
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:__ia32_sys_quotactl_path
  - fs/quota/quota.c:__x64_sys_quotactl_path
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff813321b0-ffffffff813321d4: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813884c4)
Location: fs/namei.c:555
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_fill_ns_link_info
  - kernel/events/core.c:_perf_ioctl
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__do_sys_fspick
  - fs/init.c:init_utimes
  - fs/init.c:init_link
  - fs/init.c:init_stat
  - fs/init.c:init_eaccess
  - fs/init.c:init_chmod
  - fs/init.c:init_chown
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/init.c:init_mount
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
  - block/bdev.c:lookup_bdev
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff8137f940-ffffffff8137f964: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814094d2)
Location: fs/namei.c:556
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:audit_reset_context
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_fill_ns_link_info
  - kernel/events/core.c:_perf_ioctl
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_sys_truncate
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/init.c:init_utimes
  - fs/init.c:init_link
  - fs/init.c:init_stat
  - fs/init.c:init_eaccess
  - fs/init.c:init_chmod
  - fs/init.c:init_chown
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/init.c:init_mount
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/ext4/super.c:ext4_parse_param
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - block/bdev.c:lookup_bdev
  - io_uring/io_uring.c:io_setxattr
  - io_uring/io_uring.c:io_getxattr
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff813ffaf0-ffffffff813ffb1a: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81493b82)
Location: fs/namei.c:556
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:audit_reset_context
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_fill_ns_link_info
  - kernel/events/core.c:_perf_ioctl
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_sys_truncate
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/init.c:init_utimes
  - fs/init.c:init_link
  - fs/init.c:init_stat
  - fs/init.c:init_eaccess
  - fs/init.c:init_chmod
  - fs/init.c:init_chown
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/init.c:init_mount
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/ext4/super.c:ext4_parse_param
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
  - security/landlock/fs.c:is_access_to_paths_allowed
  - block/bdev.c:lookup_bdev
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_getxattr
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81489ad0-ffffffff81489afa: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c8bca)
Location: fs/namei.c:559
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:audit_reset_context
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_fill_ns_link_info
  - kernel/events/core.c:_perf_ioctl
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_sys_truncate
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_move_mount
  - fs/namespace.c:__do_sys_move_mount
  - fs/namespace.c:__do_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:do_lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/init.c:init_utimes
  - fs/init.c:init_link
  - fs/init.c:init_stat
  - fs/init.c:init_eaccess
  - fs/init.c:init_chmod
  - fs/init.c:init_chown
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/init.c:init_mount
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/ext4/super.c:ext4_parse_param
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount_old
  - security/apparmor/mount.c:aa_bind_mount
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
  - security/landlock/fs.c:is_access_to_paths_allowed
  - block/bdev.c:lookup_bdev
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_getxattr
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff814beac0-ffffffff814beaea: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814fb47a)
Location: fs/namei.c:560
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:__kern_path_locked
  - fs/namei.c:__kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:audit_reset_context
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_dealloc
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_fill_ns_link_info
  - kernel/events/core.c:_perf_ioctl
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:__x64_sys_truncate
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_listmount
  - fs/namespace.c:__x64_sys_listmount
  - fs/namespace.c:__do_sys_statmount
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_move_mount
  - fs/namespace.c:__do_sys_move_mount
  - fs/namespace.c:__do_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:do_lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/init.c:init_utimes
  - fs/init.c:init_link
  - fs/init.c:init_stat
  - fs/init.c:init_eaccess
  - fs/init.c:init_chmod
  - fs/init.c:init_chown
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/init.c:init_mount
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/ext4/super.c:ext4_parse_param
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount_old
  - security/apparmor/mount.c:aa_bind_mount
  - security/landlock/syscalls.c:add_rule_path_beneath
  - security/landlock/fs.c:is_access_to_paths_allowed
  - block/bdev.c:lookup_bdev
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_getxattr
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff814f0f40-ffffffff814f0f6a: path_put (STB_GLOBAL)
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
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010399160)
Location: fs/namei.c:480
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:free_filters_list
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_move_mount
  - fs/namespace.c:__arm64_sys_move_mount
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__arm64_sys_fspick
  - fs/fsopen.c:__arm64_sys_fspick
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__arm64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffff800010391de0-ffff800010391e14: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057f7e8)
Location: fs/namei.c:480
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:free_filters_list
  - kernel/events/core.c:perf_fill_ns_link_info
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__se_sys_fspick
  - fs/fsopen.c:__se_sys_fspick
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/fhandle.c:__se_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:__se_sys_mq_open
  - ipc/mqueue.c:__se_sys_mq_open
  - ipc/mqueue.c:__se_sys_mq_open
  - ipc/mqueue.c:__se_sys_mq_open
  - ipc/mqueue.c:__se_sys_mq_open
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
c0578604-c0578630: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000493880)
Location: fs/namei.c:480
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:free_filters_list
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__se_sys_fspick
  - fs/fsopen.c:__se_sys_fspick
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__se_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
c000000000489f30-c000000000489f80: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000266c00)
Location: fs/namei.c:480
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:free_filters_list
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__se_sys_fspick
  - fs/fsopen.c:__se_sys_fspick
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/fhandle.c:__se_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:__se_sys_mq_open
  - ipc/mqueue.c:__se_sys_mq_open
  - ipc/mqueue.c:__se_sys_mq_open
  - ipc/mqueue.c:__se_sys_mq_open
  - ipc/mqueue.c:__se_sys_mq_open
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffe000260fde-ffffffe000261012: path_put (STB_GLOBAL)
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
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e7f92)
Location: fs/namei.c:480
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:free_filters_list
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff812e1010-ffffffff812e1031: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d8bd2)
Location: fs/namei.c:480
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:free_filters_list
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff812d1c50-ffffffff812d1c71: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e5da2)
Location: fs/namei.c:480
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:free_filters_list
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff812dee20-ffffffff812dee41: path_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void path_put(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f6d22)
Location: fs/namei.c:480
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/events/core.c:free_filters_list
  - fs/open.c:do_dentry_open
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/file_table.c:alloc_file_pseudo
  - fs/stat.c:do_readlinkat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:free_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/statfs.c:user_statfs
  - fs/nsfs.c:open_related_ns
  - fs/fs_parser.c:fs_lookup_param
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
  - fs/proc/base.c:proc_pid_readlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff812efe40-ffffffff812efe61: path_put (STB_GLOBAL)
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
