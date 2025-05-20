# Function: <code>dir_emit</code>

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
In fs/libfs.c (ffffffff812348c5)
Location: include/linux/fs.h:3013
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8127de68)
Location: include/linux/fs.h:3013
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
```
```
In fs/proc/generic.c (ffffffff8127f883)
Location: include/linux/fs.h:3013
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff81284fe9)
Location: include/linux/fs.h:3013
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff81289c30)
Location: include/linux/fs.h:3013
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/ext4/dir.c (ffffffff81290b01)
Location: include/linux/fs.h:3013
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff812e1cda)
Location: include/linux/fs.h:3013
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/dir.c (ffffffff812f838a)
Location: include/linux/fs.h:3013
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff81301188)
Location: include/linux/fs.h:3013
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/dir.c (ffffffff813137c0)
Location: include/linux/fs.h:3013
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
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
In fs/libfs.c (ffffffff8125cdc0)
Location: include/linux/fs.h:3162
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812abb7f)
Location: include/linux/fs.h:3162
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff812ac8e0)
Location: include/linux/fs.h:3162
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff812b20bc)
Location: include/linux/fs.h:3162
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff812b708c)
Location: include/linux/fs.h:3162
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/ext4/dir.c (ffffffff812be015)
Location: include/linux/fs.h:3162
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff81311d30)
Location: include/linux/fs.h:3162
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff81321d19)
Location: include/linux/fs.h:3162
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff8132bf7a)
Location: include/linux/fs.h:3162
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff81334e98)
Location: include/linux/fs.h:3162
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/dir.c (ffffffff81347b55)
Location: include/linux/fs.h:3162
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
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
In fs/libfs.c (ffffffff81270300)
Location: include/linux/fs.h:3132
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812c1448)
Location: include/linux/fs.h:3132
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff812c21d0)
Location: include/linux/fs.h:3132
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff812c793c)
Location: include/linux/fs.h:3132
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff812cc89c)
Location: include/linux/fs.h:3132
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/ext4/dir.c (ffffffff812d3505)
Location: include/linux/fs.h:3132
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff81327c70)
Location: include/linux/fs.h:3132
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff81337ba9)
Location: include/linux/fs.h:3132
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff81341cba)
Location: include/linux/fs.h:3132
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff8134ac68)
Location: include/linux/fs.h:3132
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/dir.c (ffffffff8135d49b)
Location: include/linux/fs.h:3132
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
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
In fs/libfs.c (ffffffff8127da93)
Location: include/linux/fs.h:3302
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812ce6cf)
Location: include/linux/fs.h:3302
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff812cf460)
Location: include/linux/fs.h:3302
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff812d4dec)
Location: include/linux/fs.h:3302
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff812d9eed)
Location: include/linux/fs.h:3302
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff812df496)
Location: include/linux/fs.h:3302
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff812e4fa7)
Location: include/linux/fs.h:3302
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff812fba53)
Location: include/linux/fs.h:3302
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff8134c8bd)
Location: include/linux/fs.h:3302
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff813563fd)
Location: include/linux/fs.h:3302
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff8135f7f8)
Location: include/linux/fs.h:3302
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/dir.c (ffffffff81371eb6)
Location: include/linux/fs.h:3302
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
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
In fs/libfs.c (ffffffff812a053b)
Location: include/linux/fs.h:3382
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812f2e9c)
Location: include/linux/fs.h:3382
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff812f3bcf)
Location: include/linux/fs.h:3382
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff812f961c)
Location: include/linux/fs.h:3382
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff812fe801)
Location: include/linux/fs.h:3382
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81303e15)
Location: include/linux/fs.h:3382
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff813099d4)
Location: include/linux/fs.h:3382
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813201a3)
Location: include/linux/fs.h:3382
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff81370f44)
Location: include/linux/fs.h:3382
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff8137b01d)
Location: include/linux/fs.h:3382
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff81384468)
Location: include/linux/fs.h:3382
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/dir.c (ffffffff81396bb6)
Location: include/linux/fs.h:3382
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
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
In fs/libfs.c (ffffffff812c7131)
Location: include/linux/fs.h:3409
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8131fda3)
Location: include/linux/fs.h:3409
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff81320c6b)
Location: include/linux/fs.h:3409
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff81326c77)
Location: include/linux/fs.h:3409
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff8132c972)
Location: include/linux/fs.h:3409
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81332c7c)
Location: include/linux/fs.h:3409
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff8133792d)
Location: include/linux/fs.h:3409
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8134e384)
Location: include/linux/fs.h:3409
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff8139f7d3)
Location: include/linux/fs.h:3409
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff813a9a29)
Location: include/linux/fs.h:3409
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff813b3297)
Location: include/linux/fs.h:3409
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/dir.c (ffffffff813c5d5e)
Location: include/linux/fs.h:3409
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
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
In fs/libfs.c (ffffffff812dc821)
Location: include/linux/fs.h:3488
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81336f03)
Location: include/linux/fs.h:3488
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff81337d63)
Location: include/linux/fs.h:3488
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff8133de37)
Location: include/linux/fs.h:3488
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff81343902)
Location: include/linux/fs.h:3488
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff8134a074)
Location: include/linux/fs.h:3488
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff8134eb7d)
Location: include/linux/fs.h:3488
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff81366520)
Location: include/linux/fs.h:3488
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff813b8563)
Location: include/linux/fs.h:3488
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff813c2809)
Location: include/linux/fs.h:3488
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff813cc777)
Location: include/linux/fs.h:3488
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (ffffffff813ea897)
Location: include/linux/fs.h:3488
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
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
In fs/libfs.c (ffffffff812faedf)
Location: include/linux/fs.h:3499
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8135f027)
Location: include/linux/fs.h:3499
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff8135fed6)
Location: include/linux/fs.h:3499
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff81365d38)
Location: include/linux/fs.h:3499
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff8136bc38)
Location: include/linux/fs.h:3499
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81371a3a)
Location: include/linux/fs.h:3499
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff8137784d)
Location: include/linux/fs.h:3499
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8138f91a)
Location: include/linux/fs.h:3499
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff813e2d38)
Location: include/linux/fs.h:3499
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff813ed079)
Location: include/linux/fs.h:3499
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff813f72bc)
Location: include/linux/fs.h:3499
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (ffffffff81416caa)
Location: include/linux/fs.h:3499
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
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
In fs/libfs.c (ffffffff8130cca3)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81377287)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff81378136)
Location: include/linux/fs.h:3561
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff8137dfc8)
Location: include/linux/fs.h:3561
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff81383e08)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81389e7a)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff8138fbcd)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813a837a)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff813fcd68)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff81407199)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff8141118c)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (ffffffff81430bdb)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
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
In fs/libfs.c (ffffffff8134663f)
Location: include/linux/fs.h:3611
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813bffda)
Location: include/linux/fs.h:3611
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff813c1091)
Location: include/linux/fs.h:3611
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff813c8718)
Location: include/linux/fs.h:3611
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff813cebb0)
Location: include/linux/fs.h:3611
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813d503e)
Location: include/linux/fs.h:3611
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff813db279)
Location: include/linux/fs.h:3611
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813f441a)
Location: include/linux/fs.h:3611
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff8144a6d5)
Location: include/linux/fs.h:3611
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff81454e14)
Location: include/linux/fs.h:3611
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff8145f19c)
Location: include/linux/fs.h:3611
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (ffffffff8147fb6b)
Location: include/linux/fs.h:3611
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_parse_cache
  - fs/fuse/readdir.c:fuse_emit
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
In fs/libfs.c (ffffffff81352b2f)
Location: include/linux/fs.h:3408
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813d1e7a)
Location: include/linux/fs.h:3408
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff813d2f81)
Location: include/linux/fs.h:3408
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff813da708)
Location: include/linux/fs.h:3408
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff813e07e0)
Location: include/linux/fs.h:3408
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813e6d5e)
Location: include/linux/fs.h:3408
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff813ecca9)
Location: include/linux/fs.h:3408
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff81406baa)
Location: include/linux/fs.h:3408
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff81466d75)
Location: include/linux/fs.h:3408
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff814712ed)
Location: include/linux/fs.h:3408
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff8147ae3c)
Location: include/linux/fs.h:3408
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (ffffffff8149b24b)
Location: include/linux/fs.h:3408
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_parse_cache
  - fs/fuse/readdir.c:fuse_emit
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
In fs/libfs.c (ffffffff81359b7f)
Location: include/linux/fs.h:3661
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813d8d5b)
Location: include/linux/fs.h:3661
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff813d9eb5)
Location: include/linux/fs.h:3661
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff813e12e7)
Location: include/linux/fs.h:3661
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff813e7310)
Location: include/linux/fs.h:3661
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813ee350)
Location: include/linux/fs.h:3661
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff813f31d9)
Location: include/linux/fs.h:3661
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8140cfb5)
Location: include/linux/fs.h:3661
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff8146c485)
Location: include/linux/fs.h:3661
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff81476a94)
Location: include/linux/fs.h:3661
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff8148087c)
Location: include/linux/fs.h:3661
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (ffffffff814a04eb)
Location: include/linux/fs.h:3661
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_parse_cache
  - fs/fuse/readdir.c:fuse_emit
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
In fs/libfs.c (ffffffff813a801f)
Location: include/linux/fs.h:3641
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8142a48b)
Location: include/linux/fs.h:3641
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff8142b5e5)
Location: include/linux/fs.h:3641
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff81432d97)
Location: include/linux/fs.h:3641
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff81438ecc)
Location: include/linux/fs.h:3641
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81440270)
Location: include/linux/fs.h:3641
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff814451f6)
Location: include/linux/fs.h:3641
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8145fdf5)
Location: include/linux/fs.h:3641
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff814c2ce5)
Location: include/linux/fs.h:3641
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff814ce1b3)
Location: include/linux/fs.h:3641
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff814d811c)
Location: include/linux/fs.h:3641
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (ffffffff814f8eab)
Location: include/linux/fs.h:3641
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
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
In fs/libfs.c (ffffffff8142be4d)
Location: include/linux/fs.h:3413
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff814a3a03)
Location: include/linux/fs.h:3413
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff814a4d0a)
Location: include/linux/fs.h:3413
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/proc_sysctl.c (ffffffff814ab5d2)
Location: include/linux/fs.h:3413
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff814b3fe0)
Location: include/linux/fs.h:3413
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff814ba996)
Location: include/linux/fs.h:3413
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff814c1212)
Location: include/linux/fs.h:3413
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff814de562)
Location: include/linux/fs.h:3413
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff8154d824)
Location: include/linux/fs.h:3413
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff8155a9e8)
Location: include/linux/fs.h:3413
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff815657e1)
Location: include/linux/fs.h:3413
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (ffffffff81589523)
Location: include/linux/fs.h:3413
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
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
In fs/libfs.c (ffffffff814b952d)
Location: include/linux/fs.h:3563
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81538d23)
Location: include/linux/fs.h:3563
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff8153a23a)
Location: include/linux/fs.h:3563
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/proc_sysctl.c (ffffffff81541652)
Location: include/linux/fs.h:3563
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff8154adcf)
Location: include/linux/fs.h:3563
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81552266)
Location: include/linux/fs.h:3563
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff81559492)
Location: include/linux/fs.h:3563
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff815775cf)
Location: include/linux/fs.h:3563
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff815ed7f7)
Location: include/linux/fs.h:3563
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff815fb735)
Location: include/linux/fs.h:3563
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff81608a34)
Location: include/linux/fs.h:3563
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (ffffffff8162fb31)
Location: include/linux/fs.h:3563
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
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
In fs/libfs.c (ffffffff814ee4f7)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81570f66)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff815724e0)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/proc_sysctl.c (ffffffff81579bb2)
Location: include/linux/fs.h:3178
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff81582a24)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81589fb9)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff81591295)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff815aeac0)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff816257ba)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff816336be)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff81640894)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (ffffffff81667d62)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
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
In fs/libfs.c (ffffffff815224b3)
Location: include/linux/fs.h:3475
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff815a9906)
Location: include/linux/fs.h:3475
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff815aae90)
Location: include/linux/fs.h:3475
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/proc_sysctl.c (ffffffff815b22d2)
Location: include/linux/fs.h:3475
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff815bb654)
Location: include/linux/fs.h:3475
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff815c2c8c)
Location: include/linux/fs.h:3475
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff815c9fd5)
Location: include/linux/fs.h:3475
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff815e7880)
Location: include/linux/fs.h:3475
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff8165e8f9)
Location: include/linux/fs.h:3475
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff8166cb8e)
Location: include/linux/fs.h:3475
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff81679e44)
Location: include/linux/fs.h:3475
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (ffffffff816a207a)
Location: include/linux/fs.h:3475
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
```
```
In fs/tracefs/event_inode.c (ffffffff816ab3e4)
Location: include/linux/fs.h:3475
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_iterate
  - fs/tracefs/event_inode.c:eventfs_iterate
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
In fs/libfs.c (ffff8000103c1f24)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffff800010442a9c)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffff800010444138)
Location: include/linux/fs.h:3561
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffff80001044b44c)
Location: include/linux/fs.h:3561
Inline: True
```
```
In fs/kernfs/dir.c (ffff800010452aac)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffff80001045baf4)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffff800010462314)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffff80001047bc44)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffff8000104dad24)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffff8000104e5fb8)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffff8000104f23e8)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (ffff8000105156b8)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
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
In fs/libfs.c (c059dd18)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (c06081ec)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (c06092a8)
Location: include/linux/fs.h:3561
Inline: True
```
```
In fs/proc/proc_sysctl.c (c060fccc)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
```
```
In fs/kernfs/dir.c (c061532c)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (c061bf0c)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (c06228ac)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (c063d614)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (c069c36c)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (c06a5990)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (c06afca4)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (c06d0508)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
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
In fs/libfs.c (c0000000004bffd4)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (c000000000558270)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (c0000000005598f8)
Location: include/linux/fs.h:3561
Inline: True
```
```
In fs/proc/proc_sysctl.c (c000000000562418)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
```
```
In fs/kernfs/dir.c (c00000000056b134)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (c000000000575858)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (c00000000057ed54)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (c00000000059f238)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (c000000000615a70)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (c000000000624154)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (c000000000631f90)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (c00000000065dfc4)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
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
In fs/libfs.c (ffffffe000281c9e)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffe0002d95b4)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffe0002da310)
Location: include/linux/fs.h:3561
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffe0002e08de)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
```
```
In fs/kernfs/dir.c (ffffffe0002e54b4)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffe0002ebfea)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffe0002f1134)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffe000305e84)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffe00034fb84)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffe000358ce2)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffe000361b64)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (ffffffe00037f016)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
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
In fs/libfs.c (ffffffff81305283)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8136f867)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff81370716)
Location: include/linux/fs.h:3561
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff813765a8)
Location: include/linux/fs.h:3561
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff8137c3e8)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff8138245a)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff813881ad)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813a095a)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff813f5348)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff813ff779)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff8140976c)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (ffffffff814291bb)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
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
In fs/libfs.c (ffffffff812f5ea3)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813602f7)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff813611a6)
Location: include/linux/fs.h:3561
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff81367078)
Location: include/linux/fs.h:3561
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff8136ceb8)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81372eea)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff81378c3d)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813913ea)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff813e5dc8)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff813f01f9)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff813fa1ec)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (ffffffff81419c3b)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
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
In fs/libfs.c (ffffffff81303073)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8136d337)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff8136e1e6)
Location: include/linux/fs.h:3561
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff81374078)
Location: include/linux/fs.h:3561
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff81379eb8)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff8137ff2a)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff81385b0d)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8139e1ba)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff813f26c8)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff813fcaf9)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff81406aec)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (ffffffff8142535b)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
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
In fs/libfs.c (ffffffff813140e4)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81380c5e)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/generic.c (ffffffff81381b11)
Location: include/linux/fs.h:3561
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff81387a88)
Location: include/linux/fs.h:3561
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff8138d7fe)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813937ff)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/dir.c (ffffffff813997fd)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813b272a)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/squashfs/dir.c (ffffffff814082b8)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/fat/dir.c (ffffffff81412719)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/ecryptfs/file.c (ffffffff8141c7ac)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_filldir
```
```
In fs/fuse/readdir.c (ffffffff8143c225)
Location: include/linux/fs.h:3561
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
</details>
</li>
</ul>

## Differences
