# Function: <code>locks_inode_context</code>

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
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150e1fc)
Location: include/linux/fs.h:1194
Inline: True
Inline callers:
  - fs/locks.c:show_fd_locks
  - fs/locks.c:vfs_inode_has_locks
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:generic_setlease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_free_lock_context
  - fs/locks.c:locks_get_lock_context
  - fs/locks.c:locks_get_lock_context
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff815459cf)
Location: include/linux/filelock.h:185
Inline: True
Inline callers:
  - fs/locks.c:show_fd_locks
  - fs/locks.c:vfs_inode_has_locks
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:generic_setlease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_free_lock_context
  - fs/locks.c:locks_get_lock_context
  - fs/locks.c:locks_get_lock_context
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8157af2f)
Location: include/linux/filelock.h:185
Inline: True
Inline callers:
  - fs/locks.c:show_fd_locks
  - fs/locks.c:vfs_inode_has_locks
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:generic_setlease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_free_lock_context
  - fs/locks.c:locks_get_lock_context
  - fs/locks.c:locks_get_lock_context
```
</details>
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
