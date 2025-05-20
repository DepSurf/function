# Function: <code>unregister_filesystem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8122b0e0)
Location: fs/filesystems.c:101
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/hugetlbfs/inode.c:exit_hugetlbfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:exit_pstore_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - security/selinux/selinuxfs.c:exit_sel_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff8122b0e0-ffffffff8122b159: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81253840)
Location: fs/filesystems.c:101
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:exit_pstore_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - security/selinux/selinuxfs.c:exit_sel_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff81253840-ffffffff812538b9: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81266a90)
Location: fs/filesystems.c:101
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:exit_pstore_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - security/selinux/selinuxfs.c:exit_sel_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff81266a90-ffffffff81266b09: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81274310)
Location: fs/filesystems.c:102
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - mm/shmem.c:shmem_init
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:exit_pstore_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/dax/super.c:__dax_fs_exit
```
**Symbols:**

```
ffffffff81274310-ffffffff81274389: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81296c10)
Location: fs/filesystems.c:103
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - mm/shmem.c:shmem_init
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:exit_pstore_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/dax/super.c:__dax_fs_exit
```
**Symbols:**

```
ffffffff81296c10-ffffffff81296c89: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812bd1b0)
Location: fs/filesystems.c:103
Inline: True
Direct callers:
  - init/do_mounts.c:init_rootfs
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:exit_pstore_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/dax/super.c:dax_fs_init
  - drivers/dax/super.c:__dax_fs_exit
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812bd1b0-ffffffff812bd229: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812d2470)
Location: fs/filesystems.c:103
Inline: True
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/dax/super.c:dax_fs_init
  - drivers/dax/super.c:__dax_fs_exit
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812d2470-ffffffff812d24e9: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812ef4c0)
Location: fs/filesystems.c:107
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812ef4c0-ffffffff812ef539: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81300f90)
Location: fs/filesystems.c:107
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff81300f90-ffffffff81301009: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81339dd0)
Location: fs/filesystems.c:108
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff81339dd0-ffffffff81339e4f: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81345ae0)
Location: fs/filesystems.c:108
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff81345ae0-ffffffff81345b5f: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8134bea0)
Location: fs/filesystems.c:108
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff8134bea0-ffffffff8134bf1f: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81399ce0)
Location: fs/filesystems.c:108
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff81399ce0-ffffffff81399d5f: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8141c7b0)
Location: fs/filesystems.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff8141c7b0-ffffffff8141c849: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff814a88e0)
Location: fs/filesystems.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff814a88e0-ffffffff814a8979: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff814dd8d0)
Location: fs/filesystems.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff814dd8d0-ffffffff814dd969: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81510320)
Location: fs/filesystems.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff81510320-ffffffff815103b9: unregister_filesystem (STB_GLOBAL)
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
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffff8000103b2ed8)
Location: fs/filesystems.c:107
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffff8000103b2ed8-ffff8000103b2fcc: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (c0591e2c)
Location: fs/filesystems.c:107
Inline: True
Direct callers:
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
c0591e2c-c0591ee4: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (c0000000004af440)
Location: fs/filesystems.c:107
Inline: True
Direct callers:
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
c0000000004af440-c0000000004af53c: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffe000276d30)
Location: fs/filesystems.c:107
Inline: True
Direct callers:
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffe000276d30-ffffffe000276db6: unregister_filesystem (STB_GLOBAL)
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
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812f9570)
Location: fs/filesystems.c:107
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812f9570-ffffffff812f95e9: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812ea190)
Location: fs/filesystems.c:107
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812ea190-ffffffff812ea209: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812f7360)
Location: fs/filesystems.c:107
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812f7360-ffffffff812f73d9: unregister_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int unregister_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81308260)
Location: fs/filesystems.c:107
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/configfs/mount.c:configfs_exit
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:exit_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - fs/fuse/control.c:fuse_ctl_cleanup
  - fs/pstore/inode.c:pstore_exit_fs
  - fs/efivarfs/super.c:efivarfs_exit
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff81308260-ffffffff813082e3: unregister_filesystem (STB_GLOBAL)
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
