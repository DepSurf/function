# Function: <code>new_decode_dev</code>

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
In init/do_mounts.c (ffffffff8100255e)
Location: include/linux/kdev_t.h:50
Inline: True
Inline callers:
  - init/do_mounts.c:name_to_dev_t
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:50
Inline: True
```
```
In init/do_mounts_md.c (ffffffff81f5b769)
Location: include/linux/kdev_t.h:50
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In kernel/power/user.c (ffffffff810d5d06)
Location: include/linux/kdev_t.h:50
Inline: True
```
```
In fs/namei.c (ffffffff8121d114)
Location: include/linux/kdev_t.h:50
Inline: True
Inline callers:
  - fs/namei.c:SyS_mknod
```
```
In fs/statfs.c (0)
Location: include/linux/kdev_t.h:50
Inline: True
```
```
In fs/compat.c (0)
Location: include/linux/kdev_t.h:50
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kdev_t.h:50
Inline: True
```
```
In fs/ext4/super.c (ffffffff813227c1)
Location: include/linux/kdev_t.h:50
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
```
```
In fs/fuse/inode.c (0)
Location: include/linux/kdev_t.h:50
Inline: True
```
```
In security/tomoyo/file.c (ffffffff8136f8ea)
Location: include/linux/kdev_t.h:50
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff81699e91)
Location: include/linux/kdev_t.h:50
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kdev_t.h:50
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
In init/do_mounts.c (ffffffff810025bc)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - init/do_mounts.c:name_to_dev_t
```
```
In init/do_mounts_initrd.c (ffffffff81f8311e)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff81f8370e)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In kernel/power/user.c (ffffffff810dab86)
Location: include/linux/kdev_t.h:45
Inline: True
```
```
In fs/namei.c (ffffffff81244911)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/namei.c:SyS_mknod
```
```
In fs/statfs.c (ffffffff8126a181)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/statfs.c:SYSC_ustat
```
```
In fs/compat.c (ffffffff8128fe71)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/compat.c:C_SYSC_ustat
```
```
In fs/ext4/inode.c (ffffffff812c85ac)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff812ecc45)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/squashfs/inode.c (ffffffff813235ea)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff81350aa6)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In security/tomoyo/file.c (ffffffff813a5c35)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff816faf99)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff81708af9)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
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
In init/do_mounts.c (ffffffff810025dc)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - init/do_mounts.c:name_to_dev_t
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:45
Inline: True
```
```
In init/do_mounts_md.c (ffffffff81fbed23)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In kernel/power/user.c (ffffffff810e1656)
Location: include/linux/kdev_t.h:45
Inline: True
```
```
In fs/namei.c (ffffffff81257881)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/namei.c:SyS_mknod
```
```
In fs/statfs.c (ffffffff8127d131)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/statfs.c:SYSC_ustat
```
```
In fs/compat.c (ffffffff812a4eb1)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/compat.c:C_SYSC_ustat
```
```
In fs/ext4/inode.c (ffffffff812de12f)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff81302a30)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/squashfs/inode.c (ffffffff8133947a)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff81366406)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In security/tomoyo/file.c (ffffffff813bc7b5)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff8172cb08)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff8173a9c9)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
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
In init/do_mounts.c (ffffffff810026ba)
Location: include/linux/kdev_t.h:45
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:45
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8209ee5b)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In kernel/power/user.c (ffffffff810e055c)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In fs/namei.c (ffffffff81263a00)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/namei.c:SyS_mknod
```
```
In fs/statfs.c (ffffffff8128ac81)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/statfs.c:C_SYSC_ustat
  - fs/statfs.c:SYSC_ustat
```
```
In fs/ext4/inode.c (ffffffff81302138)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff813383ab)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff8134e1da)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff8137aac6)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In security/tomoyo/file.c (ffffffff813d30f4)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff81745541)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff817543dc)
Location: include/linux/kdev_t.h:45
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
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
In init/do_mounts.c (ffffffff810026ea)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_md.c (ffffffff826a4e58)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In kernel/power/user.c (ffffffff810e880c)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In fs/namei.c (ffffffff81285f40)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/namei.c:SyS_mknod
```
```
In fs/statfs.c (ffffffff812ad281)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:C_SYSC_ustat
  - fs/statfs.c:SYSC_ustat
```
```
In fs/ext4/inode.c (ffffffff81326b1a)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff8135cdf7)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff8137288f)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff8139f966)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In security/tomoyo/file.c (ffffffff813f9604)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff817b7711)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff817c658c)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
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
In init/do_mounts.c (ffffffff81002e02)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_md.c (ffffffff826cdf97)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In kernel/power/user.c (ffffffff810f0abe)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In fs/namei.c (ffffffff812ad43d)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In fs/statfs.c (ffffffff812d4ead)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/ext4/inode.c (ffffffff81354eff)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff813864d2)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff813a11ee)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff813cecff)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In security/tomoyo/file.c (ffffffff8142a61a)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff817fe7c5)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff8180fe10)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
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
In init/do_mounts.c (ffffffff81002ed8)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_md.c (ffffffff82883fda)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In kernel/power/user.c (ffffffff810fc14e)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In fs/namei.c (ffffffff812c253d)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In fs/statfs.c (ffffffff812ea27d)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/ext4/inode.c (ffffffff8136d264)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff8139efd2)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff813ba06c)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff813e816f)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In security/tomoyo/file.c (ffffffff81446eea)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff8182a965)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff8183be10)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
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
In init/do_mounts.c (ffffffff81003003)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8289b020)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In kernel/power/user.c (ffffffff81104933)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In fs/namei.c (ffffffff812dec60)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In fs/statfs.c (ffffffff81308cf0)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/ext4/inode.c (ffffffff81396854)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813c9648)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff813e4394)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff8141423b)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In security/tomoyo/file.c (ffffffff81474b12)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff8186cf2e)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff8187dec0)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
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
In init/do_mounts.c (ffffffff81002ff3)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8289e005)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In kernel/power/user.c (ffffffff81110ce3)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In fs/namei.c (ffffffff812f0770)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In fs/statfs.c (ffffffff8131bd60)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/ext4/inode.c (ffffffff813af2b1)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813e2948)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff813fe3e4)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff8142e2db)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In security/tomoyo/file.c (ffffffff8148e8b2)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff8189ed1e)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff818afeb0)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
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
In init/do_mounts.c (ffffffff81004108)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_md.c (ffffffff82cc455c)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In kernel/power/user.c (ffffffff8111bad9)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_set_swap_area
```
```
In fs/namei.c (ffffffff8132785d)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In fs/statfs.c (ffffffff813558dc)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/ext4/inode.c (ffffffff813fb300)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff8142f88d)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff8144bd63)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff8147df2c)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In security/tomoyo/file.c (ffffffff814e5b42)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff8196f066)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff819801b0)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
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
In init/do_mounts.c (ffffffff81003d31)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - init/do_mounts.c:devt_from_devnum
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In kernel/power/user.c (ffffffff8111644e)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_set_swap_area
```
```
In fs/namei.c (ffffffff81332e2d)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In fs/statfs.c (ffffffff813621fe)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/init.c (ffffffff82fede07)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/init.c:init_mknod
```
```
In fs/ext4/inode.c (ffffffff8140d9b6)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff814485bd)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff81468453)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff81497283)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init_inode
```
```
In security/tomoyo/file.c (ffffffff81502f42)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff81976004)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-autodetect.c (ffffffff83013003)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md-autodetect.c:md_setup_drive
```
```
In drivers/md/dm-ioctl.c (ffffffff81984679)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
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
In init/do_mounts.c (ffffffff81003f89)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In kernel/power/user.c (ffffffff81116ce4)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In fs/namei.c (ffffffff81338eab)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In fs/statfs.c (ffffffff81368ccf)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/init.c (ffffffff831f861b)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/init.c:init_mknod
```
```
In fs/ext4/inode.c (ffffffff81413b51)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff8144de0d)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff8146db11)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff8149c3f3)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init_inode
```
```
In security/tomoyo/file.c (ffffffff81509b12)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff8195a1ce)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-autodetect.c (ffffffff8321e132)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md-autodetect.c:md_setup_drive
```
```
In drivers/md/dm-ioctl.c (ffffffff8196a177)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
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
In init/do_mounts.c (ffffffff81003fd9)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In kernel/power/user.c (ffffffff811370a4)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In fs/namei.c (ffffffff81386740)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/namei.c:do_mknodat
```
```
In fs/statfs.c (ffffffff813b79cf)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/init.c (ffffffff832df594)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/init.c:init_mknod
```
```
In fs/ext4/inode.c (ffffffff81466e6f)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff814a1e9d)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff814c43a1)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff814f3f43)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init_inode
```
```
In security/tomoyo/file.c (ffffffff81566f34)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff819ff99e)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-autodetect.c (ffffffff833074a5)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md-autodetect.c:md_setup_drive
```
```
In drivers/md/dm-ioctl.c (ffffffff81a12617)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
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
In init/do_mounts.c (ffffffff81001ce9)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In kernel/power/user.c (ffffffff81159518)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In fs/namei.c (ffffffff814073a7)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/namei.c:do_mknodat
```
```
In fs/statfs.c (ffffffff8143d138)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/init.c (ffffffff83495214)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/init.c:init_mknod
```
```
In fs/ext4/inode.c (ffffffff814e6aa3)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff8152911c)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff8154f239)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff81583910)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init_inode
```
```
In security/tomoyo/file.c (ffffffff81602a75)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff81b66cfd)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-autodetect.c (ffffffff834c0946)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md-autodetect.c:md_setup_drive
```
```
In drivers/md/dm-ioctl.c (ffffffff81b7ae4b)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
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
In init/do_mounts.c (ffffffff810023c9)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In kernel/power/user.c (ffffffff8118b748)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In fs/namei.c (ffffffff814918b8)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/namei.c:do_mknodat
```
```
In fs/statfs.c (ffffffff814cb908)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/init.c (ffffffff83ec9c54)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/init.c:init_mknod
```
```
In fs/ext4/inode.c (ffffffff81580283)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff815c724c)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff815efc1b)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff816298f9)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init_inode
```
```
In security/tomoyo/file.c (ffffffff816b3be5)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff81d0256c)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-autodetect.c (ffffffff83eff8e1)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md-autodetect.c:md_setup_drive
```
```
In drivers/md/dm-ioctl.c (ffffffff81d16b8e)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
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
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff811950e9)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
```
```
In kernel/power/user.c (ffffffff8119cfdb)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In fs/namei.c (ffffffff814c5e73)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/namei.c:do_mknodat
```
```
In fs/statfs.c (ffffffff81501b48)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/init.c (ffffffff836eec94)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/init.c:init_mknod
```
```
In fs/ext4/inode.c (ffffffff815b7824)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff815fefc2)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff81627e83)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff81661b09)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init_inode
```
```
In security/tomoyo/file.c (ffffffff816ec5a5)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In block/early-lookup.c (ffffffff836fe29b)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - block/early-lookup.c:early_lookup_bdev
```
```
In drivers/md/md.c (ffffffff81d6b66d)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-autodetect.c (ffffffff83725780)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md-autodetect.c:md_setup_drive
```
```
In drivers/md/dm-ioctl.c (ffffffff81d7fdc9)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
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
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff811a3ac9)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
```
```
In kernel/power/user.c (ffffffff811ac12b)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In fs/namei.c (ffffffff814f8755)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/namei.c:do_mknodat
```
```
In fs/statfs.c (ffffffff81536798)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/init.c (ffffffff83921cf5)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/init.c:init_mknod
```
```
In fs/ext4/inode.c (ffffffff815f05d5)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff81637bcf)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff81661001)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff8169ba5c)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init_inode
```
```
In security/tomoyo/file.c (ffffffff81729375)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In block/early-lookup.c (ffffffff8393197b)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - block/early-lookup.c:early_lookup_bdev
```
```
In drivers/md/md.c (ffffffff81e21636)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-autodetect.c (ffffffff839595f0)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md-autodetect.c:md_setup_drive
```
```
In drivers/md/dm-ioctl.c (ffffffff81e37419)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
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
In init/do_mounts.c (ffff800010085628)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_md.c (ffff80001143220c)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In fs/namei.c (ffff800010399f2c)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In fs/statfs.c (ffff8000103d322c)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/ext4/inode.c (ffff800010483c4c)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffff8000104bbd98)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffff8000104dc500)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffff8000105129a0)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In security/tomoyo/file.c (ffff80001058223c)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffff800010af37f8)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffff800010b06f0c)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
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
In init/do_mounts.c (c0303dc4)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_md.c (c1502238)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In kernel/power/user.c (c03c3b50)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In fs/namei.c (c0580460)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In fs/statfs.c (c05ad984)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/ext4/inode.c (c0645198)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (c067f4e4)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (c069e024)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (c06cdab0)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In security/tomoyo/file.c (c0734160)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (c0bd4e28)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (c0be5a10)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
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
In init/do_mounts.c (c0000000000112b8)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_md.c (c0000000013458f4)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In fs/namei.c (c000000000494a0c)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In fs/statfs.c (c0000000004d6064)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/ext4/inode.c (c0000000005a8ca4)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (c0000000005f7120)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (c000000000617c64)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (c00000000065a714)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In security/tomoyo/file.c (c0000000006f0aa8)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (c000000000be0ac0)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (c000000000bf7c78)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
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
In init/do_mounts.c (ffffffe0000b4a68)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_md.c (ffffffe000001ca6)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In fs/namei.c (ffffffe000267626)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In fs/statfs.c (ffffffe00028e11a)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/ext4/inode.c (ffffffe00030c276)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffe00033bdce)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffe0003511e6)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffe00037c9d4)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In security/tomoyo/file.c (ffffffe0003d277a)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffe0006e70ae)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffe0006f5862)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
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
In init/do_mounts.c (ffffffff81002ff3)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8288c005)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In kernel/power/user.c (ffffffff811092ad)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In fs/namei.c (ffffffff812e8d50)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In fs/statfs.c (ffffffff81314340)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/ext4/inode.c (ffffffff813a7891)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813daf28)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff813f69c4)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff814268bb)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In security/tomoyo/file.c (ffffffff81486e92)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff81844b9e)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff81855d30)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
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
In init/do_mounts.c (ffffffff810014d3)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_md.c (ffffffff82889f82)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In kernel/power/user.c (ffffffff810fa1a3)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In fs/namei.c (ffffffff812d9990)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In fs/statfs.c (ffffffff81304f50)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/ext4/inode.c (ffffffff81398321)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813cb9a8)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff813e7444)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff8141733b)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In security/tomoyo/file.c (ffffffff814778b2)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff8180c1fe)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff8181d340)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
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
In init/do_mounts.c (ffffffff81002ff3)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8289f005)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In kernel/power/user.c (ffffffff811071b3)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In fs/namei.c (ffffffff812e6b60)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In fs/statfs.c (ffffffff81312130)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/ext4/inode.c (ffffffff813a50f1)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813d83c8)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff813f3d44)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff81422a5b)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In security/tomoyo/file.c (ffffffff81482f32)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff818941ce)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff818a5360)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
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
In init/do_mounts.c (ffffffff81003043)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8289f00a)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
```
```
In kernel/power/user.c (ffffffff81112573)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
```
```
In fs/namei.c (ffffffff812f7ae0)
Location: include/linux/kdev_t.h:46
Inline: True
```
```
In fs/statfs.c (ffffffff81323970)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
```
```
In fs/ext4/inode.c (ffffffff813b9821)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813ed668)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_getfsmap_class
  - fs/ext4/super.c:trace_event_raw_event_ext4_fsmap_class
```
```
In fs/squashfs/inode.c (ffffffff81409974)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fuse/inode.c (ffffffff8143988b)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In security/tomoyo/file.c (ffffffff8149aac2)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_mkdev_perm
```
```
In drivers/md/md.c (ffffffff818afdf0)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff818c15a0)
Location: include/linux/kdev_t.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
</details>
</li>
</ul>

## Differences
