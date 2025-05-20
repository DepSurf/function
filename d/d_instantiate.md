# Function: <code>d_instantiate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81224460)
Location: fs/dcache.c:1772
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_link
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:shmem_symlink
  - fs/pipe.c:create_pipe_files
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:mount_pseudo
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_fill_super
  - fs/nsfs.c:ns_get_path
  - fs/aio.c:SyS_io_setup
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_link
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_interpose
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - ipc/mqueue.c:mqueue_create
  - security/inode.c:securityfs_create_file
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff81224460-ffffffff812244c4: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124b370)
Location: fs/dcache.c:1808
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/pipe.c:create_pipe_files
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo
  - fs/nsfs.c:ns_get_path
  - fs/aio.c:aio_setup_ring
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_interpose
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create
  - security/inode.c:__securityfs_setup_d_inode
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff8124b370-ffffffff8124b3c6: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125e350)
Location: fs/dcache.c:1817
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/pipe.c:create_pipe_files
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
  - fs/nsfs.c:__ns_get_path
  - fs/aio.c:aio_setup_ring
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_interpose
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create
  - security/inode.c:__securityfs_setup_d_inode
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff8125e350-ffffffff8125e3a6: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126bbb0)
Location: fs/dcache.c:1847
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/pipe.c:create_pipe_files
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
  - fs/nsfs.c:__ns_get_path
  - fs/aio.c:aio_setup_ring
  - fs/configfs/inode.c:configfs_create
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_interpose
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:__aafs_setup_d_inode
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff8126bbb0-ffffffff8126bc07: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128e440)
Location: fs/dcache.c:1859
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/pipe.c:create_pipe_files
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
  - fs/nsfs.c:__ns_get_path
  - fs/aio.c:aio_setup_ring
  - fs/configfs/inode.c:configfs_create
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_interpose
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create
  - security/inode.c:securityfs_create_dentry
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff8128e440-ffffffff8128e495: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b4d40)
Location: fs/dcache.c:1867
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/pipe.c:create_pipe_files
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
  - fs/aio.c:aio_setup_ring
  - fs/configfs/inode.c:configfs_create
  - fs/ext4/namei.c:ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_interpose
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff812b4d40-ffffffff812b4d95: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ca210)
Location: fs/dcache.c:1875
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
  - fs/configfs/inode.c:configfs_create
  - fs/ext4/namei.c:ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_interpose
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812ca210-ffffffff812ca265: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e6c70)
Location: fs/dcache.c:1949
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/configfs/inode.c:configfs_create
  - fs/ext4/namei.c:ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_interpose
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812e6c70-ffffffff812e6cc8: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f87e0)
Location: fs/dcache.c:1949
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ext4/namei.c:ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_interpose
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812f87e0-ffffffff812f8838: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813314f0)
Location: fs/dcache.c:1970
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mklink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/nsfs.c:__ns_get_path
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ext4/namei.c:ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_create
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_mk_null_file
```
**Symbols:**

```
ffffffff813314f0-ffffffff81331548: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133ce80)
Location: fs/dcache.c:1977
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/nsfs.c:__ns_get_path
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ext4/namei.c:__ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_create
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_mk_null_file
```
**Symbols:**

```
ffffffff8133ce80-ffffffff8133ced8: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81343300)
Location: fs/dcache.c:2004
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/nsfs.c:__ns_get_path
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ext4/namei.c:__ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_create
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff81343300-ffffffff81343358: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8139119f)
Location: fs/dcache.c:2005
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_make_root
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/libfs.c:simple_link
  - fs/nsfs.c:__ns_get_path
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ext4/namei.c:__ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_create
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff81390c90-ffffffff81390ce8: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81412a12)
Location: fs/dcache.c:2030
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_make_root
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/libfs.c:simple_link
  - fs/nsfs.c:__ns_get_path
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ext4/namei.c:__ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_create
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff814127e0-ffffffff8141283b: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149dda3)
Location: fs/dcache.c:2030
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_make_root
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/libfs.c:simple_link
  - fs/nsfs.c:__ns_get_path
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ext4/namei.c:__ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff8149da20-ffffffff8149da7b: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d30c6)
Location: fs/dcache.c:2030
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_make_root
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/libfs.c:simple_link
  - fs/nsfs.c:__ns_get_path
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ext4/namei.c:__ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff814d2e60-ffffffff814d2ebb: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff815057ab)
Location: fs/dcache.c:1874
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_make_root
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ext4/namei.c:__ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
  - fs/efivarfs/inode.c:efivarfs_create
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff81505650-ffffffff815056ab: d_instantiate (STB_GLOBAL)
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
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a6f60)
Location: fs/dcache.c:1949
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ext4/namei.c:ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_interpose
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffff8000103a6f60-ffff8000103a7008: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0588540)
Location: fs/dcache.c:1949
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/nsfs.c:__ns_get_path
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ext4/namei.c:ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_interpose
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
c0588540-c05885a8: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a1410)
Location: fs/dcache.c:1949
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ext4/namei.c:ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_interpose
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
c0000000004a1410-c0000000004a14d0: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026cf96)
Location: fs/dcache.c:1949
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ext4/namei.c:ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_interpose
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffe00026cf96-ffffffe00026d02a: d_instantiate (STB_GLOBAL)
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
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0dc0)
Location: fs/dcache.c:1949
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ext4/namei.c:ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_interpose
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812f0dc0-ffffffff812f0e18: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e19f0)
Location: fs/dcache.c:1949
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ext4/namei.c:ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_interpose
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812e19f0-ffffffff812e1a48: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812eebd0)
Location: fs/dcache.c:1949
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ext4/namei.c:ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_interpose
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812eebd0-ffffffff812eec28: d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void d_instantiate(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ffdc0)
Location: fs/dcache.c:1949
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ext4/namei.c:ext4_link
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/ecryptfs/inode.c:ecryptfs_interpose
  - fs/fuse/dir.c:fuse_create_open
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - ipc/mqueue.c:mqueue_create_attr
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812ffdc0-ffffffff812ffe16: d_instantiate (STB_GLOBAL)
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
