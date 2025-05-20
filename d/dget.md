# Function: <code>dget</code>

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
In kernel/bpf/inode.c (ffffffff81176d94)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
```
In mm/shmem.c (ffffffff811a7980)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_symlink
```
```
In fs/super.c (ffffffff8120fa22)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/super.c:mount_ns
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_single
```
```
In fs/namei.c (ffffffff81216469)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/namei.c:path_get
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_down
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
```
```
In fs/dcache.c (ffffffff8122571d)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff8122c817)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:lock_mount
  - fs/namespace.c:mnt_set_mountpoint
```
```
In fs/libfs.c (ffffffff81233bb8)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/libfs.c:mount_pseudo
  - fs/libfs.c:simple_link
```
```
In fs/proc/root.c (ffffffff81279f95)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/proc/root.c:proc_mount
```
```
In fs/kernfs/mount.c (ffffffff812885d5)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_mount_ns
```
```
In fs/devpts/inode.c (ffffffff8128df1d)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_mount
```
```
In fs/ramfs/inode.c (ffffffff812f3391)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_symlink
```
```
In fs/hugetlbfs/inode.c (ffffffff812f4858)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
```
```
In fs/ecryptfs/inode.c (ffffffff8130177d)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/main.c (ffffffff81303685)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff8130c83b)
Location: include/linux/dcache.h:357
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff8131d6c6)
Location: include/linux/dcache.h:357
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8131f1bc)
Location: include/linux/dcache.h:357
Inline: True
```
```
In fs/efivarfs/inode.c (ffffffff813211c2)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
```
In ipc/mqueue.c (ffffffff8132c99c)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create
```
```
In security/inode.c (ffffffff8133fe2c)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_file
```
```
In security/selinux/hooks.c (ffffffff8134364b)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff813611f8)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff81f99429)
Location: include/linux/dcache.h:357
Inline: True
```
```
In net/unix/af_unix.c (ffffffff817c0a05)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In kernel/bpf/inode.c (ffffffff8118580e)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
```
In mm/shmem.c (ffffffff811c1bf8)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff812370cb)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
```
```
In fs/namei.c (ffffffff81241530)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:path_get
```
```
In fs/dcache.c (ffffffff8124dda7)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff812562e4)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:mnt_set_mountpoint
```
```
In fs/libfs.c (ffffffff8125c299)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo
```
```
In fs/kernfs/mount.c (ffffffff812b5c50)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/devpts/inode.c (ffffffff812bb535)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_mount
```
```
In fs/ramfs/inode.c (ffffffff81326c2c)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff81327b8c)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (ffffffff813357ed)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff8133763a)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff81340afb)
Location: include/linux/dcache.h:315
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff81352166)
Location: include/linux/dcache.h:315
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8135467c)
Location: include/linux/dcache.h:315
Inline: True
```
```
In fs/efivarfs/inode.c (ffffffff8135655b)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
```
In ipc/mqueue.c (ffffffff813615fc)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create
```
```
In security/inode.c (ffffffff81375353)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - security/inode.c:__securityfs_setup_d_inode
```
```
In security/selinux/hooks.c (ffffffff81378361)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff81394c1b)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff813aeff4)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
```
```
In net/unix/af_unix.c (ffffffff8182da92)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In kernel/bpf/inode.c (ffffffff81192a37)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
```
```
In mm/shmem.c (ffffffff811d1ccd)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff81249d7b)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
```
```
In fs/namei.c (ffffffff812543a4)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:path_get
```
```
In fs/dcache.c (ffffffff81260e87)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff812696bb)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:mnt_set_mountpoint
```
```
In fs/libfs.c (ffffffff8126f7fe)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
```
```
In fs/kernfs/mount.c (ffffffff812cb4e0)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/ramfs/inode.c (ffffffff8133c9ac)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff8133d8cc)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (ffffffff8134b4a6)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff8134d415)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff8135689a)
Location: include/linux/dcache.h:315
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff81368416)
Location: include/linux/dcache.h:315
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8136a93c)
Location: include/linux/dcache.h:315
Inline: True
```
```
In fs/efivarfs/inode.c (ffffffff8136c9b1)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
```
In ipc/mqueue.c (ffffffff81377df5)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create
```
```
In security/inode.c (ffffffff8138bc83)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - security/inode.c:__securityfs_setup_d_inode
```
```
In security/selinux/hooks.c (ffffffff8138ef42)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff813add86)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff813c6137)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
```
```
In net/unix/af_unix.c (ffffffff8185f3d6)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In kernel/bpf/inode.c (ffffffff811998a9)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
```
```
In mm/shmem.c (ffffffff811da692)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff81255679)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
```
```
In fs/namei.c (ffffffff812600ea)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_lookupat
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:path_get
```
```
In fs/dcache.c (ffffffff8126e677)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff81276e5b)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:mnt_set_mountpoint
```
```
In fs/libfs.c (ffffffff8127cfe0)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
```
```
In fs/kernfs/mount.c (ffffffff812d8936)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/inode.c (ffffffff812de200)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_create
```
```
In fs/configfs/dir.c (ffffffff812df792)
Location: include/linux/dcache.h:321
Inline: True
```
```
In fs/ramfs/inode.c (ffffffff813514ee)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff81351cae)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (ffffffff81360036)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff81361f75)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff8136b50c)
Location: include/linux/dcache.h:321
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff8137ca76)
Location: include/linux/dcache.h:321
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8137ef76)
Location: include/linux/dcache.h:321
Inline: True
```
```
In fs/efivarfs/inode.c (ffffffff81380efd)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
```
In ipc/mqueue.c (ffffffff8138b944)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create
```
```
In security/inode.c (ffffffff813a1a5b)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff813a5279)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff813c2d27)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff813dc12f)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_setup_d_inode
```
```
In net/unix/af_unix.c (ffffffff81882c5c)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In kernel/bpf/inode.c (ffffffff811a8b49)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
```
```
In mm/shmem.c (ffffffff811f03f2)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff8127780b)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
```
```
In fs/namei.c (ffffffff812827ca)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
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
```
```
In fs/dcache.c (ffffffff81290f97)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff8129989b)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:mnt_set_mountpoint
```
```
In fs/libfs.c (ffffffff8129fa80)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
```
```
In fs/kernfs/mount.c (ffffffff812fd1b6)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/inode.c (ffffffff81302b42)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_create
```
```
In fs/configfs/dir.c (ffffffff81304112)
Location: include/linux/dcache.h:322
Inline: True
```
```
In fs/ramfs/inode.c (ffffffff81375fee)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff8137714e)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (ffffffff81384d06)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff81386c4b)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff8139009c)
Location: include/linux/dcache.h:322
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff813a1946)
Location: include/linux/dcache.h:322
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff813a3fb6)
Location: include/linux/dcache.h:322
Inline: True
```
```
In fs/efivarfs/inode.c (ffffffff813a5f0d)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
```
In ipc/mqueue.c (ffffffff813b0cda)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create
```
```
In security/inode.c (ffffffff813c785b)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff813cad7f)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff813e8fe7)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff81402baf)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In net/unix/af_unix.c (ffffffff8190500c)
Location: include/linux/dcache.h:322
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In kernel/bpf/inode.c (ffffffff811bffd7)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
```
```
In mm/shmem.c (ffffffff81211b80)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff8129e10b)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
```
```
In fs/namei.c (ffffffff812ab40a)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
```
```
In fs/dcache.c (ffffffff812b7677)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff812bf773)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:mnt_set_mountpoint
```
```
In fs/libfs.c (ffffffff812c649e)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
```
```
In fs/kernfs/mount.c (ffffffff8132aef7)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/inode.c (ffffffff81330a8e)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_create
```
```
In fs/configfs/dir.c (ffffffff8133193d)
Location: include/linux/dcache.h:323
Inline: True
```
```
In fs/ramfs/inode.c (ffffffff813a49fc)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff813a591c)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (ffffffff813b3b0a)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff813b5a25)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff813bf16b)
Location: include/linux/dcache.h:323
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff813d0d93)
Location: include/linux/dcache.h:323
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff813d33b5)
Location: include/linux/dcache.h:323
Inline: True
```
```
In fs/efivarfs/inode.c (ffffffff813d51cc)
Location: include/linux/dcache.h:323
Inline: True
```
```
In ipc/mqueue.c (ffffffff813e32ce)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffffffff813f6e90)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff813feed6)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff81419eb7)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff827173eb)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In net/unix/af_unix.c (ffffffff8195a8e9)
Location: include/linux/dcache.h:323
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In kernel/bpf/inode.c (ffffffff811d1427)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
```
```
In mm/shmem.c (ffffffff81225c10)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff812b30cb)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
```
```
In fs/namei.c (ffffffff812be01a)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
```
```
In fs/dcache.c (ffffffff812cc7d7)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff812d4973)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:mnt_set_mountpoint
```
```
In fs/libfs.c (ffffffff812db69e)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
```
```
In fs/kernfs/mount.c (ffffffff81342262)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/inode.c (ffffffff81347e7e)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_create
```
```
In fs/configfs/dir.c (ffffffff81348d7d)
Location: include/linux/dcache.h:320
Inline: True
```
```
In fs/ramfs/inode.c (ffffffff813bd7fc)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff813be78c)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (ffffffff813ccfea)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff813cef82)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff813d87cc)
Location: include/linux/dcache.h:320
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff813eb503)
Location: include/linux/dcache.h:320
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff813edb85)
Location: include/linux/dcache.h:320
Inline: True
```
```
In fs/efivarfs/inode.c (ffffffff813ef81a)
Location: include/linux/dcache.h:320
Inline: True
```
```
In ipc/mqueue.c (ffffffff813fdabe)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffffffff81412940)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff8141b033)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff81436685)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff828ceeb0)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In net/unix/af_unix.c (ffffffff8198f5d9)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In kernel/bpf/inode.c (ffffffff811e5757)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
```
```
In mm/shmem.c (ffffffff81235260)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff812cfe21)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:vfs_get_super
```
```
In fs/namei.c (ffffffff812dac23)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
```
```
In fs/dcache.c (ffffffff812e850e)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff812f31eb)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (ffffffff812f9d30)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
```
```
In fs/fs_context.c (ffffffff8130ac16)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (ffffffff8136a622)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/inode.c (ffffffff81370305)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_create
```
```
In fs/configfs/dir.c (ffffffff8137133d)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/ramfs/inode.c (ffffffff813e80dc)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff813e902c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (ffffffff813f7b6a)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff813f9c33)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff81403190)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff81417585)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81419db7)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/efivarfs/inode.c (ffffffff8141bb04)
Location: include/linux/dcache.h:318
Inline: True
```
```
In ipc/mqueue.c (ffffffff8142a113)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffffffff8144037b)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff81448b2b)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff8146435f)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff828e8932)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In net/unix/af_unix.c (ffffffff819fab4f)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In kernel/bpf/inode.c (ffffffff811f1eb7)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
```
```
In mm/shmem.c (ffffffff812434a0)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff812e1a31)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
```
```
In fs/namei.c (ffffffff812ec733)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
```
```
In fs/dcache.c (ffffffff812fa09e)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff81304dab)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (ffffffff8130b960)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
```
```
In fs/fs_context.c (ffffffff8131dbf6)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (ffffffff81382802)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/dir.c (ffffffff8138b95d)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/ramfs/inode.c (ffffffff8140224c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff814030cc)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (ffffffff81411a62)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff81413b03)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff8141d0a0)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff81431445)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81433c07)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/efivarfs/inode.c (ffffffff81435954)
Location: include/linux/dcache.h:318
Inline: True
```
```
In ipc/mqueue.c (ffffffff81443e43)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffffffff81459c4b)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff814626bb)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff8147e12f)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff828f141e)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In drivers/base/devtmpfs.c (ffffffff81708afb)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In net/unix/af_unix.c (ffffffff81a317df)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In kernel/bpf/inode.c (ffffffff81213b24)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mklink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
```
In mm/shmem.c (ffffffff81271ff0)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff81318d41)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
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
```
```
In fs/namei.c (ffffffff81326659)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
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
```
```
In fs/dcache.c (ffffffff8133315e)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff8133e982)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (ffffffff81345160)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs_context.c (ffffffff81357938)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (ffffffff813ccf63)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/dir.c (ffffffff813d6c1d)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/ramfs/inode.c (ffffffff8144fe4c)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff81450b4c)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_create
```
```
In fs/ecryptfs/inode.c (ffffffff8145f912)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff81461ca3)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff8146be55)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/efivarfs/inode.c (ffffffff8148565e)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
```
In ipc/mqueue.c (ffffffff81494b5a)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffffffff814acecb)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff814b6615)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff814d3bb0)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff814f04f2)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In drivers/base/devtmpfs.c (ffffffff817c3b8b)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In net/unix/af_unix.c (ffffffff81b23b09)
Location: include/linux/dcache.h:320
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_mknod
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
In kernel/bpf/inode.c (ffffffff812153c4)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
```
In mm/shmem.c (ffffffff8127ad60)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff81324281)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
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
```
```
In fs/namei.c (ffffffff81331af9)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
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
```
```
In fs/dcache.c (ffffffff8133eabe)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff8134a9e2)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (ffffffff813514b0)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs_context.c (ffffffff81364386)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (ffffffff813debb3)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/dir.c (ffffffff813e88ed)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/ramfs/inode.c (ffffffff8146c35c)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff8146d05c)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_create
```
```
In fs/ecryptfs/inode.c (ffffffff8147b532)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff8147d813)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff814865a5)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff8148cf4d)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_automount
```
```
In fs/efivarfs/inode.c (ffffffff814a2c8e)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
```
In ipc/mqueue.c (ffffffff814b24c6)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffffffff814ca41b)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff814d42d1)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff814f0d70)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff81bf15c0)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In drivers/base/devtmpfs.c (ffffffff817d8cbb)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In net/unix/af_unix.c (ffffffff81b324d9)
Location: include/linux/dcache.h:321
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_mknod
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
In kernel/bpf/inode.c (ffffffff812180d4)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
```
In mm/shmem.c (ffffffff8127fee0)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff8132a351)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
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
```
```
In fs/namei.c (ffffffff81335b73)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
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
```
```
In fs/dcache.c (ffffffff81344eae)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff81351237)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (ffffffff813581c0)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs_context.c (ffffffff8136adee)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (ffffffff813e5899)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/dir.c (ffffffff813ef4ad)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/ramfs/inode.c (ffffffff81471a39)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff81472759)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_create
```
```
In fs/ecryptfs/inode.c (ffffffff81481010)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff814833ba)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff8148c005)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff814927e1)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_automount
```
```
In fs/efivarfs/inode.c (ffffffff814a8e7e)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
```
In ipc/mqueue.c (ffffffff814b8332)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffffffff814d0a4b)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff814da885)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff814f7c2b)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff831fe348)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In drivers/base/devtmpfs.c (ffffffff817bce2b)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In net/unix/af_unix.c (ffffffff81b22687)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In kernel/bpf/inode.c (ffffffff8124e6b4)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
```
In mm/shmem.c (ffffffff812be1e0)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff81377981)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
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
```
```
In fs/namei.c (ffffffff81383686)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
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
```
```
In fs/dcache.c (ffffffff8139299e)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff8139f5fb)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (ffffffff813a6640)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs_context.c (ffffffff813b9aae)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (ffffffff81437469)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/dir.c (ffffffff8144139d)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/ramfs/inode.c (ffffffff814c84d9)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff814c8f79)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_create
```
```
In fs/ecryptfs/inode.c (ffffffff814d8910)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff814dab3a)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff814e3815)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/inode.c (ffffffff814f5603)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
```
```
In fs/efivarfs/inode.c (ffffffff815011da)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
```
In ipc/mqueue.c (ffffffff81510b62)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffffffff8152977b)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff81533789)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff815527eb)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff832e565a)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In drivers/base/devtmpfs.c (ffffffff8184719b)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In net/unix/af_unix.c (ffffffff81be6e36)
Location: include/linux/dcache.h:324
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind_bsd
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
In kernel/bpf/inode.c (ffffffff81295724)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
```
In mm/shmem.c (ffffffff8131b1f9)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff813f6c1e)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
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
```
```
In fs/namei.c (ffffffff81404122)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
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
```
```
In fs/dcache.c (ffffffff81414247)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff81422aea)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (ffffffff8142ae7e)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs_context.c (ffffffff8143f537)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (ffffffff814b20ce)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/dir.c (ffffffff814bcf5f)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/ramfs/inode.c (ffffffff81553a7d)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff815546f9)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_create
```
```
In fs/ecryptfs/inode.c (ffffffff81566140)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff8156849e)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff81571be5)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/inode.c (ffffffff815856f2)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
```
```
In fs/efivarfs/inode.c (ffffffff81592543)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
```
In ipc/mqueue.c (ffffffff815a1492)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffffffff815bef5d)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff815c9f75)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff815ec287)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff8349c3cd)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In security/landlock/fs.c (ffffffff81639853)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - security/landlock/fs.c:collect_domain_accesses
```
```
In drivers/base/devtmpfs.c (ffffffff8198bc4a)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In net/unix/af_unix.c (ffffffff81d7e153)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind_bsd
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
In kernel/bpf/inode.c (ffffffff812f04b4)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
```
In mm/shmem.c (ffffffff8138dbc6)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff8147fe3e)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
```
```
In fs/namei.c (ffffffff8148e5a2)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
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
```
```
In fs/dcache.c (ffffffff8149f6c7)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff814af179)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (ffffffff814b7fee)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs_context.c (ffffffff814ce1d7)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (ffffffff81548c1e)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/dir.c (ffffffff81554b0e)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/ramfs/inode.c (ffffffff815f52cd)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6159)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (ffffffff81609600)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff8160be19)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff81617005)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/inode.c (ffffffff8162b902)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
```
```
In fs/efivarfs/inode.c (ffffffff81639eb1)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
```
In ipc/mqueue.c (ffffffff8164aed2)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffffffff8166b30d)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff81677195)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff8169bf47)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff83ed35b0)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In security/landlock/fs.c (ffffffff816f0f13)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - security/landlock/fs.c:collect_domain_accesses
```
```
In drivers/base/devtmpfs.c (ffffffff81afb30a)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In net/unix/af_unix.c (ffffffff81f4cb3c)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind_bsd
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
In kernel/bpf/inode.c (ffffffff8131d7c4)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
```
In mm/shmem.c (ffffffff813c22dd)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff814b4b2e)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
```
```
In fs/namei.c (ffffffff814c3cf5)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
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
```
```
In fs/dcache.c (ffffffff814d49e7)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff814e40dc)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (ffffffff814ed1fe)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs_context.c (ffffffff81504461)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (ffffffff815807ea)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/dir.c (ffffffff8158c88e)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/ramfs/inode.c (ffffffff8162d34d)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e0e9)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (ffffffff816414c0)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff81643cf9)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff8164f0f5)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/inode.c (ffffffff81663b35)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
```
```
In fs/efivarfs/inode.c (ffffffff81672311)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
```
In ipc/mqueue.c (ffffffff81683422)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffffffff816a3a6d)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff816af44a)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff816d4b09)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff836f862a)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In security/landlock/fs.c (ffffffff8172b397)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - security/landlock/fs.c:collect_domain_accesses
```
```
In drivers/base/devtmpfs.c (ffffffff81b496fa)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In net/unix/af_unix.c (ffffffff81fac4a8)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind_bsd
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
In kernel/bpf/inode.c (ffffffff8133fb88)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
```
In mm/shmem.c (ffffffff813ed09d)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff814e6dfe)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
```
```
In fs/namei.c (ffffffff814f61c8)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
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
```
```
In fs/dcache.c (ffffffff81506d27)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff81517e0c)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (ffffffff81521163)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs_context.c (ffffffff81539123)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (ffffffff815b927b)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/dir.c (ffffffff815c5591)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/ramfs/inode.c (ffffffff8166683d)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff816675a9)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (ffffffff8167aa97)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff8167d28c)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff81688635)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/inode.c (ffffffff8169dc8c)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
```
```
In fs/efivarfs/inode.c (ffffffff816ae33e)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
```
In ipc/mqueue.c (ffffffff816bf807)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffffffff816e04c4)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff816ec3ba)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff81710e5c)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff8392b9f5)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In security/landlock/fs.c (ffffffff8176daa0)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - security/landlock/fs.c:collect_domain_accesses
```
```
In drivers/base/devtmpfs.c (ffffffff81ba1aea)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In net/unix/af_unix.c (ffffffff820798c8)
Location: include/linux/dcache.h:325
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind_bsd
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
In kernel/bpf/inode.c (ffff8000102754a8)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
```
```
In mm/shmem.c (ffff8000102d5744)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffff800010388e84)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
```
```
In fs/namei.c (ffff800010395f4c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
```
```
In fs/dcache.c (ffff8000103a8d04)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffff8000103b8634)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (ffff8000103bffe0)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
```
```
In fs/fs_context.c (ffff8000103d5cf8)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (ffff800010450cb0)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/dir.c (ffff80001045cb68)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/ramfs/inode.c (ffff8000104e066c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffff8000104e0d54)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (ffff8000104f2e18)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffff8000104f4fc0)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffff8000104fed30)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/debugfs/inode.c (ffff800010516170)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/tracefs/inode.c (ffff8000105196a8)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/efivarfs/inode.c (ffff80001051b888)
Location: include/linux/dcache.h:318
Inline: True
```
```
In ipc/mqueue.c (ffff80001052c53c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffff800010545f24)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffff8000105503d4)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffff80001056ef90)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffff80001146b5c4)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In drivers/base/devtmpfs.c (ffff8000108f6e4c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In net/unix/af_unix.c (ffff800010cf29e0)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In kernel/bpf/inode.c (c04a7c5c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
```
```
In mm/shmem.c (c04fd904)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (c0571460)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
```
```
In fs/namei.c (c057b404)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_lookupat
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:path_get
```
```
In fs/dcache.c (c058a318)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (c0598150)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (c059d0ac)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
```
```
In fs/fs_context.c (c05af248)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (c0613c80)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/dir.c (c061c60c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/configfs/dir.c:detach_groups
  - fs/configfs/dir.c:detach_attrs
  - fs/configfs/dir.c:configfs_detach_prep
  - fs/configfs/dir.c:configfs_remove_dir
  - fs/configfs/dir.c:configfs_remove_dir
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/ramfs/inode.c (c06a1eb4)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/ecryptfs/inode.c (c06b0580)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (c06b2884)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (c06bbd58)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/debugfs/inode.c (c06d0eec)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/tracefs/inode.c (c06d3d60)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/efivarfs/inode.c (c06d82a0)
Location: include/linux/dcache.h:318
Inline: True
```
```
In ipc/mqueue.c (c06e2cd4)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (c06fbd5c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (c0703078)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (c0722984)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (c154427c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In drivers/base/devtmpfs.c (c09e28c8)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In drivers/mtd/mtdsuper.c (c0a911ec)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - drivers/mtd/mtdsuper.c:mtd_get_sb
```
```
In net/unix/af_unix.c (c0df8810)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In kernel/bpf/inode.c (c00000000031d4a4)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
```
```
In mm/shmem.c (c000000000395540)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (c00000000047fddc)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
```
```
In fs/namei.c (c00000000048e274)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
```
```
In fs/dcache.c (c0000000004a38a4)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (c0000000004b55d8)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (c0000000004bee64)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
```
```
In fs/fs_context.c (c0000000004d9424)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (c00000000056902c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/dir.c (c000000000574d10)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_detach_prep
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/ramfs/inode.c (c00000000061cec8)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (c00000000061d9b8)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (c000000000632cb4)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (c000000000635890)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (c000000000641ed0)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
```
```
In fs/debugfs/inode.c (c00000000065ec90)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/tracefs/inode.c (c000000000662b60)
Location: include/linux/dcache.h:318
Inline: True
```
```
In ipc/mqueue.c (c000000000674f60)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (c00000000069c8fc)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (c0000000006a5c04)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (c0000000006d5a24)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (c00000000139a014)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In drivers/base/devtmpfs.c (c000000000992050)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In net/unix/af_unix.c (c000000000e17e78)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In kernel/bpf/inode.c (ffffffe0001adc1c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
```
```
In mm/shmem.c (ffffffe0001f12be)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffe00025b390)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
```
```
In fs/namei.c (ffffffe000264588)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
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
```
```
In fs/dcache.c (ffffffe00026f006)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffe00027c8b0)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (ffffffe0002807c8)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
```
```
In fs/fs_context.c (ffffffe00028f55a)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (ffffffe0002e3ab6)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/dir.c (ffffffe0002ea6d4)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_detach_prep
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/ramfs/inode.c (ffffffe00035471e)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffe000354f0c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (ffffffe000362402)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffe000364052)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffe00036cb9a)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/debugfs/inode.c (ffffffe00037f8ce)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/tracefs/inode.c (ffffffe0003829ec)
Location: include/linux/dcache.h:318
Inline: True
```
```
In ipc/mqueue.c (ffffffe00038d73c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffffffe0003a1a7c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffe0003a9a2c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffe0003c4ea6)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffe000026624)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In drivers/base/devtmpfs.c (ffffffe000587968)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In net/unix/af_unix.c (ffffffe00083e0ec)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In kernel/bpf/inode.c (ffffffff811ea4d7)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
```
```
In mm/shmem.c (ffffffff8123baf0)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff812da011)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
```
```
In fs/namei.c (ffffffff812e4d13)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
```
```
In fs/dcache.c (ffffffff812f267e)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff812fd38b)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (ffffffff81303f40)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
```
```
In fs/fs_context.c (ffffffff813161d6)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (ffffffff8137ade2)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/dir.c (ffffffff81383f3d)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/ramfs/inode.c (ffffffff813fa82c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff813fb6ac)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (ffffffff8140a042)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff8140c0e3)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff81415680)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff81429a25)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8142c1e7)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/efivarfs/inode.c (ffffffff8142df34)
Location: include/linux/dcache.h:318
Inline: True
```
```
In ipc/mqueue.c (ffffffff8143c423)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffffffff8145222b)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff8145ac9b)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff8147670f)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff828da2d2)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In drivers/base/devtmpfs.c (ffffffff816ce24b)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In net/unix/af_unix.c (ffffffff819d0e6f)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In kernel/bpf/inode.c (ffffffff811dd297)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
```
```
In mm/shmem.c (ffffffff8122eaf0)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff812cac91)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
```
```
In fs/namei.c (ffffffff812d5953)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
```
```
In fs/dcache.c (ffffffff812e32ae)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff812edfab)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (ffffffff812f4b60)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
```
```
In fs/fs_context.c (ffffffff81306dc6)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (ffffffff8136b8b2)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/dir.c (ffffffff813749cd)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/ramfs/inode.c (ffffffff813eb2ac)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff813ec12c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (ffffffff813faac2)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff813fcb63)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff81406100)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff8141a4a5)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8141cc67)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/efivarfs/inode.c (ffffffff8141e9b4)
Location: include/linux/dcache.h:318
Inline: True
```
```
In ipc/mqueue.c (ffffffff8142ce93)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffffffff81442c7b)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff8144b6cb)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff8146712f)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff828d29ee)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In drivers/base/devtmpfs.c (ffffffff816a957b)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In net/unix/af_unix.c (ffffffff8198dc2f)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In kernel/bpf/inode.c (ffffffff811e82a7)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
```
```
In mm/shmem.c (ffffffff81239890)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff812d7e21)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
```
```
In fs/namei.c (ffffffff812e2b23)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
```
```
In fs/dcache.c (ffffffff812f048e)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff812fb17b)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (ffffffff81301d30)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
```
```
In fs/fs_context.c (ffffffff81313fc6)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (ffffffff813788b2)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/dir.c (ffffffff81381a0d)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/ramfs/inode.c (ffffffff813f7bac)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff813f8a2c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (ffffffff814073c2)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff81409463)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff81412a00)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff81425bc5)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81428387)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/efivarfs/inode.c (ffffffff8142a0d4)
Location: include/linux/dcache.h:318
Inline: True
```
```
In ipc/mqueue.c (ffffffff814385c3)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffffffff8144e2cb)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff81456d3b)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff814727af)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff828ed046)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In drivers/base/devtmpfs.c (ffffffff816fc7bb)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In net/unix/af_unix.c (ffffffff81a3b8ef)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In kernel/bpf/inode.c (ffffffff811f6657)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
```
```
In mm/shmem.c (ffffffff81248f80)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
```
```
In fs/super.c (ffffffff812e8c61)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/super.c:vfs_get_super
```
```
In fs/namei.c (ffffffff812f2a63)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_mountpoint
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
```
```
In fs/dcache.c (ffffffff813015e9)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:shrink_dcache_for_umount
```
```
In fs/namespace.c (ffffffff8130c7cb)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
```
```
In fs/libfs.c (ffffffff81313100)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/libfs.c:simple_link
```
```
In fs/fs_context.c (ffffffff81325816)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernfs/mount.c (ffffffff8138c362)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_node_dentry
```
```
In fs/configfs/dir.c (ffffffff8139553d)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/ramfs/inode.c (ffffffff8140d83c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff8140e82c)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/ecryptfs/inode.c (ffffffff8141d082)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/main.c (ffffffff8141f123)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff81428679)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff8143ca85)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8143f247)
Location: include/linux/dcache.h:318
Inline: True
```
```
In fs/efivarfs/inode.c (ffffffff81440f94)
Location: include/linux/dcache.h:318
Inline: True
```
```
In ipc/mqueue.c (ffffffff8144f601)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In security/inode.c (ffffffff8146569b)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/hooks.c (ffffffff8146bcc0)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
```
In security/smack/smack_lsm.c (ffffffff8148a09f)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff828f2468)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
```
In drivers/base/devtmpfs.c (ffffffff8171705b)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In net/unix/af_unix.c (ffffffff81a46c3f)
Location: include/linux/dcache.h:318
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
</details>
</li>
</ul>

## Differences
