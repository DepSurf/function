# Function: <code>files_lookup_fd_raw</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81344b28)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:__fget_files
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81375d0a)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff813af8e4)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff813d5bcc)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/file.c (ffffffff8134b0dc)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:__fget_files
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8137c69f)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff813b6b6d)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff813dcbdc)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/file.c (ffffffff81398eb8)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
```
```
In fs/notify/dnotify/dnotify.c (ffffffff813c9528)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff81406866)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff8142e2b8)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/file.c (ffffffff8141b789)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget_light
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81450edf)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff8147b37e)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff814a79e0)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/file.c (ffffffff814a7969)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget_light
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
```
```
In fs/notify/dnotify/dnotify.c (ffffffff814df94f)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff8150defe)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff8153d3e0)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/file.c (ffffffff814dc889)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget_light
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
```
```
In fs/notify/dnotify/dnotify.c (ffffffff815161da)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff815456d2)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff815756c0)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/file.c (ffffffff8150e915)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:__fdget_pos
  - fs/file.c:__fdget_raw
```
```
In fs/locks.c (ffffffff8157ac32)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff815ae020)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In io_uring/openclose.c (ffffffff81819632)
Location: include/linux/fdtable.h:83
Inline: True
Inline callers:
  - io_uring/openclose.c:io_close
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
