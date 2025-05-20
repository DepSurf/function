# Function: <code>__d_entry_type</code>

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
In kernel/audit_watch.c (0)
Location: include/linux/dcache.h:410
Inline: True
```
```
In mm/shmem.c (ffffffff811a7ab5)
Location: include/linux/dcache.h:410
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
```
```
In fs/namei.c (ffffffff8121766a)
Location: include/linux/dcache.h:410
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:path_openat
```
```
In fs/namespace.c (ffffffff8122e00d)
Location: include/linux/dcache.h:410
Inline: True
Inline callers:
  - fs/namespace.c:graft_tree
  - fs/namespace.c:do_mount
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:410
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:410
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/dcache.h:410
Inline: True
```
```
In fs/ecryptfs/file.c (0)
Location: include/linux/dcache.h:410
Inline: True
```
```
In fs/ecryptfs/inode.c (0)
Location: include/linux/dcache.h:410
Inline: True
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:410
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:410
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/dcache.h:410
Inline: True
```
```
In security/security.c (0)
Location: include/linux/dcache.h:410
Inline: True
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:410
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/dcache.h:410
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/dcache.h:410
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:410
Inline: True
```
```
In security/apparmor/path.c (0)
Location: include/linux/dcache.h:410
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
In kernel/audit_watch.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In mm/shmem.c (ffffffff811bde65)
Location: include/linux/dcache.h:384
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
```
```
In fs/namei.c (ffffffff81244535)
Location: include/linux/dcache.h:384
Inline: True
Inline callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff81257e1d)
Location: include/linux/dcache.h:384
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8127b2ab)
Location: include/linux/dcache.h:384
Inline: True
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff8133635a)
Location: include/linux/dcache.h:384
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In security/security.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8137a0d4)
Location: include/linux/dcache.h:384
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In security/apparmor/path.c (0)
Location: include/linux/dcache.h:384
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
In kernel/audit_watch.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In mm/shmem.c (ffffffff811ce4ad)
Location: include/linux/dcache.h:384
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
```
```
In fs/stat.c (ffffffff8124b60b)
Location: include/linux/dcache.h:384
Inline: True
Inline callers:
  - fs/stat.c:SyS_readlink
```
```
In fs/namei.c (ffffffff812506b5)
Location: include/linux/dcache.h:384
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff8126b2ad)
Location: include/linux/dcache.h:384
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8128ee5a)
Location: include/linux/dcache.h:384
Inline: True
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff8134c019)
Location: include/linux/dcache.h:384
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In security/security.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In security/selinux/hooks.c (ffffffff813907f4)
Location: include/linux/dcache.h:384
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:384
Inline: True
```
```
In security/apparmor/path.c (0)
Location: include/linux/dcache.h:384
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
In kernel/audit_watch.c (0)
Location: include/linux/dcache.h:390
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/dcache.h:390
Inline: True
```
```
In fs/open.c (ffffffff8124e6a8)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/open.c:SyS_fchdir
```
```
In fs/stat.c (ffffffff8125773d)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/stat.c:SyS_readlink
```
```
In fs/namei.c (ffffffff8125c845)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff81277c8d)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:390
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8129bc92)
Location: include/linux/dcache.h:390
Inline: True
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/dcache.h:390
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff81360cc5)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:390
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:390
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/dcache.h:390
Inline: True
```
```
In security/security.c (0)
Location: include/linux/dcache.h:390
Inline: True
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:390
Inline: True
```
```
In security/selinux/hooks.c (ffffffff813a6c5a)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/dcache.h:390
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:390
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/dcache.h:390
Inline: True
```
```
In security/apparmor/path.c (0)
Location: include/linux/dcache.h:390
Inline: True
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
In kernel/audit_watch.c (0)
Location: include/linux/dcache.h:391
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/dcache.h:391
Inline: True
```
```
In fs/open.c (ffffffff8127062d)
Location: include/linux/dcache.h:391
Inline: True
Inline callers:
  - fs/open.c:SyS_fchdir
```
```
In fs/stat.c (ffffffff8127998d)
Location: include/linux/dcache.h:391
Inline: True
Inline callers:
  - fs/stat.c:SyS_readlink
```
```
In fs/namei.c (ffffffff8127eb65)
Location: include/linux/dcache.h:391
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff8129a6d8)
Location: include/linux/dcache.h:391
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:391
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812bf0a3)
Location: include/linux/dcache.h:391
Inline: True
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/dcache.h:391
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff81385995)
Location: include/linux/dcache.h:391
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:391
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:391
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff813a1967)
Location: include/linux/dcache.h:391
Inline: True
```
```
In security/security.c (0)
Location: include/linux/dcache.h:391
Inline: True
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:391
Inline: True
```
```
In security/selinux/hooks.c (ffffffff813cc6aa)
Location: include/linux/dcache.h:391
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/dcache.h:391
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:391
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/dcache.h:391
Inline: True
```
```
In security/apparmor/path.c (0)
Location: include/linux/dcache.h:391
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
In kernel/audit_watch.c (ffffffff81159144)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (ffffffff811afdea)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
```
In mm/shmem.c (0)
Location: include/linux/dcache.h:392
Inline: True
```
```
In fs/open.c (ffffffff81294a1a)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff812a0429)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff812a54f5)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (0)
Location: include/linux/dcache.h:392
Inline: True
```
```
In fs/namespace.c (ffffffff812c079d)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:392
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812e7fe7)
Location: include/linux/dcache.h:392
Inline: True
```
```
In fs/crypto/crypto.c (ffffffff812fa006)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff813b45a5)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:392
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:392
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff813d0da3)
Location: include/linux/dcache.h:392
Inline: True
```
```
In security/security.c (ffffffff813f4983)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:392
Inline: True
```
```
In security/selinux/hooks.c (ffffffff814007e0)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff8141b759)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:392
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/dcache.h:392
Inline: True
```
```
In security/apparmor/path.c (ffffffff814370eb)
Location: include/linux/dcache.h:392
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In kernel/audit_watch.c (ffffffff811660e4)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (ffffffff811be465)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (0)
Location: include/linux/dcache.h:389
Inline: True
```
```
In fs/open.c (ffffffff812a94ca)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff812b5409)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff812ba665)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffffffff812ca70f)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (ffffffff812d59ed)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:389
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812fcc8c)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/crypto/crypto.c (ffffffff8130f2e6)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff813cdac5)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:389
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:389
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff813eb513)
Location: include/linux/dcache.h:389
Inline: True
```
```
In security/security.c (ffffffff8140fd53)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:389
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8141c89e)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff81437da1)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:389
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/dcache.h:389
Inline: True
```
```
In security/apparmor/path.c (ffffffff81453d4b)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In kernel/audit_watch.c (ffffffff81172c17)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ce060)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/open.c (ffffffff812c5c23)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff812d21b9)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff812d7265)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffffffff812e7022)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (ffffffff812f3bcc)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8131daab)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/configfs/dir.c (ffffffff813721aa)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff81374eb8)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (ffffffff813f8677)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff814175b6)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81419de5)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/security.c (ffffffff8143d3b8)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8144a294)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff81465a0d)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/apparmor/path.c (ffffffff81481619)
Location: include/linux/dcache.h:387
Inline: True
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
In kernel/audit_watch.c (ffffffff8117eab3)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (ffffffff811da6c0)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/open.c (ffffffff812d7633)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff812e3d49)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff812e8dc5)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffffffff812f8b92)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (ffffffff8130577c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813308eb)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/configfs/dir.c (ffffffff8138a7ba)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff8138d138)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (ffffffff814124d7)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff81431476)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81433c35)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/security.c (ffffffff81456e58)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81463fac)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff8147f8bd)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/apparmor/path.c (ffffffff8149b349)
Location: include/linux/dcache.h:387
Inline: True
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
In kernel/audit_watch.c (ffffffff8119203c)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f7160)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (ffffffff812718b3)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffff8130d7e3)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff8131a629)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff81321475)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:atomic_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
```
```
In fs/dcache.c (ffffffff81331cc2)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (ffffffff8133f0a0)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff8134632d)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8136a456)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_group_event_mask
```
```
In fs/configfs/dir.c (ffffffff813d5b6d)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813d85ab)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (ffffffff81460b02)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff8146bff7)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8147561d)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff81481155)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - fs/debugfs/inode.c:remove_one
  - fs/debugfs/inode.c:start_creating
```
```
In security/security.c (ffffffff814a9c68)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (ffffffff814ad06b)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff814b7f84)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff814d4c7d)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (ffffffff814e5d81)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff814eb5ab)
Location: include/linux/dcache.h:389
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/apparmor/path.c (ffffffff814f3d98)
Location: include/linux/dcache.h:389
Inline: True
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
In kernel/audit_watch.c (ffffffff8118f1cc)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5d10)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (ffffffff81278803)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffff81319ac3)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff81325cb9)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff8132ca15)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:atomic_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
```
```
In fs/dcache.c (ffffffff8133d6e2)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (ffffffff8134b100)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff8135281d)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813781b4)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/configfs/dir.c (ffffffff813e785d)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813ea228)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (ffffffff8147c712)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff8148673c)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/fuse/dir.c (ffffffff814902d4)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff8149ea95)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/debugfs/inode.c:remove_one
```
```
In security/security.c (ffffffff814c7268)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (ffffffff814ca5bb)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff814d5c94)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff814f227d)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (ffffffff81503181)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff8150898b)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/apparmor/path.c (ffffffff81510ef8)
Location: include/linux/dcache.h:390
Inline: True
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
In kernel/audit_watch.c (ffffffff8118fff9)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f6c00)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
```
In mm/shmem.c (ffffffff8127d80b)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffff81320652)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff8132bded)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff813325e5)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
```
```
In fs/dcache.c (ffffffff81343b62)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (ffffffff813519b0)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff8135953d)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137ed73)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/configfs/dir.c (ffffffff813ee22d)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813f0d68)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (ffffffff814821c2)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff8148c19c)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/fuse/dir.c (ffffffff81495d04)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff814a4a75)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/debugfs/inode.c:remove_one
```
```
In security/security.c (ffffffff814cd6a8)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (ffffffff814d0beb)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff814dcaf4)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff814f929d)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (ffffffff81509d51)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff8150f4fb)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/apparmor/path.c (ffffffff81517878)
Location: include/linux/dcache.h:393
Inline: True
```
```
In security/landlock/syscalls.c (ffffffff815371d5)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
```
```
In security/landlock/fs.c (ffffffff81538961)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_link
  - security/landlock/fs.c:landlock_append_fs_rule
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
In kernel/audit_watch.c (ffffffff811b8ed9)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (ffffffff812281d0)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
```
In mm/shmem.c (ffffffff812bb98b)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffff8136d182)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff8137955d)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff8137fd75)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
```
```
In fs/dcache.c (ffffffff81391b07)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (ffffffff8139fd20)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff813a79dd)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cb30c)
Location: include/linux/dcache.h:393
Inline: True
```
```
In fs/configfs/dir.c (ffffffff8143fa56)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff81442c74)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (ffffffff814d90b2)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff814e39ac)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/fuse/dir.c (ffffffff814ed7c4)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff814fc7b5)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - fs/debugfs/inode.c:remove_one
```
```
In security/security.c (ffffffff815265f8)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (ffffffff8152991b)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff81535fc4)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff81553e8d)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (ffffffff8156723d)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff8156d05b)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/apparmor/path.c (ffffffff81575878)
Location: include/linux/dcache.h:393
Inline: True
```
```
In security/landlock/syscalls.c (ffffffff815957f5)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
```
```
In security/landlock/fs.c (ffffffff815970c1)
Location: include/linux/dcache.h:393
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_link
  - security/landlock/fs.c:landlock_append_fs_rule
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
In kernel/audit_watch.c (ffffffff811ebf0a)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (ffffffff812682e6)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
```
In fs/open.c (ffffffff813ebd7f)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff813f8a27)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff813fffc5)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
```
```
In fs/dcache.c (ffffffff81411ba2)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (ffffffff81423310)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff8142ca2a)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81453078)
Location: include/linux/dcache.h:383
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81456bfc)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/configfs/dir.c (ffffffff814bbfbb)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff814bea30)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (ffffffff815668b8)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff81571d9b)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/fuse/dir.c (ffffffff8157c667)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff8158d204)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:remove_one
```
```
In security/security.c (ffffffff815bae88)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (ffffffff815bf138)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff815cc427)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff815edd2d)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (ffffffff81602deb)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff81609648)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/apparmor/path.c (ffffffff81613358)
Location: include/linux/dcache.h:383
Inline: True
```
```
In security/landlock/syscalls.c (ffffffff81637a99)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
```
```
In security/landlock/fs.c (ffffffff8163b1af)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:landlock_append_fs_rule
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
In kernel/audit_watch.c (ffffffff8123236a)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (ffffffff812ba4b6)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
```
In mm/memcontrol.c (ffffffff814537f0)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff81474221)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff81481fa7)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff8148a005)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
```
```
In fs/dcache.c (ffffffff8149c5c2)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (ffffffff814afa50)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff814ba17a)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e1e36)
Location: include/linux/dcache.h:383
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e5e80)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/configfs/dir.c (ffffffff81553ae6)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff815568f0)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (ffffffff81609e41)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff816171cb)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/fuse/dir.c (ffffffff81622087)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff81633d04)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:remove_one
```
```
In security/security.c (ffffffff81666938)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (ffffffff8166b528)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff81679647)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff8169e1cd)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (ffffffff816b3f6b)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff816bb148)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/apparmor/path.c (ffffffff816c5fa8)
Location: include/linux/dcache.h:383
Inline: True
```
```
In security/landlock/syscalls.c (ffffffff816eee69)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
```
```
In security/landlock/fs.c (ffffffff816f29a7)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:landlock_append_fs_rule
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
In kernel/audit_watch.c (ffffffff81248ffa)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (ffffffff812ddac6)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
```
In mm/memcontrol.c (ffffffff81489602)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff814a8bcf)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff814b6bb7)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff814beee5)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
```
```
In fs/dcache.c (ffffffff814d1912)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (ffffffff814e4a80)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff814ef11a)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/notify/fanotify/fanotify.c (ffffffff815186f2)
Location: include/linux/dcache.h:383
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151cb13)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/configfs/dir.c (ffffffff8158b876)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff8158e6b0)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (ffffffff81641d01)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff8164f2bc)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/fuse/dir.c (ffffffff8165a4e4)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff8166c022)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:remove_one
```
```
In security/security.c (ffffffff8169ef28)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (ffffffff816a3c88)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff816b17f7)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff816d6b6d)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (ffffffff816ec92b)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff816f3838)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/apparmor/path.c (ffffffff816fed88)
Location: include/linux/dcache.h:383
Inline: True
```
```
In security/landlock/syscalls.c (ffffffff817292fe)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
```
```
In security/landlock/fs.c (ffffffff8172ce04)
Location: include/linux/dcache.h:383
Inline: True
Inline callers:
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:landlock_append_fs_rule
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
In kernel/audit_watch.c (ffffffff81262e8a)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/bpf_trace.c (ffffffff812ea334)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fbbb6)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
```
In mm/memcontrol.c (ffffffff814b8a61)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff814d9c2f)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff814e8ee7)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff814f1585)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
```
```
In fs/dcache.c (ffffffff8150422e)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (ffffffff815188a0)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff81523175)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154cad2)
Location: include/linux/dcache.h:390
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81551060)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/configfs/dir.c (ffffffff815c45ac)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff815c73c3)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (ffffffff8167b324)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff816887f2)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/fuse/dir.c (ffffffff816941b4)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff816a64c2)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:remove_one
```
```
In fs/debugfs/file.c (ffffffff816a75dc)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_leave_cancellation
  - fs/debugfs/file.c:debugfs_enter_cancellation
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/security.c (ffffffff816db878)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (ffffffff816e06e8)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff816ee88a)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff8171341d)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (ffffffff817296fb)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff817305c8)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/apparmor/path.c (ffffffff8173c318)
Location: include/linux/dcache.h:390
Inline: True
```
```
In security/landlock/syscalls.c (ffffffff8176a6ca)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - security/landlock/syscalls.c:add_rule_path_beneath
```
```
In security/landlock/fs.c (ffffffff8176dbd5)
Location: include/linux/dcache.h:390
Inline: True
Inline callers:
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:find_rule
  - security/landlock/fs.c:landlock_append_fs_rule
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
In kernel/audit_watch.c (ffff8000101f39dc)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (ffff80001025adc4)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/open.c (ffff80001037c9e8)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/open.c:__arm64_sys_fchdir
```
```
In fs/stat.c (ffff80001038a7d8)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffff8000103921dc)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffff8000103a6c30)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (ffff8000103b8e94)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffff8000103edae8)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/configfs/dir.c (ffff80001045ade0)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffff80001045ee50)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (ffff8000104f38e4)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/debugfs/inode.c (ffff8000105161a0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/tracefs/inode.c (ffff8000105196dc)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/security.c (ffff8000105428d0)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/selinux/hooks.c (ffff80001055203c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffff800010570c30)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/apparmor/path.c (ffff80001059161c)
Location: include/linux/dcache.h:387
Inline: True
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
In kernel/audit_watch.c (c0433e4c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (c048dec4)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (c04f9ae4)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (c0569050)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/open.c:__se_sys_fchdir
```
```
In fs/stat.c (c0572d70)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (c057972c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (c05878ec)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (c0596814)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (c059d224)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
```
```
In fs/notify/fanotify/fanotify.c (c05c4364)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/configfs/dir.c (c061c998)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (c061f868)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (c06b1334)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (c06bc18c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (c06c5904)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (c06d0b84)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (c06d3d98)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/security.c (c06f8878)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (c06fbf14)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (c0704260)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (c07241ac)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (c0734430)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (c073a9bc)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/apparmor/path.c (c0742220)
Location: include/linux/dcache.h:387
Inline: True
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
In kernel/audit_watch.c (c000000000268654)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (c0000000002fe94c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (c00000000038fcd0)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (c000000000471c94)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/open.c:__se_sys_fchdir
```
```
In fs/stat.c (c000000000482b88)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (c00000000048a9c0)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (c00000000049f7cc)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (c0000000004b5fc4)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (c0000000004c0754)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
```
```
In fs/notify/fanotify/fanotify.c (c0000000004f532c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/configfs/dir.c (c000000000576838)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (c00000000057b018)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (c000000000633b74)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (c000000000642914)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (c00000000064f7d4)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (c00000000065e93c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (c000000000662ba0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/security.c (c000000000695f04)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (c00000000069cb6c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (c0000000006a8748)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (c0000000006d749c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (c0000000006f0e20)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (c0000000006fa7ec)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/apparmor/path.c (c00000000070526c)
Location: include/linux/dcache.h:387
Inline: True
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
In kernel/audit_watch.c (ffffffe000166dd0)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In mm/shmem.c (ffffffe0001ef12a)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffe00025438a)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/open.c:__se_sys_fchdir
```
```
In fs/stat.c (ffffffe00025cada)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffe0002613c0)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffffffe00026d55a)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (ffffffe00027b23a)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffe0002814b4)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
```
```
In fs/notify/fanotify/fanotify.c (ffffffe0002a142c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/configfs/dir.c (ffffffe0002eb6ec)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffe0002ee954)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (ffffffe000362d6e)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffe00036cf58)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffe00037539c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffe00037f5b2)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffffffe000382a18)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/security.c (ffffffe00039f122)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (ffffffe0003a1c3c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffe0003aafa8)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffe0003c38ea)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (ffffffe0003d2a24)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffe0003d8684)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/apparmor/path.c (ffffffe0003def88)
Location: include/linux/dcache.h:387
Inline: True
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
In kernel/audit_watch.c (ffffffff811770d3)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d2ce0)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/open.c (ffffffff812cfc13)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff812dc329)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff812e13a5)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffffffff812f1172)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (ffffffff812fdd5c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81328ecb)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/configfs/dir.c (ffffffff81382d9a)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff81385718)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (ffffffff8140aab7)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff81429a56)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8142c215)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/security.c (ffffffff8144f438)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8145c58c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff81477e9d)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/apparmor/path.c (ffffffff81493929)
Location: include/linux/dcache.h:387
Inline: True
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
In kernel/audit_watch.c (ffffffff8116a273)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c5ab0)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/open.c (ffffffff812c0893)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff812ccfa9)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff812d1fe5)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffffffff812e1da2)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (ffffffff812ee97c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81319a6b)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/configfs/dir.c (ffffffff8137382a)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813761a8)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (ffffffff813fb537)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff8141a4d6)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8141cc95)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/security.c (ffffffff8143fe88)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8144cfbc)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff814688bd)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/apparmor/path.c (ffffffff81484349)
Location: include/linux/dcache.h:387
Inline: True
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
In kernel/audit_watch.c (ffffffff81174ea3)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d0ab0)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/open.c (ffffffff812cda23)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff812da139)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff812df1b5)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffffffff812eef82)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (ffffffff812fbb4c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8132699b)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/configfs/dir.c (ffffffff8138086a)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813831e8)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (ffffffff81407e37)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff81425bf6)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff814283b5)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/security.c (ffffffff8144b4d8)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8145862c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff81473f3d)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/apparmor/path.c (ffffffff8148f9c9)
Location: include/linux/dcache.h:387
Inline: True
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
In kernel/audit_watch.c (ffffffff81182783)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ded70)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/open.c (ffffffff812de833)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff812eb049)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff812f05a5)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_unlink
  - fs/namei.c:filename_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffffffff812ff2e4)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_lru_add
```
```
In fs/namespace.c (ffffffff8130ce6c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813387bb)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/configfs/dir.c (ffffffff81394326)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff81396d08)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/ecryptfs/inode.c (ffffffff8141daf7)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff8143cab6)
Location: include/linux/dcache.h:387
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8143f275)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/security.c (ffffffff814628a8)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8146d44c)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff8148b84d)
Location: include/linux/dcache.h:387
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/dcache.h:387
Inline: True
```
```
In security/apparmor/path.c (ffffffff814a78d7)
Location: include/linux/dcache.h:387
Inline: True
```
</details>
</li>
</ul>

## Differences
