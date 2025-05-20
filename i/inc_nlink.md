# Function: <code>inc_nlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81226cc0)
Location: fs/inode.c:327
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_link
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_rename
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_file
  - security/inode.c:securityfs_create_file
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
```
**Symbols:**

```
ffffffff81226cc0-ffffffff81226d11: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124f3e0)
Location: fs/inode.c:334
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:__securityfs_setup_d_inode
  - security/inode.c:__securityfs_setup_d_inode
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
```
**Symbols:**

```
ffffffff8124f3e0-ffffffff8124f431: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81262410)
Location: fs/inode.c:336
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:__securityfs_setup_d_inode
  - security/inode.c:__securityfs_setup_d_inode
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
```
**Symbols:**

```
ffffffff81262410-ffffffff81262461: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8126fc60)
Location: fs/inode.c:337
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:init_dir
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/apparmor/apparmorfs.c:__aafs_setup_d_inode
  - security/apparmor/apparmorfs.c:__aafs_setup_d_inode
```
**Symbols:**

```
ffffffff8126fc60-ffffffff8126fc9c: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81292580)
Location: fs/inode.c:337
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:init_dir
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
```
**Symbols:**

```
ffffffff81292580-ffffffff812925bb: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8030)
Location: fs/inode.c:339
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:init_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
```
**Symbols:**

```
ffffffff812b8030-ffffffff812b806b: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cd180)
Location: fs/inode.c:339
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:init_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
```
**Symbols:**

```
ffffffff812cd180-ffffffff812cd1bc: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:352
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:init_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
```
**Symbols:**

```
ffffffff812ecf0d-ffffffff812ecf20: inc_nlink.cold (STB_LOCAL)
ffffffff812ea330-ffffffff812ea372: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fbca0)
Location: fs/inode.c:356
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
```
**Symbols:**

```
ffffffff812fbca0-ffffffff812fbcdc: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81334a40)
Location: fs/inode.c:357
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
```
**Symbols:**

```
ffffffff81334a40-ffffffff81334a7c: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813403b0)
Location: fs/inode.c:358
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff813403b0-ffffffff813403ec: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813468e0)
Location: fs/inode.c:358
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff813468e0-ffffffff8134691c: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81394310)
Location: fs/inode.c:362
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81394310-ffffffff8139434c: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81416050)
Location: fs/inode.c:386
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81416050-ffffffff8141609c: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a10b0)
Location: fs/inode.c:384
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff814a10b0-ffffffff814a10fc: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d63c0)
Location: fs/inode.c:384
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff814d63c0-ffffffff814d640c: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81508790)
Location: fs/inode.c:385
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:__shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81508790-ffffffff815087dc: inc_nlink (STB_GLOBAL)
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
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103accf0)
Location: fs/inode.c:356
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
```
**Symbols:**

```
ffff8000103accf0-ffff8000103acd6c: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058c65c)
Location: fs/inode.c:356
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
```
**Symbols:**

```
c058c65c-c058c6d8: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a6540)
Location: fs/inode.c:356
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
```
**Symbols:**

```
c0000000004a6540-c0000000004a659c: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000270cfa)
Location: fs/inode.c:356
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
```
**Symbols:**

```
ffffffe000270cfa-ffffffe000270d4a: inc_nlink (STB_GLOBAL)
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
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4280)
Location: fs/inode.c:356
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
```
**Symbols:**

```
ffffffff812f4280-ffffffff812f42bc: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e4eb0)
Location: fs/inode.c:356
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
```
**Symbols:**

```
ffffffff812e4eb0-ffffffff812e4eec: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f2090)
Location: fs/inode.c:356
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
```
**Symbols:**

```
ffffffff812f2090-ffffffff812f20cc: inc_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inc_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81303660)
Location: fs/inode.c:356
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mkdir
  - mm/shmem.c:shmem_get_inode
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ramfs/inode.c:ramfs_mkdir
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/control.c:fuse_ctl_add_conn
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_dir
```
**Symbols:**

```
ffffffff81303660-ffffffff8130369c: inc_nlink (STB_GLOBAL)
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
