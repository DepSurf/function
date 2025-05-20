# Function: <code>ktime_get_real_ts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f0d56)
Location: include/linux/timekeeping.h:69
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_clock_realtime_get
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
In kernel/time/posix-timers.c (ffffffff810f7d76)
Location: include/linux/timekeeping.h:85
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_clock_realtime_get
```
```
In fs/kernfs/inode.c (ffffffff812b6123)
Location: include/linux/timekeeping.h:85
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff812b7570)
Location: include/linux/timekeeping.h:85
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/kernfs/dir.c:kernfs_add_one
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
In kernel/time/posix-timers.c (ffffffff81105716)
Location: include/linux/timekeeping.h:85
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_clock_realtime_get
```
```
In fs/kernfs/inode.c (ffffffff812cb9b3)
Location: include/linux/timekeeping.h:85
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff812ccd79)
Location: include/linux/timekeeping.h:85
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/kernfs/dir.c:kernfs_add_one
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
In fs/kernfs/inode.c (ffffffff812d8dfa)
Location: include/linux/timekeeping.h:74
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff812dac86)
Location: include/linux/timekeeping.h:74
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_add_one
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
In fs/kernfs/inode.c (ffffffff812fd65a)
Location: include/linux/timekeeping32.h:46
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff812ff566)
Location: include/linux/timekeeping32.h:46
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_add_one
```
</details>
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
