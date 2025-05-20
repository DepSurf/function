# Function: <code>huge_encode_dev</code>

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
In arch/x86/ia32/sys_ia32.c (0)
Location: include/linux/kdev_t.h:57
Inline: True
```
```
In fs/fat/inode.c (ffffffff812fc18a)
Location: include/linux/kdev_t.h:57
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff8156e8ce)
Location: include/linux/kdev_t.h:57
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/kdev_t.h:57
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
In arch/x86/ia32/sys_ia32.c (ffffffff81078e59)
Location: include/linux/kdev_t.h:52
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In fs/squashfs/super.c (ffffffff81323e45)
Location: include/linux/kdev_t.h:52
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8132fd3a)
Location: include/linux/kdev_t.h:52
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff815c41c7)
Location: include/linux/kdev_t.h:52
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff8170a915)
Location: include/linux/kdev_t.h:52
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
In arch/x86/ia32/sys_ia32.c (ffffffff8107cc49)
Location: include/linux/kdev_t.h:52
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In fs/squashfs/super.c (ffffffff81339cd5)
Location: include/linux/kdev_t.h:52
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff81345a9a)
Location: include/linux/kdev_t.h:52
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff815f2917)
Location: include/linux/kdev_t.h:52
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff8173c7e5)
Location: include/linux/kdev_t.h:52
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
In arch/x86/ia32/sys_ia32.c (ffffffff8107b3e9)
Location: include/linux/kdev_t.h:52
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In fs/squashfs/super.c (ffffffff8134e9a5)
Location: include/linux/kdev_t.h:52
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8135a54e)
Location: include/linux/kdev_t.h:52
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff81606b38)
Location: include/linux/kdev_t.h:52
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff817561cd)
Location: include/linux/kdev_t.h:52
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
In arch/x86/ia32/sys_ia32.c (ffffffff81081ae9)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In fs/squashfs/super.c (ffffffff81373055)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8137f25e)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff8166ef58)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff817c83dd)
Location: include/linux/kdev_t.h:53
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
In arch/x86/ia32/sys_ia32.c (ffffffff81084e39)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In fs/squashfs/super.c (ffffffff813a19a5)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff813ad81a)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff816aab8a)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff81810e76)
Location: include/linux/kdev_t.h:53
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
In arch/x86/ia32/sys_ia32.c (ffffffff8108bb09)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In fs/squashfs/super.c (ffffffff813ba785)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff813c6bca)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff816cc247)
Location: include/linux/kdev_t.h:53
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8183ce76)
Location: include/linux/kdev_t.h:53
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
In arch/x86/ia32/sys_ia32.c (ffffffff8108f90b)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In fs/squashfs/super.c (ffffffff813e5065)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff813f16cb)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff8170781b)
Location: include/linux/kdev_t.h:53
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8187fd72)
Location: include/linux/kdev_t.h:53
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
In arch/x86/ia32/sys_ia32.c (ffffffff81090569)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In fs/squashfs/super.c (ffffffff813ff105)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8140b5ab)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff8172ba6b)
Location: include/linux/kdev_t.h:53
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818b1c32)
Location: include/linux/kdev_t.h:53
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
In arch/x86/kernel/sys_ia32.c (ffffffff8103a3a1)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In fs/squashfs/super.c (ffffffff8144ca65)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8145921b)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff817e77ca)
Location: include/linux/kdev_t.h:53
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff81980ac8)
Location: include/linux/kdev_t.h:53
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
In arch/x86/kernel/sys_ia32.c (ffffffff8103aba5)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In fs/squashfs/super.c (ffffffff814690b6)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8147556c)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff817fc3fa)
Location: include/linux/kdev_t.h:53
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff819850f9)
Location: include/linux/kdev_t.h:53
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
In arch/x86/kernel/sys_ia32.c (ffffffff8103c5a4)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In fs/squashfs/super.c (ffffffff8146e7b6)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8147afdb)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff817e07e1)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff8196b05b)
Location: include/linux/kdev_t.h:53
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
In arch/x86/kernel/sys_ia32.c (ffffffff810420a4)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In fs/squashfs/super.c (ffffffff814c504c)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff814d25fb)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff8186c601)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff81a1351b)
Location: include/linux/kdev_t.h:53
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
In arch/x86/kernel/sys_ia32.c (ffffffff81049db0)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In kernel/taskstats.c (ffffffff812062cd)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats
```
```
In fs/squashfs/super.c (ffffffff8154fe7c)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8155f5db)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff819b5172)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff81b7bdce)
Location: include/linux/kdev_t.h:53
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
In arch/x86/kernel/sys_ia32.c (ffffffff81054f90)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In kernel/taskstats.c (ffffffff8124e5bd)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats
```
```
In fs/squashfs/super.c (ffffffff815f09bc)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff816018ab)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff81b2a572)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff81d192de)
Location: include/linux/kdev_t.h:53
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
In arch/x86/kernel/sys_ia32.c (ffffffff81056196)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In kernel/taskstats.c (ffffffff81265970)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats
```
```
In fs/squashfs/super.c (ffffffff816289fc)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8163979b)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff81b7a958)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff81d82592)
Location: include/linux/kdev_t.h:53
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
In arch/x86/kernel/sys_ia32.c (ffffffff8105d3e6)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In kernel/taskstats.c (ffffffff8127f7f0)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats
```
```
In fs/libfs.c (ffffffff815204bd)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/libfs.c:simple_statfs
```
```
In fs/squashfs/super.c (ffffffff81661bec)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/hugetlbfs/inode.c (ffffffff81667a62)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
```
```
In fs/fat/inode.c (ffffffff81672c8b)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/efivarfs/super.c (ffffffff816aec10)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_statfs
```
```
In drivers/block/loop.c (ffffffff81bce728)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/md/dm-ioctl.c (ffffffff81e39c22)
Location: include/linux/kdev_t.h:53
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
In fs/stat.c (0)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat64
```
```
In fs/squashfs/super.c (ffff8000104dd1d8)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffff8000104ebfa8)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffff800010921f00)
Location: include/linux/kdev_t.h:53
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffff800010b08a54)
Location: include/linux/kdev_t.h:53
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
In fs/stat.c (c0572e94)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat64
```
```
In fs/squashfs/super.c (c069ec80)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (c06aa25c)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (c0a07734)
Location: include/linux/kdev_t.h:53
Inline: True
```
```
In drivers/md/dm-ioctl.c (c0be67b0)
Location: include/linux/kdev_t.h:53
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
In fs/stat.c (c000000000482028)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat64
```
```
In fs/squashfs/super.c (c000000000618ac4)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (c00000000062ac0c)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (c0000000009c6cf8)
Location: include/linux/kdev_t.h:53
Inline: True
```
```
In drivers/md/dm-ioctl.c (c000000000bfa520)
Location: include/linux/kdev_t.h:53
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
In fs/squashfs/super.c (ffffffe000351c6e)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffe00035c868)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffe0005a0934)
Location: include/linux/kdev_t.h:53
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffe0006f739e)
Location: include/linux/kdev_t.h:53
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
In arch/x86/ia32/sys_ia32.c (ffffffff8108f529)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In fs/squashfs/super.c (ffffffff813f76e5)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff81403b8b)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff816f184b)
Location: include/linux/kdev_t.h:53
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff81857ab2)
Location: include/linux/kdev_t.h:53
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
In arch/x86/ia32/sys_ia32.c (ffffffff8107e039)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In fs/squashfs/super.c (ffffffff813e8165)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff813f460b)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff816cb94b)
Location: include/linux/kdev_t.h:53
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8181f0c2)
Location: include/linux/kdev_t.h:53
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
In arch/x86/ia32/sys_ia32.c (ffffffff8108f4d9)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In fs/squashfs/super.c (ffffffff813f4a65)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff81400f0b)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff8171ef2b)
Location: include/linux/kdev_t.h:53
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818a70e2)
Location: include/linux/kdev_t.h:53
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
In arch/x86/ia32/sys_ia32.c (ffffffff810918b9)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In fs/squashfs/super.c (ffffffff8140a695)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff81416f7b)
Location: include/linux/kdev_t.h:53
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In drivers/block/loop.c (ffffffff8173a35b)
Location: include/linux/kdev_t.h:53
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818c3322)
Location: include/linux/kdev_t.h:53
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
