# Function: <code>new_encode_dev</code>

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
In init/do_mounts.c (0)
Location: include/linux/kdev_t.h:43
Inline: True
```
```
In init/do_mounts_rd.c (0)
Location: include/linux/kdev_t.h:43
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:43
Inline: True
```
```
In init/do_mounts_md.c (0)
Location: include/linux/kdev_t.h:43
Inline: True
```
```
In init/initramfs.c (0)
Location: include/linux/kdev_t.h:43
Inline: True
```
```
In arch/x86/ia32/sys_ia32.c (0)
Location: include/linux/kdev_t.h:43
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/kdev_t.h:43
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/kdev_t.h:43
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kdev_t.h:43
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/kdev_t.h:43
Inline: True
```
```
In fs/fat/inode.c (ffffffff812fc18a)
Location: include/linux/kdev_t.h:43
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (0)
Location: include/linux/kdev_t.h:43
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/kdev_t.h:43
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/kdev_t.h:43
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kdev_t.h:43
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
In init/do_mounts.c (ffffffff81002ef6)
Location: include/linux/kdev_t.h:38
Inline: True
```
```
In init/do_mounts_rd.c (ffffffff81002f34)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - init/do_mounts_rd.c:create_dev
```
```
In init/do_mounts_initrd.c (ffffffff81f8302b)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff81f83646)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff81f83e01)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81078e59)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In fs/stat.c (ffffffff81238489)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff812ace6e)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/inode.c (ffffffff812c798d)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffffffff812e86e6)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffffffff81323e45)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8132fd3a)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff8134694e)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff81534525)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff815c41c7)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff8170a925)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff81002e96)
Location: include/linux/kdev_t.h:38
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:38
Inline: True
```
```
In init/do_mounts_md.c (ffffffff81fbec5b)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff81fbf52a)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107cc49)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In fs/stat.c (ffffffff8124b149)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff812c273f)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/inode.c (ffffffff812dd4f3)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffffffff812fe486)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffffffff81339cd5)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff81345a9a)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff8135cae0)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff81560c50)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff815f2917)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff8173c7f5)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff810027b3)
Location: include/linux/kdev_t.h:38
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:38
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8209edaa)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8209f65a)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107b3e9)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In kernel/events/core.c (ffffffff811a1088)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fill_ns_link_info
```
```
In fs/stat.c (ffffffff81256c39)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff812cf9cf)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff812f311c)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff812ff2bd)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffffffff813331ce)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffffffff8134e9a5)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8135a54e)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff813714d2)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff81573f2c)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff81606b38)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff817561dd)
Location: include/linux/kdev_t.h:38
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff810027e3)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_md.c (ffffffff826a4da7)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff826a565a)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81081ae9)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In kernel/events/core.c (ffffffff811b4be2)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fill_ns_link_info
```
```
In fs/stat.c (ffffffff81278e89)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff812f4151)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff813176ac)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff81323a6d)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffffffff813576e4)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffffffff81373055)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8137f25e)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff813961d2)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff815d841c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff8166ef58)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff817c83ed)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff81002f1a)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_md.c (ffffffff826cdedc)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff826cf048)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81084e39)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In kernel/bpf/offload.c (ffffffff811cc1ba)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffffffff811d515f)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In fs/stat.c (ffffffff8129f891)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff81321559)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff8134554a)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff813520e3)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffffffff8138588c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffffffff813a19a5)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff813ad81a)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff813c5129)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff81611e1d)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff816aab8a)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff81810e76)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff81002fa7)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_md.c (ffffffff82883f1f)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8288509b)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108bb09)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In kernel/bpf/offload.c (ffffffff811e02ea)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffffffff811e597f)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In fs/stat.c (ffffffff812b4871)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff81338669)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff8135d69a)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff81369b8a)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffffffff8139e3c1)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffffffff813ba785)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff813c6bca)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff813df539)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff8162eb84)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff816cc247)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8183ce76)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff810030d4)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8289af68)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289c0ed)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f90b)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In kernel/bpf/offload.c (ffffffff811f5e87)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffffffff811fd09f)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In fs/stat.c (ffffffff812d1601)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff81360d34)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff8138682a)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff81392fe4)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffffffff813c8521)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffffffff813e5065)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff813f16cb)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff8140b172)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff81662834)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff8170781b)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8187fd72)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff810030c4)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8289df4d)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289f0dd)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81090569)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In kernel/bpf/offload.c (ffffffff81202e97)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffffffff8120a34f)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In fs/stat.c (ffffffff812e3191)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff81378f94)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff8139f27a)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff813ab93e)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffffffff813e18de)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffffffff813ff105)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8140b5ab)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff81424d42)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff81684ea4)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff8172ba6b)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818b1c32)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff81004299)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8100438d)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/initramfs.c (ffffffff82cc4dac)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103a3a1)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In kernel/bpf/offload.c (ffffffff8122a491)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffffffff81230db0)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fill_ns_link_info
```
```
In fs/stat.c (ffffffff8131a101)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff813c2044)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff813eb122)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff813f7972)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In fs/ext4/super.c (ffffffff8142ea4e)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffffffff8144ca65)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8145921b)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff814743d0)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff817364c0)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff817e77ca)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff81980ac8)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:retrieve_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff82fafc80)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/initramfs.c (ffffffff82fb0771)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103aba5)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In kernel/bpf/offload.c (ffffffff81232021)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffffffff8123a9c0)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fill_ns_link_info
```
```
In fs/stat.c (ffffffff81325791)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff813d4194)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff813fd353)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff8140a9d5)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In fs/ext4/super.c (ffffffff81447849)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffffffff814690b6)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8147556c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff8148ed42)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff81752f11)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff817fc3fa)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff819850f9)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:retrieve_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff831b9ce4)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/initramfs.c (ffffffff831ba7e2)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103c5a4)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In kernel/bpf/offload.c (ffffffff812361a1)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffffffff8123f190)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fill_ns_link_info
```
```
In fs/stat.c (ffffffff8132b8d1)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff813dafd4)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff814037cb)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff81410b9e)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In fs/ext4/super.c (ffffffff8144d068)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffffffff8146e7b6)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8147afdb)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff81494777)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff81736f00)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff817e07e1)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff8196b05b)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff8329a183)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/initramfs.c (ffffffff8329acce)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff810420a4)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In kernel/bpf/offload.c (ffffffff812703f1)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffffffff81279b10)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fill_ns_link_info
```
```
In fs/stat.c (ffffffff81379041)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff8142c6d1)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff81455f8b)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff814638df)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In fs/ext4/super.c (ffffffff814a10f8)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffffffff814c504c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff814d25fb)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff814eba37)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff817b78d9)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff8186c601)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff81a1351b)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff834482a5)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/initramfs.c (ffffffff834496d7)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81049db0)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In kernel/taskstats.c (ffffffff812062cd)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats
```
```
In kernel/bpf/offload.c (ffffffff812bf4ec)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffffffff812cce53)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fill_ns_link_info
```
```
In fs/stat.c (ffffffff813f87f6)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff814a5f83)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff814d3964)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff814e25b8)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/super.c (ffffffff815289d1)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_parse_param
```
```
In fs/squashfs/super.c (ffffffff8154fe7c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8155f5db)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff8157a6d6)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff818f2dcc)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff819b5172)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff81b7bdce)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff83e62705)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/initramfs.c (ffffffff83e63193)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81054f90)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In kernel/taskstats.c (ffffffff8124e5bd)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats
```
```
In kernel/bpf/offload.c (ffffffff81322bfc)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffffffff81334fc3)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fill_ns_link_info
```
```
In fs/stat.c (ffffffff81481d66)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff8153b5c3)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff8156c5a4)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff8157b9a8)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/super.c (ffffffff815c6a47)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_parse_param
```
```
In fs/squashfs/super.c (ffffffff815f09bc)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff816018ab)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff8161fe56)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff81a4b1ed)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff81b2a572)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff81d192de)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff83682b6c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/initramfs.c (ffffffff836837b3)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81056196)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In kernel/taskstats.c (ffffffff81265970)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats
```
```
In kernel/bpf/offload.c (ffffffff81352bac)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffffffff81365d03)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fill_ns_link_info
```
```
In fs/stat.c (ffffffff814b6976)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff815738f3)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff815a4450)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff815b2da0)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/super.c (ffffffff815fe524)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_parse_param
```
```
In fs/squashfs/super.c (ffffffff816289fc)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8163979b)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff816582c6)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff81a954c6)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff81b7a958)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff81d82592)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff838b1c1c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/initramfs.c (ffffffff838b28c3)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8105d3e6)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In kernel/taskstats.c (ffffffff8127f7f0)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats
```
```
In kernel/bpf/offload.c (ffffffff8137a08c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffffffff8138ee23)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fill_ns_link_info
```
```
In fs/stat.c (ffffffff814e8ca6)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/libfs.c (ffffffff815204bd)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/libfs.c:simple_statfs
```
```
In fs/proc/array.c (ffffffff815ac298)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff815dd290)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff815ebb96)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/super.c (ffffffff81636eff)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_parse_param
```
```
In fs/squashfs/super.c (ffffffff81661bec)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/hugetlbfs/inode.c (ffffffff81667a62)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
```
```
In fs/fat/inode.c (ffffffff81672c8b)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff81690655)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_statx
  - fs/fuse/dir.c:fuse_mknod
```
```
In fs/efivarfs/super.c (ffffffff816aec10)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_statfs
```
```
In drivers/tty/tty_io.c (ffffffff81ae7ea4)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff81bce728)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff81e39c22)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffff800010085724)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_md.c (ffff800011432164)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffff80001143334c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In kernel/bpf/offload.c (ffff80001028b45c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffff800010293434)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In fs/stat.c (ffff80001038b110)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffff80001044548c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffff800010472710)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffff80001048019c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffff8000104bacf0)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffff8000104dd1d8)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffff8000104ebfa8)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffff800010508420)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffff800010852a54)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffff800010921f00)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffff800010b08a54)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (c0303ed8)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_md.c (c1502184)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (c150352c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:do_header
```
```
In kernel/bpf/offload.c (c04bac38)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (c04c2818)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fill_ns_link_info
```
```
In fs/stat.c (c0572e94)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat64
```
```
In fs/proc/array.c (c060a4c8)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (c0633af8)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap_is_valid_device
  - fs/ext4/fsmap.c:ext4_getfsmap_is_valid_device
```
```
In fs/ext4/inode.c (c06415ac)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (c067e4e0)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (c069ec80)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (c06aa25c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (c06c4424)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (c095d574)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (c0a07734)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In drivers/md/dm-ioctl.c (c0be67b0)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (c000000000011388)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_md.c (c00000000134583c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (c000000001347004)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In kernel/bpf/offload.c (c0000000003373a4)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (c000000000341954)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In fs/stat.c (c000000000482028)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (c00000000055ae8c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (c0000000005934f8)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (c0000000005a40ec)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (c0000000005f09c0)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (c000000000618ac4)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (c00000000062ac0c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (c00000000064dd08)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (c0000000008f0ea4)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (c0000000009c6cf8)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In drivers/md/dm-ioctl.c (c000000000bfa520)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffe0000b4acc)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_md.c (ffffffe000001d3a)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffe000002da8)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In kernel/bpf/offload.c (ffffffe0001bf156)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffffffe0001c5bf6)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In fs/stat.c (ffffffe00025c6fe)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffe0002db43a)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffe0002fe60c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffe000308e1c)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffffffe0003372a2)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffffffe000351c6e)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffe00035c868)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffe000374102)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffe00052f97a)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffe0005a0934)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffe0006f739e)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff810030c4)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8288bf4d)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8288d0dd)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f529)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In kernel/bpf/offload.c (ffffffff811fb4b7)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffffffff8120296f)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In fs/stat.c (ffffffff812db771)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff81371574)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff8139785a)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff813a3f1e)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffffffff813d9ebe)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffffffff813f76e5)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff81403b8b)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff8141d322)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff8164a924)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff816f184b)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff81857ab2)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff810015a4)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_md.c (ffffffff82889eca)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8288b05a)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107e039)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In kernel/bpf/offload.c (ffffffff811ee207)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffffffff811f56bf)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In fs/stat.c (ffffffff812cc3f1)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff81362002)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff813882ea)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff813949ae)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffffffff813ca93e)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffffffff813e8165)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff813f460b)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff8140dda2)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff8162ad74)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff816cb94b)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8181f0c2)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff810030c4)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8289ef4d)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff828a00dd)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f4d9)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In kernel/bpf/offload.c (ffffffff811f9287)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffffffff8120073f)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In fs/stat.c (ffffffff812d9581)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff8136f044)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff813951ba)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff813a177e)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffffffff813d733e)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffffffff813f4a65)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff81400f0b)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff814194c2)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff81678ce4)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff8171ef2b)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818a70e2)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
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
In init/do_mounts.c (ffffffff81003114)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8289ef52)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff828a00e2)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - init/initramfs.c:parse_header
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff810918b9)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In kernel/bpf/offload.c (ffffffff81207d27)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/events/core.c (ffffffff8120f7cf)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In fs/stat.c (ffffffff812ea491)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/proc/array.c (ffffffff813829d4)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/fsmap.c (ffffffff813a92da)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap
  - fs/ext4/fsmap.c:ext4_getfsmap
```
```
In fs/ext4/inode.c (ffffffff813b6391)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffffffff813ec5fe)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/squashfs/super.c (ffffffff8140a695)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff81416f7b)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/fuse/dir.c (ffffffff81430232)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_mknod
```
```
In drivers/tty/tty_io.c (ffffffff8169291f)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff8173a35b)
Location: include/linux/kdev_t.h:39
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818c3322)
Location: include/linux/kdev_t.h:39
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
</details>
</li>
</ul>

## Differences
