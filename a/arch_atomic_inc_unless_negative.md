# Function: <code>arch_atomic_inc_unless_negative</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
Location: include/linux/atomic-arch-fallback.h:1136
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff8129c1fe)
Location: include/linux/atomic-arch-fallback.h:1136
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff8130e299)
Location: include/linux/atomic-arch-fallback.h:1136
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff813213e7)
Location: include/linux/atomic-arch-fallback.h:1136
Inline: True
Inline callers:
  - fs/namei.c:handle_truncate
```
```
In fs/proc/inode.c (ffffffff813b95ed)
Location: include/linux/atomic-arch-fallback.h:1136
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
Location: include/linux/atomic-arch-fallback.h:1136
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
Location: include/linux/atomic-arch-fallback.h:1206
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff812a75a8)
Location: include/linux/atomic-arch-fallback.h:1206
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff8131a37c)
Location: include/linux/atomic-arch-fallback.h:1206
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff8132c987)
Location: include/linux/atomic-arch-fallback.h:1206
Inline: True
Inline callers:
  - fs/namei.c:handle_truncate
```
```
In fs/proc/inode.c (ffffffff813caffd)
Location: include/linux/atomic-arch-fallback.h:1206
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
Location: include/linux/atomic-arch-fallback.h:1206
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
Location: include/linux/atomic-arch-fallback.h:1206
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff812ad2df)
Location: include/linux/atomic-arch-fallback.h:1206
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff8132045c)
Location: include/linux/atomic-arch-fallback.h:1206
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff813367a6)
Location: include/linux/atomic-arch-fallback.h:1206
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/proc/inode.c (ffffffff813d203a)
Location: include/linux/atomic-arch-fallback.h:1206
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
Location: include/linux/atomic-arch-fallback.h:1206
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
Location: include/linux/atomic/atomic-arch-fallback.h:1206
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff812ee9a1)
Location: include/linux/atomic/atomic-arch-fallback.h:1206
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff8136da15)
Location: include/linux/atomic/atomic-arch-fallback.h:1206
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff81384186)
Location: include/linux/atomic/atomic-arch-fallback.h:1206
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/proc/inode.c (ffffffff8142356a)
Location: include/linux/atomic/atomic-arch-fallback.h:1206
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
Location: include/linux/atomic/atomic-arch-fallback.h:1206
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
Location: include/linux/atomic/atomic-arch-fallback.h:1290
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff81351d73)
Location: include/linux/atomic/atomic-arch-fallback.h:1290
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff813ebb4c)
Location: include/linux/atomic/atomic-arch-fallback.h:1290
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff814052d5)
Location: include/linux/atomic/atomic-arch-fallback.h:1290
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/proc/inode.c (ffffffff8149c18a)
Location: include/linux/atomic/atomic-arch-fallback.h:1290
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
Location: include/linux/atomic/atomic-arch-fallback.h:1290
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
Location: include/linux/atomic/atomic-arch-fallback.h:1290
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff813cb98b)
Location: include/linux/atomic/atomic-arch-fallback.h:1290
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/open.c (ffffffff81473fbe)
Location: include/linux/atomic/atomic-arch-fallback.h:1290
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff8148f722)
Location: include/linux/atomic/atomic-arch-fallback.h:1290
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/proc/inode.c (ffffffff81530aaa)
Location: include/linux/atomic/atomic-arch-fallback.h:1290
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
Location: include/linux/atomic/atomic-arch-fallback.h:1290
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_get_active
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
