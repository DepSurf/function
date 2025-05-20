# Function: <code>d_can_lookup</code>

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
In mm/shmem.c (ffffffff811a7ab5)
Location: include/linux/dcache.h:425
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
```
```
In fs/namei.c (0)
Location: include/linux/dcache.h:425
Inline: True
```
```
In fs/namespace.c (ffffffff8122e00d)
Location: include/linux/dcache.h:425
Inline: True
Inline callers:
  - fs/namespace.c:graft_tree
  - fs/namespace.c:do_mount
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:425
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:425
Inline: True
```
```
In fs/ecryptfs/file.c (0)
Location: include/linux/dcache.h:425
Inline: True
```
```
In fs/ecryptfs/inode.c (0)
Location: include/linux/dcache.h:425
Inline: True
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:425
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:425
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/dcache.h:425
Inline: True
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:425
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/dcache.h:425
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:425
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
In mm/shmem.c (ffffffff811bde65)
Location: include/linux/dcache.h:399
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
```
```
In fs/namei.c (ffffffff81241f5b)
Location: include/linux/dcache.h:399
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
```
```
In fs/namespace.c (ffffffff81257e1d)
Location: include/linux/dcache.h:399
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:399
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:399
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff8133635a)
Location: include/linux/dcache.h:399
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:399
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:399
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/dcache.h:399
Inline: True
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:399
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/dcache.h:399
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:399
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
In mm/shmem.c (ffffffff811ce4ad)
Location: include/linux/dcache.h:399
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
```
```
In fs/namei.c (ffffffff81254e1c)
Location: include/linux/dcache.h:399
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
```
```
In fs/namespace.c (ffffffff8126b2ad)
Location: include/linux/dcache.h:399
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:399
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:399
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff8134c019)
Location: include/linux/dcache.h:399
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:399
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:399
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/dcache.h:399
Inline: True
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:399
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/dcache.h:399
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:399
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
In mm/shmem.c (0)
Location: include/linux/dcache.h:405
Inline: True
```
```
In fs/open.c (ffffffff8124e6a8)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/open.c:SyS_fchdir
```
```
In fs/namei.c (ffffffff8125f3c1)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
```
```
In fs/namespace.c (0)
Location: include/linux/dcache.h:405
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:405
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:405
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff81360cc5)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (0)
Location: include/linux/dcache.h:405
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:405
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/dcache.h:405
Inline: True
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:405
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/dcache.h:405
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/dcache.h:405
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/dcache.h:405
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
In mm/shmem.c (0)
Location: include/linux/dcache.h:406
Inline: True
```
```
In fs/open.c (ffffffff81270628)
Location: include/linux/dcache.h:406
Inline: True
Inline callers:
  - fs/open.c:SyS_fchdir
```
```
In fs/namei.c (ffffffff812826d1)
Location: include/linux/dcache.h:406
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
```
```
In fs/namespace.c (ffffffff8129b462)
Location: include/linux/dcache.h:406
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (0)
Location: include/linux/dcache.h:406
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:406
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff81385833)
Location: include/linux/dcache.h:406
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff813904cd)
Location: include/linux/dcache.h:406
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:406
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/dcache.h:406
Inline: True
```
```
In security/inode.c (0)
Location: include/linux/dcache.h:406
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/dcache.h:406
Inline: True
```
```
In security/tomoyo/file.c (ffffffff813f991b)
Location: include/linux/dcache.h:406
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/dcache.h:406
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
In mm/shmem.c (ffffffff81210133)
Location: include/linux/dcache.h:407
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffff81294a1a)
Location: include/linux/dcache.h:407
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/namei.c (ffffffff812aca3b)
Location: include/linux/dcache.h:407
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
```
```
In fs/dcache.c (ffffffff812b4e15)
Location: include/linux/dcache.h:407
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
```
```
In fs/namespace.c (ffffffff812c1597)
Location: include/linux/dcache.h:407
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff812c7379)
Location: include/linux/dcache.h:407
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:407
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff813b45a3)
Location: include/linux/dcache.h:407
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff813bf570)
Location: include/linux/dcache.h:407
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff813c77df)
Location: include/linux/dcache.h:407
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff813d1084)
Location: include/linux/dcache.h:407
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
```
```
In security/inode.c (ffffffff813f7075)
Location: include/linux/dcache.h:407
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81400722)
Location: include/linux/dcache.h:407
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/tomoyo/file.c (ffffffff8142a91c)
Location: include/linux/dcache.h:407
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff81430126)
Location: include/linux/dcache.h:407
Inline: True
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
In mm/shmem.c (ffffffff81225503)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffff812a94ca)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/namei.c (ffffffff812c1b3b)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffffffff812ca075)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
```
```
In fs/namespace.c (ffffffff812d67f9)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff812dc0c9)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:404
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff813cdac3)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff813d8bd7)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff813e09ef)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff813eb7b1)
Location: include/linux/dcache.h:404
Inline: True
```
```
In security/inode.c (ffffffff81412b25)
Location: include/linux/dcache.h:404
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8141c7c3)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/tomoyo/file.c (ffffffff814471ec)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff8144cc76)
Location: include/linux/dcache.h:404
Inline: True
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
In mm/shmem.c (ffffffff812326c3)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffff812c5c23)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/namei.c (ffffffff812de09c)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (ffffffff812f3b13)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff812fa769)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:402
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff813f8673)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff81403587)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8140c5bf)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff81417f3b)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In security/inode.c (ffffffff8144051b)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff8144a1b1)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/tomoyo/file.c (ffffffff81474e04)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff8147a44b)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In mm/shmem.c (ffffffff812408f3)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffff812d7633)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/namei.c (ffffffff812efbbc)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (ffffffff813056c3)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff8130c879)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:402
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff814124d3)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff8141d497)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8142612f)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff81431dfb)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In security/inode.c (ffffffff81459deb)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff81463ec9)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/tomoyo/file.c (ffffffff8148eba4)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff8149414b)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In mm/shmem.c (ffffffff812718b3)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffff8130d7e3)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/namei.c (ffffffff81327e6d)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (ffffffff8133f483)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff8134632d)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:404
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff81460b02)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff8146bff7)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8147561d)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff81481a43)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In security/inode.c (ffffffff814ad06b)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff814b7f84)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/tomoyo/file.c (ffffffff814e5d81)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff814eb5ab)
Location: include/linux/dcache.h:404
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In mm/shmem.c (ffffffff81278803)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffff81319ac3)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/namei.c (ffffffff8133496c)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (ffffffff8134b4e3)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff8135281d)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:405
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff8147c712)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff8148673c)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/fuse/dir.c (ffffffff814902d4)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff81bef7fe)
Location: include/linux/dcache.h:405
Inline: True
```
```
In security/inode.c (ffffffff814ca5bb)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff814d5c94)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/tomoyo/file.c (ffffffff81503181)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff8150898b)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In mm/shmem.c (ffffffff8127d80b)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffff81320652)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/namei.c (ffffffff8133aaa9)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (ffffffff81351d8a)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff8135953d)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:408
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff814821c2)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff8148c19c)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/fuse/dir.c (ffffffff81495d04)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff81be18a7)
Location: include/linux/dcache.h:408
Inline: True
```
```
In security/inode.c (ffffffff814d0beb)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff814dcaf4)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/tomoyo/file.c (ffffffff81509d51)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff8150f4fb)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/landlock/fs.c (ffffffff8153908d)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
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
In mm/shmem.c (ffffffff812bb98b)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffff8136d182)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/namei.c (ffffffff813886af)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (ffffffff813a00fa)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff813a79dd)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:408
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff814d90b2)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff814e39ac)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/fuse/dir.c (ffffffff814ed7c4)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff81cd2469)
Location: include/linux/dcache.h:408
Inline: True
```
```
In security/inode.c (ffffffff8152991b)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff81535fc4)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/tomoyo/file.c (ffffffff8156723d)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff8156d05b)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/landlock/fs.c (ffffffff815978cd)
Location: include/linux/dcache.h:408
Inline: True
Inline callers:
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
In fs/open.c (ffffffff813ebd7f)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/namei.c (ffffffff814096bb)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (ffffffff8142377e)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff8142ca2a)
Location: include/linux/dcache.h:398
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
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:398
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81456bfc)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/ecryptfs/inode.c (ffffffff815668b8)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff81571d9b)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/fuse/dir.c (ffffffff8157c667)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff8158d204)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
```
```
In security/inode.c (ffffffff815bf138)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff815cc427)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/tomoyo/file.c (ffffffff81602deb)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff81609648)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/landlock/fs.c (ffffffff8163a697)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
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
In fs/open.c (ffffffff81474221)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/namei.c (ffffffff81493d6b)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (ffffffff814afede)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff814ba17a)
Location: include/linux/dcache.h:398
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
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:398
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e5e80)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/ecryptfs/inode.c (ffffffff81609e41)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff816171cb)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/fuse/dir.c (ffffffff81622087)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff81633d04)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
```
```
In security/inode.c (ffffffff8166b528)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff81679647)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/tomoyo/file.c (ffffffff816b3f6b)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff816bb148)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/landlock/fs.c (ffffffff816f1c1b)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
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
In fs/open.c (ffffffff814a8bcf)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/namei.c (ffffffff814c8dd9)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (ffffffff814e4f29)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff814ef11a)
Location: include/linux/dcache.h:398
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
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:398
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151cb13)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/ecryptfs/inode.c (ffffffff81641d01)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff8164f2bc)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/fuse/dir.c (ffffffff8165a4e4)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff8166c022)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
```
```
In security/inode.c (ffffffff816a3c88)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff816b17f7)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/tomoyo/file.c (ffffffff816ec92b)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff816f3838)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/landlock/fs.c (ffffffff8172c014)
Location: include/linux/dcache.h:398
Inline: True
Inline callers:
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
In fs/open.c (ffffffff814d9c2f)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/namei.c (ffffffff814fb698)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (ffffffff81518d59)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff81523175)
Location: include/linux/dcache.h:405
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
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:405
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81551060)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/ecryptfs/inode.c (ffffffff8167b324)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff816887f2)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/fuse/dir.c (ffffffff816941b4)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff816a64c2)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
```
```
In security/inode.c (ffffffff816e06e8)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff816ee88a)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/tomoyo/file.c (ffffffff817296fb)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff817305c8)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/landlock/fs.c (ffffffff8176d1e3)
Location: include/linux/dcache.h:405
Inline: True
Inline callers:
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
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
In mm/shmem.c (ffff8000102d23b4)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffff80001037c9e8)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/open.c:__arm64_sys_fchdir
```
```
In fs/namei.c (ffff800010399318)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (ffff8000103b8dac)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffff8000103c10e4)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:402
Inline: True
```
```
In fs/ecryptfs/inode.c (ffff8000104f38e0)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffff8000104ff1fc)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffff800010509958)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffff800010515e08)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In security/inode.c (ffff80001054613c)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffff800010551f58)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/tomoyo/file.c (ffff8000105824f0)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffff80001058979c)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In mm/shmem.c (c04f9ae4)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (c0569050)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/open.c:__se_sys_fchdir
```
```
In fs/namei.c (c057f9a0)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (c059695c)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (c059d224)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:402
Inline: True
```
```
In fs/ecryptfs/inode.c (c06b1334)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (c06bc18c)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (c06c5904)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (c06d0b84)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In security/inode.c (c06fbf14)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (c0704260)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/tomoyo/file.c (c0734430)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (c073a9bc)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In mm/shmem.c (c00000000038fcd0)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (c000000000471c94)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/open.c:__se_sys_fchdir
```
```
In fs/namei.c (c000000000493b08)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (c0000000004b5ec0)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (c0000000004c0754)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:402
Inline: True
```
```
In fs/ecryptfs/inode.c (c000000000633b74)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (c000000000642914)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (c00000000064f7d4)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (c00000000065e93c)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In security/inode.c (c00000000069cb6c)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (c0000000006a8748)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/tomoyo/file.c (c0000000006f0e20)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (c0000000006fa7ec)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In mm/shmem.c (ffffffe0001ef12a)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffe00025438a)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/open.c:__se_sys_fchdir
```
```
In fs/namei.c (ffffffe000266dba)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (ffffffe00027b17e)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffe0002814b4)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:402
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffe000362d6e)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffe00036cf58)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffe00037539c)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffe00037f5b2)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In security/inode.c (ffffffe0003a1c3c)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffe0003aafa8)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/tomoyo/file.c (ffffffe0003d2a24)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffe0003d8684)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In mm/shmem.c (ffffffff81238f43)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffff812cfc13)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/namei.c (ffffffff812e819c)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (ffffffff812fdca3)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff81304e59)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:402
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff8140aab3)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff81415a77)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8141e70f)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff8142a3db)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In security/inode.c (ffffffff814523cb)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff8145c4a9)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/tomoyo/file.c (ffffffff81487184)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff8148c72b)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In mm/shmem.c (ffffffff8122bf83)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffff812c0893)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/namei.c (ffffffff812d8ddc)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (ffffffff812ee8c3)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff812f5a79)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:402
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff813fb533)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff814064f7)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8140f18f)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff8141ae5b)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In security/inode.c (ffffffff81442e1b)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff8144ced9)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/tomoyo/file.c (ffffffff81477ba4)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff8147d14b)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In mm/shmem.c (ffffffff81236ce3)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffff812cda23)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/namei.c (ffffffff812e5fac)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (ffffffff812fba93)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff81302c49)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:402
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff81407e33)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff81412df7)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8141a8af)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff8142657b)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In security/inode.c (ffffffff8144e46b)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff81458549)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/tomoyo/file.c (ffffffff81483224)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff814887cb)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In mm/shmem.c (ffffffff81244193)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - mm/shmem.c:shmem_rename2
```
```
In fs/open.c (ffffffff812de833)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/namei.c (ffffffff812f6f2c)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/namespace.c (ffffffff8130cdb3)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/namespace.c:graft_tree
```
```
In fs/libfs.c (ffffffff813131f9)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/dcache.h:402
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff8141daf3)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
```
In fs/exportfs/expfs.c (ffffffff81428a77)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8143164f)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
```
```
In fs/debugfs/inode.c (ffffffff8143d43b)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In security/inode.c (ffffffff8146583b)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/selinux/hooks.c (ffffffff8146d369)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/tomoyo/file.c (ffffffff8149adb4)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/apparmor/apparmorfs.c (ffffffff814a030b)
Location: include/linux/dcache.h:402
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
</details>
</li>
</ul>

## Differences
