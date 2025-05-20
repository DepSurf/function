# Function: <code>mntget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122b610)
Location: fs/namespace.c:1149
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:__shmem_file_setup
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:path_get
  - fs/namei.c:follow_managed
  - fs/namei.c:pick_link
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_openat
  - fs/libfs.c:simple_pin_fs
  - fs/nsfs.c:ns_get_path
  - fs/aio.c:SyS_io_setup
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - ipc/mqueue.c:SyS_mq_open
  - net/socket.c:sock_alloc_file
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8122b610-ffffffff8122b62a: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812582e8)
Location: fs/namespace.c:1149
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:__shmem_file_setup
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:path_mountpoint
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:path_get
  - fs/libfs.c:simple_pin_fs
  - fs/nsfs.c:ns_get_path
  - fs/aio.c:aio_setup_ring
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - ipc/mqueue.c:SyS_mq_open
  - net/socket.c:sock_alloc_file
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81253d80-ffffffff81253d9a: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8126b780)
Location: fs/namespace.c:1194
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:__shmem_file_setup
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:path_get
  - fs/libfs.c:simple_pin_fs
  - fs/nsfs.c:__ns_get_path
  - fs/aio.c:aio_setup_ring
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - ipc/mqueue.c:SyS_mq_open
  - net/socket.c:sock_alloc_file
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81267050-ffffffff8126706a: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81278f42)
Location: fs/namespace.c:1195
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:path_get
  - fs/libfs.c:simple_pin_fs
  - fs/nsfs.c:__ns_get_path
  - fs/aio.c:aio_setup_ring
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - ipc/mqueue.c:do_mq_open
  - net/socket.c:sock_alloc_file
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812748a0-ffffffff812748ba: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8129b982)
Location: fs/namespace.c:1260
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/libfs.c:simple_pin_fs
  - fs/nsfs.c:__ns_get_path
  - fs/aio.c:aio_setup_ring
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - ipc/mqueue.c:do_mq_open
  - net/socket.c:sock_alloc_file
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812971d0-ffffffff812971ec: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812c1a56)
Location: fs/namespace.c:1286
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/libfs.c:simple_pin_fs
  - fs/aio.c:aio_setup_ring
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc_file
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812bd410-ffffffff812bd42b: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d6d06)
Location: fs/namespace.c:1198
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812d2720-ffffffff812d273b: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f3273)
Location: fs/namespace.c:1208
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812ef860-ffffffff812ef87a: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81304e33)
Location: fs/namespace.c:1208
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81301330-ffffffff8130134a: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133ea0a)
Location: fs/namespace.c:1224
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/libfs.c:simple_pin_fs
  - fs/nsfs.c:__ns_get_path
  - fs/fhandle.c:handle_to_path
  - fs/fhandle.c:handle_to_path
  - fs/ecryptfs/inode.c:ecryptfs_lookup_interpose
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - net/unix/af_unix.c:unix_mknod
```
**Symbols:**

```
ffffffff8133a540-ffffffff8133a55a: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134aa6a)
Location: fs/namespace.c:1227
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/libfs.c:simple_pin_fs
  - fs/nsfs.c:__ns_get_path
  - fs/fhandle.c:handle_to_path
  - fs/fhandle.c:handle_to_path
  - fs/ecryptfs/inode.c:ecryptfs_lookup_interpose
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - net/unix/af_unix.c:unix_mknod
```
**Symbols:**

```
ffffffff813461b0-ffffffff813461ca: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813512bf)
Location: fs/namespace.c:1237
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__do_sys_open_tree
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/libfs.c:simple_pin_fs
  - fs/nsfs.c:__ns_get_path
  - fs/fhandle.c:handle_to_path
  - fs/fhandle.c:handle_to_path
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8134c570-ffffffff8134c58a: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139f683)
Location: fs/namespace.c:1246
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__do_sys_open_tree
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/libfs.c:simple_pin_fs
  - fs/nsfs.c:__ns_get_path
  - fs/fhandle.c:handle_to_path
  - fs/fhandle.c:handle_to_path
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff8139a340-ffffffff8139a35a: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81422b72)
Location: fs/namespace.c:1287
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/libfs.c:simple_pin_fs
  - fs/nsfs.c:__ns_get_path
  - fs/fhandle.c:handle_to_path
  - fs/fhandle.c:handle_to_path
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:policy_get_link
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff8141ce90-ffffffff8141ceb2: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814af201)
Location: fs/namespace.c:1392
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/libfs.c:simple_pin_fs
  - fs/nsfs.c:__ns_get_path
  - fs/fhandle.c:handle_to_path
  - fs/fhandle.c:handle_to_path
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:policy_get_link
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff814a9150-ffffffff814a9172: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e4164)
Location: fs/namespace.c:1355
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/libfs.c:simple_pin_fs
  - fs/nsfs.c:__ns_get_path
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:policy_get_link
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff814de090-ffffffff814de0b2: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81517e7d)
Location: fs/namespace.c:1368
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/libfs.c:simple_pin_fs
  - fs/nsfs.c:__ns_get_path
  - fs/fhandle.c:handle_to_path
  - fs/fhandle.c:handle_to_path
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:policy_get_link
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff81510ae0-ffffffff81510b02: mntget (STB_GLOBAL)
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
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b86b0)
Location: fs/namespace.c:1208
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__arm64_sys_open_tree
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffff8000103b4bd0-ffff8000103b4c1c: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c05981e4)
Location: fs/namespace.c:1208
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__se_sys_open_tree
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:path_get
  - fs/libfs.c:simple_pin_fs
  - fs/nsfs.c:__ns_get_path
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - ipc/mqueue.c:__se_sys_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
c059272c-c059276c: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b566c)
Location: fs/namespace.c:1208
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__se_sys_open_tree
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
c0000000004b1280-c0000000004b12e8: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027c918)
Location: fs/namespace.c:1208
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__se_sys_open_tree
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - ipc/mqueue.c:__se_sys_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffe000277232-ffffffe00027727e: mntget (STB_GLOBAL)
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
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fd413)
Location: fs/namespace.c:1208
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812f9910-ffffffff812f992a: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ee033)
Location: fs/namespace.c:1208
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812ea530-ffffffff812ea54a: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fb203)
Location: fs/namespace.c:1208
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812f7700-ffffffff812f771a: mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *mntget(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130c853)
Location: fs/namespace.c:1208
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:open_detached_copy
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:pick_link
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:path_get
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - ipc/mqueue.c:do_mq_open
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81308940-ffffffff8130895a: mntget (STB_GLOBAL)
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
