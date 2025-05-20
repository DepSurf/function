# Function: <code>atomic_inc_unless_negative</code>

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
In kernel/events/core.c (ffffffff8117ecdb)
Location: include/linux/atomic.h:511
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff811c73cb)
Location: include/linux/atomic.h:511
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff81209904)
Location: include/linux/atomic.h:511
Inline: True
Inline callers:
  - fs/open.c:vfs_truncate
  - fs/open.c:do_dentry_open
```
```
In fs/namei.c (ffffffff8121ab6c)
Location: include/linux/atomic.h:511
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/block_dev.c (ffffffff81249425)
Location: include/linux/atomic.h:511
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/proc/inode.c (ffffffff8127926a)
Location: include/linux/atomic.h:511
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_follow_link
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_reg_open
```
```
In fs/kernfs/dir.c (ffffffff8128a5a4)
Location: include/linux/atomic.h:511
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
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
In kernel/events/core.c (ffffffff811907c4)
Location: include/linux/atomic.h:580
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff811e397b)
Location: include/linux/atomic.h:580
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff8122fde6)
Location: include/linux/atomic.h:580
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812423b9)
Location: include/linux/atomic.h:580
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/block_dev.c (ffffffff81271ff5)
Location: include/linux/atomic.h:580
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/proc/inode.c (ffffffff812a5fca)
Location: include/linux/atomic.h:580
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff812b7a9b)
Location: include/linux/atomic.h:580
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
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
In kernel/events/core.c (ffffffff8119f692)
Location: include/linux/atomic.h:580
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff811f395b)
Location: include/linux/atomic.h:580
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff81242386)
Location: include/linux/atomic.h:580
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff8125528e)
Location: include/linux/atomic.h:580
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/block_dev.c (ffffffff81285595)
Location: include/linux/atomic.h:580
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/proc/inode.c (ffffffff812bb8ea)
Location: include/linux/atomic.h:580
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff812cd234)
Location: include/linux/atomic.h:580
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
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
In kernel/events/core.c (ffffffff811a60cd)
Location: include/linux/atomic.h:603
Inline: True
```
```
In mm/mmap.c (ffffffff811fe984)
Location: include/linux/atomic.h:603
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff8124d8c8)
Location: include/linux/atomic.h:603
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812612d6)
Location: include/linux/atomic.h:603
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/block_dev.c (ffffffff812930a6)
Location: include/linux/atomic.h:603
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/proc/inode.c (ffffffff812c8e2a)
Location: include/linux/atomic.h:603
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff812da4ca)
Location: include/linux/atomic.h:603
Inline: True
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
In kernel/events/core.c (ffffffff811b9cc3)
Location: include/linux/atomic.h:607
Inline: True
```
```
In mm/mmap.c (ffffffff81216f3a)
Location: include/linux/atomic.h:607
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff8126f92e)
Location: include/linux/atomic.h:607
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff81283a09)
Location: include/linux/atomic.h:607
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/block_dev.c (ffffffff812b5ea7)
Location: include/linux/atomic.h:607
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/proc/inode.c (ffffffff812ed69a)
Location: include/linux/atomic.h:607
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff812fed2a)
Location: include/linux/atomic.h:607
Inline: True
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
In kernel/events/core.c (0)
Location: include/linux/atomic.h:607
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff81237e39)
Location: include/linux/atomic.h:607
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (0)
Location: include/linux/atomic.h:607
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812aab92)
Location: include/linux/atomic.h:607
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/block_dev.c (ffffffff812ddb02)
Location: include/linux/atomic.h:607
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/proc/inode.c (0)
Location: include/linux/atomic.h:607
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/atomic.h:607
Inline: True
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
In kernel/events/core.c (ffffffff811e97c9)
Location: include/linux/atomic.h:674
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff8124b854)
Location: include/linux/atomic.h:674
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff812aa047)
Location: include/linux/atomic.h:674
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812bf967)
Location: include/linux/atomic.h:674
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/block_dev.c (ffffffff812f30e4)
Location: include/linux/atomic.h:674
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/proc/inode.c (ffffffff81331ab9)
Location: include/linux/atomic.h:674
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff81344077)
Location: include/linux/atomic.h:674
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
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
In kernel/events/core.c (0)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff8125dca0)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff812c6803)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812dcaf8)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/block_dev.c (ffffffff81314b59)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/proc/inode.c (ffffffff8135989a)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff8136c2cd)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
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
In kernel/events/core.c (0)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff8126c470)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff812d8207)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812ee647)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/proc/inode.c (ffffffff81371aea)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff8138447d)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
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
In kernel/events/core.c (0)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff8129c1fe)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff8130e299)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff813213e7)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - fs/namei.c:handle_truncate
```
```
In fs/proc/inode.c (ffffffff813b95ed)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff813cee94)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_get_active
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
In kernel/events/core.c (0)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff812a75a8)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff8131a37c)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff8132c987)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - fs/namei.c:handle_truncate
```
```
In fs/proc/inode.c (ffffffff813caffd)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff813e0ac4)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_get_active
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
In kernel/events/core.c (0)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff812ad2df)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff8132045c)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff813367a6)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/proc/inode.c (ffffffff813d203a)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff813e75f4)
Location: include/asm-generic/atomic-instrumented.h:806
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_get_active
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
In kernel/events/core.c (0)
Location: include/linux/atomic/atomic-instrumented.h:582
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff812ee9a1)
Location: include/linux/atomic/atomic-instrumented.h:582
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff8136da15)
Location: include/linux/atomic/atomic-instrumented.h:582
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff81384186)
Location: include/linux/atomic/atomic-instrumented.h:582
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/proc/inode.c (ffffffff8142356a)
Location: include/linux/atomic/atomic-instrumented.h:582
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff81439304)
Location: include/linux/atomic/atomic-instrumented.h:582
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_get_active
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
In kernel/events/core.c (0)
Location: include/linux/atomic/atomic-instrumented.h:620
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff81351d73)
Location: include/linux/atomic/atomic-instrumented.h:620
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff813ebb4c)
Location: include/linux/atomic/atomic-instrumented.h:620
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff814052d5)
Location: include/linux/atomic/atomic-instrumented.h:620
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/proc/inode.c (ffffffff8149c18a)
Location: include/linux/atomic/atomic-instrumented.h:620
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff814b432e)
Location: include/linux/atomic/atomic-instrumented.h:620
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_get_active
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
In kernel/events/core.c (0)
Location: include/linux/atomic/atomic-instrumented.h:620
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff813cb98b)
Location: include/linux/atomic/atomic-instrumented.h:620
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff81473fbe)
Location: include/linux/atomic/atomic-instrumented.h:620
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff8148f722)
Location: include/linux/atomic/atomic-instrumented.h:620
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/proc/inode.c (ffffffff81530aaa)
Location: include/linux/atomic/atomic-instrumented.h:620
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff8154b1be)
Location: include/linux/atomic/atomic-instrumented.h:620
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_get_active
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
In kernel/events/core.c (0)
Location: include/linux/atomic/atomic-instrumented.h:1540
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff8140025f)
Location: include/linux/atomic/atomic-instrumented.h:1540
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff814a8866)
Location: include/linux/atomic/atomic-instrumented.h:1540
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff814c1f0e)
Location: include/linux/atomic/atomic-instrumented.h:1540
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/proc/inode.c (ffffffff81568c2a)
Location: include/linux/atomic/atomic-instrumented.h:1540
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff81582e0e)
Location: include/linux/atomic/atomic-instrumented.h:1540
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_get_active
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
In kernel/events/core.c (0)
Location: include/linux/atomic/atomic-instrumented.h:1540
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff8142cbe8)
Location: include/linux/atomic/atomic-instrumented.h:1540
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff814d9961)
Location: include/linux/atomic/atomic-instrumented.h:1540
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff814f43ce)
Location: include/linux/atomic/atomic-instrumented.h:1540
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/proc/inode.c (ffffffff815a124a)
Location: include/linux/atomic/atomic-instrumented.h:1540
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff815bba3e)
Location: include/linux/atomic/atomic-instrumented.h:1540
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_get_active
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
In kernel/events/core.c (0)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffff8000103036ac)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffff80001037dd38)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffff8000103982b4)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/proc/inode.c (ffff80001043b7e8)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffff8000104530c8)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
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
In kernel/events/core.c (0)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (c0521f64)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (c0567854)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (c057e8a4)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/proc/inode.c (c0601cd0)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (c0615ce0)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
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
In kernel/events/core.c (c000000000346f5c)
Location: include/linux/atomic-fallback.h:1134
Inline: True
```
```
In mm/mmap.c (c0000000003d02f8)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (c000000000472a18)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (c0000000004921c0)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/proc/inode.c (c00000000054f484)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (c00000000056c35c)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
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
In kernel/events/core.c (ffffffe0001ca112)
Location: include/linux/atomic-fallback.h:1134
Inline: True
```
```
In mm/mmap.c (ffffffe0002101f6)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffe0002538e6)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffe000265ed4)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/proc/inode.c (ffffffe0002d3bba)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffe0002e5792)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_get_active
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
In kernel/events/core.c (0)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff81264ac0)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff812d07e7)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812e6c27)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/proc/inode.c (ffffffff8136a0ca)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff8137ca5d)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
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
In kernel/events/core.c (0)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff81256ee0)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff812c1467)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812d7867)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/proc/inode.c (ffffffff8135ab5a)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff8136d52d)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
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
In kernel/events/core.c (0)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff81262860)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff812ce5f7)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812e4a37)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/proc/inode.c (ffffffff81367b9a)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff8137a52d)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
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
In kernel/events/core.c (0)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff81272220)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff812df407)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812f59b7)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/proc/inode.c (ffffffff8137b1ea)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff8138e01d)
Location: include/linux/atomic-fallback.h:1134
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
```
</details>
</li>
</ul>

## Differences
