# Function: <code>new_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81229030)
Location: fs/inode.c:901
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:mount_pseudo
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_file
  - security/selinux/selinuxfs.c:sel_make_inode
```
**Symbols:**

```
ffffffff81229030-ffffffff8122905c: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81251730)
Location: fs/inode.c:910
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:mount_pseudo
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:devpts_mount
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:__securityfs_setup_d_inode
  - security/selinux/selinuxfs.c:sel_make_inode
```
**Symbols:**

```
ffffffff81251730-ffffffff8125175c: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81264830)
Location: fs/inode.c:912
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:mount_pseudo_xattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:__securityfs_setup_d_inode
  - security/selinux/selinuxfs.c:sel_make_inode
```
**Symbols:**

```
ffffffff81264830-ffffffff8126485c: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81272060)
Location: fs/inode.c:913
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:mount_pseudo_xattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:__aafs_setup_d_inode
```
**Symbols:**

```
ffffffff81272060-ffffffff81272090: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81294980)
Location: fs/inode.c:913
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:mount_pseudo_xattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
```
**Symbols:**

```
ffffffff81294980-ffffffff812949b0: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812baa80)
Location: fs/inode.c:918
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:mount_pseudo_xattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812baa80-ffffffff812baaac: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cfdc0)
Location: fs/inode.c:926
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:mount_pseudo_xattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812cfdc0-ffffffff812cfdec: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ecd10)
Location: fs/inode.c:939
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812ecd10-ffffffff812ecd3e: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fe8a0)
Location: fs/inode.c:950
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812fe8a0-ffffffff812fe8ce: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81335ee0)
Location: fs/inode.c:951
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:mknod_ptmx
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_perm_files
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_mk_null_file
```
**Symbols:**

```
ffffffff81335ee0-ffffffff81335f9f: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81341870)
Location: fs/inode.c:950
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/block_dev.c:bdev_alloc
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:mknod_ptmx
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_perm_files
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_mk_null_file
```
**Symbols:**

```
ffffffff81341870-ffffffff8134192f: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81347d00)
Location: fs/inode.c:957
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/block_dev.c:bdev_alloc
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff81347d00-ffffffff81347dbf: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81395910)
Location: fs/inode.c:961
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - block/bdev.c:bdev_alloc
```
**Symbols:**

```
ffffffff81395910-ffffffff813959cf: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81417e40)
Location: fs/inode.c:1042
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - block/bdev.c:bdev_alloc
```
**Symbols:**

```
ffffffff81417e40-ffffffff81417ef6: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a3610)
Location: fs/inode.c:1040
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - block/bdev.c:bdev_alloc
```
**Symbols:**

```
ffffffff814a3610-ffffffff814a36b6: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d8780)
Location: fs/inode.c:1042
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - block/bdev.c:bdev_alloc
```
**Symbols:**

```
ffffffff814d8780-ffffffff814d881f: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8150b010)
Location: fs/inode.c:1027
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:__shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - block/bdev.c:bdev_alloc
```
**Symbols:**

```
ffffffff8150b010-ffffffff8150b0af: new_inode (STB_GLOBAL)
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
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103af748)
Location: fs/inode.c:950
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffff8000103af748-ffff8000103af78c: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058f4d0)
Location: fs/inode.c:950
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
c058f4d0-c058f500: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004ab290)
Location: fs/inode.c:950
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
c0000000004ab290-c0000000004ab2e4: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe0002741e2)
Location: fs/inode.c:950
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffe0002741e2-ffffffe00027421a: new_inode (STB_GLOBAL)
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
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f6e80)
Location: fs/inode.c:950
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812f6e80-ffffffff812f6eae: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e7aa0)
Location: fs/inode.c:950
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812e7aa0-ffffffff812e7ace: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4c90)
Location: fs/inode.c:950
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812f4c90-ffffffff812f4cbe: new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *new_inode(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81305e20)
Location: fs/inode.c:950
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/configfs/inode.c:configfs_new_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff81305e20-ffffffff81305e4e: new_inode (STB_GLOBAL)
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
