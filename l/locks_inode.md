# Function: <code>locks_inode</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f3d42)
Location: include/linux/fs.h:1027
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff8124240f)
Location: include/linux/fs.h:1027
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/namei.c (ffffffff812552a2)
Location: include/linux/fs.h:1027
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/locks.c (ffffffff812a41ea)
Location: include/linux/fs.h:1027
Inline: True
Inline callers:
  - fs/locks.c:show_fd_locks
  - fs/locks.c:lock_get_status
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In fs/fuse/file.c (ffffffff81361bdb)
Location: include/linux/fs.h:1027
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
In mm/mmap.c (ffffffff811fed1f)
Location: include/linux/fs.h:1049
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff8124d7d0)
Location: include/linux/fs.h:1049
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/namei.c (ffffffff812612ea)
Location: include/linux/fs.h:1049
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/locks.c (ffffffff812b2dfa)
Location: include/linux/fs.h:1049
Inline: True
Inline callers:
  - fs/locks.c:show_fd_locks
  - fs/locks.c:lock_get_status
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
```
```
In fs/fuse/file.c (ffffffff813765ab)
Location: include/linux/fs.h:1049
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
In mm/mmap.c (ffffffff81217362)
Location: include/linux/fs.h:1052
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff8126f830)
Location: include/linux/fs.h:1052
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/namei.c (ffffffff81283a1d)
Location: include/linux/fs.h:1052
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/locks.c (ffffffff812d68fa)
Location: include/linux/fs.h:1052
Inline: True
Inline callers:
  - fs/locks.c:show_fd_locks
  - fs/locks.c:lock_get_status
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_check_ctx_file_list
```
```
In fs/fuse/file.c (ffffffff8139b34b)
Location: include/linux/fs.h:1052
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
In mm/mmap.c (ffffffff81238427)
Location: include/linux/fs.h:1059
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff812951f9)
Location: include/linux/fs.h:1059
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/namei.c (ffffffff812aabae)
Location: include/linux/fs.h:1059
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/locks.c (ffffffff81301573)
Location: include/linux/fs.h:1059
Inline: True
Inline callers:
  - fs/locks.c:show_fd_locks
  - fs/locks.c:lock_get_status
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_check_ctx_file_list
```
```
In fs/fuse/file.c (ffffffff813ca274)
Location: include/linux/fs.h:1059
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
