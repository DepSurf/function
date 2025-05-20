# Function: <code>lockref_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff813f7b60)
Location: lib/lockref.c:40
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_symlink
  - fs/super.c:mount_ns
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_single
  - fs/namei.c:path_get
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_down
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/dcache.c:d_find_any_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_instantiate_unique
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:__d_obtain_alias
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:lock_mount
  - fs/namespace.c:mnt_set_mountpoint
  - fs/libfs.c:mount_pseudo
  - fs/libfs.c:simple_link
  - fs/proc/root.c:proc_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/devpts/inode.c:devpts_mount
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create
  - security/inode.c:securityfs_create_file
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff813f7b60-ffffffff813f7bb6: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff8143e9f0)
Location: lib/lockref.c:40
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:path_get
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_find_any_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:mnt_set_mountpoint
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/devpts/inode.c:devpts_mount
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create
  - security/inode.c:__securityfs_setup_d_inode
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8143e9f0-ffffffff8143ea47: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff8145ba40)
Location: lib/lockref.c:40
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:path_get
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_find_any_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:mnt_set_mountpoint
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create
  - security/inode.c:__securityfs_setup_d_inode
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8145ba40-ffffffff8145ba97: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff81460f30)
Location: lib/lockref.c:40
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_lookupat
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:path_get
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_find_any_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:mnt_set_mountpoint
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/inode.c:configfs_create
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_setup_d_inode
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81460f30-ffffffff81460f88: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff8148ce00)
Location: lib/lockref.c:41
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_lookupat
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_find_any_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:mnt_set_mountpoint
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/inode.c:configfs_create
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8148ce00-ffffffff8148ce59: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff814c1b90)
Location: lib/lockref.c:41
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_any_alias
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:mnt_set_mountpoint
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/inode.c:configfs_create
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff814c1b90-ffffffff814c1be9: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff814d6280)
Location: lib/lockref.c:41
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_any_alias
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:mnt_set_mountpoint
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/inode.c:configfs_create
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff814d6280-ffffffff814d62d9: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff815020e0)
Location: lib/lockref.c:44
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:vfs_get_super
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_any_alias
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/inode.c:configfs_create
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff815020e0-ffffffff8150214c: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff8151fff0)
Location: lib/lockref.c:44
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_any_alias
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - drivers/base/devtmpfs.c:public_dev_mount
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8151fff0-ffffffff8152005c: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff815831a0)
Location: lib/lockref.c:44
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mklink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/super.c:get_tree_nodev
  - fs/namei.c:vfs_rename
  - fs/namei.c:atomic_open
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_alias
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_recursive_removal
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_create
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - drivers/base/devtmpfs.c:public_dev_mount
  - net/unix/af_unix.c:unix_mknod
```
**Symbols:**

```
ffffffff815831a0-ffffffff81583210: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff815a0020)
Location: lib/lockref.c:44
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/super.c:get_tree_nodev
  - fs/namei.c:vfs_rename
  - fs/namei.c:atomic_open
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_alias
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_recursive_removal
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_create
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_dentry_automount
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - drivers/base/devtmpfs.c:public_dev_mount
  - net/unix/af_unix.c:unix_mknod
```
**Symbols:**

```
ffffffff815a0020-ffffffff815a0090: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff815a6e10)
Location: lib/lockref.c:44
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/super.c:get_tree_nodev
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_alias
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_recursive_removal
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_create
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_dentry_automount
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - drivers/base/devtmpfs.c:public_dev_mount
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff815a6e10-ffffffff815a6e7d: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff8160fd50)
Location: lib/lockref.c:44
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/super.c:get_tree_nodev
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_alias
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_recursive_removal
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_create
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - drivers/base/devtmpfs.c:public_dev_mount
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff8160fd50-ffffffff8160fdbd: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff816dc020)
Location: lib/lockref.c:43
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:handle_dots
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_alias
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_recursive_removal
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_create
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/landlock/fs.c:collect_domain_accesses
  - drivers/base/devtmpfs.c:public_dev_mount
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff816dc020-ffffffff816dc094: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff817cbc90)
Location: lib/lockref.c:42
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:handle_dots
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_alias
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_recursive_removal
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/landlock/fs.c:collect_domain_accesses
  - drivers/base/devtmpfs.c:public_dev_mount
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff817cbc90-ffffffff817cbd02: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff8180a050)
Location: lib/lockref.c:42
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:handle_dots
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_alias
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_recursive_removal
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/landlock/fs.c:collect_domain_accesses
  - drivers/base/devtmpfs.c:public_dev_mount
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff8180a050-ffffffff8180a0cf: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff818508b0)
Location: lib/lockref.c:42
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:handle_dots
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_alias
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_recursive_removal
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/landlock/fs.c:collect_domain_accesses
  - drivers/base/devtmpfs.c:public_dev_mount
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff818508b0-ffffffff81850922: lockref_get (STB_GLOBAL)
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
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffff800010629380)
Location: lib/lockref.c:44
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_any_alias
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - drivers/base/devtmpfs.c:public_dev_mount
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffff800010629380-ffff800010629464: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (c07d0348)
Location: lib/lockref.c:44
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_lookupat
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:path_get
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_any_alias
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:detach_groups
  - fs/configfs/dir.c:detach_attrs
  - fs/configfs/dir.c:configfs_detach_prep
  - fs/configfs/dir.c:configfs_remove_dir
  - fs/configfs/dir.c:configfs_remove_dir
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - drivers/base/devtmpfs.c:public_dev_mount
  - drivers/mtd/mtdsuper.c:mtd_get_sb
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
c07d0348-c07d0428: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (c0000000007cb010)
Location: lib/lockref.c:44
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_any_alias
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_detach_prep
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - drivers/base/devtmpfs.c:public_dev_mount
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
c0000000007cb010-c0000000007cb0f0: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffe00045a214)
Location: lib/lockref.c:44
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_lookupat
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_any_alias
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_detach_prep
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - drivers/base/devtmpfs.c:public_dev_mount
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffe00045a214-ffffffe00045a278: lockref_get (STB_GLOBAL)
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
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff815185d0)
Location: lib/lockref.c:44
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_any_alias
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - drivers/base/devtmpfs.c:public_dev_mount
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff815185d0-ffffffff8151863c: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff815088d0)
Location: lib/lockref.c:44
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_any_alias
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - drivers/base/devtmpfs.c:public_dev_mount
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff815088d0-ffffffff8150893c: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff81514660)
Location: lib/lockref.c:44
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_any_alias
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - drivers/base/devtmpfs.c:public_dev_mount
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81514660-ffffffff815146cc: lockref_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void lockref_get(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff8152dd40)
Location: lib/lockref.c:44
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:d_find_any_alias
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/libfs.c:simple_link
  - fs/fs_context.c:alloc_fs_context
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - drivers/base/devtmpfs.c:public_dev_mount
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8152dd40-ffffffff8152ddaa: lockref_get (STB_GLOBAL)
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
