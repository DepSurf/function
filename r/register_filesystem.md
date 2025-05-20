# Function: <code>register_filesystem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8122b310)
Location: fs/filesystems.c:69
Inline: True
Direct callers:
  - init/do_mounts.c:init_rootfs
  - kernel/cgroup.c:cgroup_init
  - kernel/cpuset.c:cpuset_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff8122b310-ffffffff8122b381: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81253a70)
Location: fs/filesystems.c:69
Inline: True
Direct callers:
  - init/do_mounts.c:init_rootfs
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:cgroup_init
  - kernel/cpuset.c:cpuset_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff81253a70-ffffffff81253ae2: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81266cc0)
Location: fs/filesystems.c:69
Inline: True
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:cgroup_init
  - kernel/cpuset.c:cpuset_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff81266cc0-ffffffff81266d32: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81274290)
Location: fs/filesystems.c:70
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - mm/shmem.c:shmem_init
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff81274290-ffffffff81274302: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81296b90)
Location: fs/filesystems.c:71
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - mm/shmem.c:shmem_init
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff81296b90-ffffffff81296c02: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812bcda0)
Location: fs/filesystems.c:71
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:init_pstore_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/dax/super.c:dax_fs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812bcda0-ffffffff812bce12: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812d2060)
Location: fs/filesystems.c:71
Inline: False
Direct callers:
  - init/do_mounts.c:init_rootfs
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/dax/super.c:dax_fs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812d2060-ffffffff812d20d2: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812ef0b0)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812ef0b0-ffffffff812ef141: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81300b70)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff81300b70-ffffffff81300c01: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81339cf0)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff81339cf0-ffffffff81339dc4: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81345a00)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff81345a00-ffffffff81345ad4: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8134bdc0)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff8134bdc0-ffffffff8134be94: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81399c00)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - block/bdev.c:bdev_cache_init
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff81399c00-ffffffff81399cd4: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8141c6c0)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - block/bdev.c:bdev_cache_init
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff8141c6c0-ffffffff8141c7ad: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff814a87e0)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - block/bdev.c:bdev_cache_init
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff814a87e0-ffffffff814a88cd: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff814dd7d0)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - block/bdev.c:bdev_cache_init
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff814dd7d0-ffffffff814dd8bd: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81510220)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - block/bdev.c:bdev_cache_init
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff81510220-ffffffff8151030d: register_filesystem (STB_GLOBAL)
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
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffff8000103b2d70)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffff8000103b2d70-ffff8000103b2e74: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (c0591d74)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
c0591d74-c0591e2c: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (c0000000004aea90)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
c0000000004aea90-c0000000004aeb88: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffe000276ab6)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffe000276ab6-ffffffe000276b4c: register_filesystem (STB_GLOBAL)
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
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812f9150)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812f9150-ffffffff812f91e1: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812e9d70)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812e9d70-ffffffff812e9e01: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812f6f60)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812f6f60-ffffffff812f6fd7: register_filesystem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff813081c0)
Location: fs/filesystems.c:72
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/bpf/inode.c:bpf_init
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/block_dev.c:bdev_cache_init
  - fs/proc/root.c:proc_root_init
  - fs/sysfs/mount.c:sysfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/devpts/inode.c:init_devpts_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/ramfs/inode.c:init_ramfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/namei_vfat.c:init_vfat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/control.c:fuse_ctl_init
  - fs/debugfs/inode.c:debugfs_init
  - fs/tracefs/inode.c:tracefs_init
  - fs/pstore/inode.c:pstore_init_fs
  - fs/efivarfs/super.c:efivarfs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/inode.c:securityfs_init
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff813081c0-ffffffff81308256: register_filesystem (STB_GLOBAL)
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
