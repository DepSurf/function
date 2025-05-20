# Function: <code>timespec_to_timespec64</code>

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
In kernel/signal.c (0)
Location: include/linux/time64.h:50
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/time64.h:50
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/time64.h:50
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/time64.h:50
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/time64.h:50
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
In kernel/time/time.c (0)
Location: include/linux/time64.h:50
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/time64.h:50
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/time64.h:50
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/time64.h:50
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/time64.h:50
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/time64.h:50
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/time64.h:50
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/time64.h:50
Inline: True
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
In kernel/time/time.c (0)
Location: include/linux/time64.h:51
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/time64.h:51
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/time64.h:51
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/time64.h:51
Inline: True
```
```
In kernel/compat.c (0)
Location: include/linux/time64.h:51
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/time64.h:51
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/time64.h:51
Inline: True
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
In kernel/time/time.c (0)
Location: include/linux/time64.h:51
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/time64.h:51
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/time64.h:51
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/time64.h:51
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: include/linux/time32.h:24
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
In kernel/time/timekeeping.c (ffffffff81118929)
Location: include/linux/time32.h:24
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_clock64
```
```
In fs/ext4/inode.c (0)
Location: include/linux/time32.h:24
Inline: True
```
```
In fs/fat/inode.c (ffffffff813af986)
Location: include/linux/time32.h:24
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813b1ee1)
Location: include/linux/time32.h:24
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/time32.h:24
Inline: True
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
