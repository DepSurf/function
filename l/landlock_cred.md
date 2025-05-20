# Function: <code>landlock_cred</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff8153771b)
Location: security/landlock/cred.h:23
Inline: True
Inline callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
```
In security/landlock/cred.c (ffffffff815383e5)
Location: security/landlock/cred.h:23
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_free
  - security/landlock/cred.c:hook_cred_prepare
  - security/landlock/cred.c:hook_cred_prepare
```
```
In security/landlock/ptrace.c (ffffffff81538526)
Location: security/landlock/cred.h:23
Inline: True
Inline callers:
  - security/landlock/ptrace.c:hook_ptrace_traceme
  - security/landlock/ptrace.c:hook_ptrace_traceme
  - security/landlock/ptrace.c:hook_ptrace_access_check
  - security/landlock/ptrace.c:task_is_scoped
  - security/landlock/ptrace.c:task_is_scoped
```
```
In security/landlock/fs.c (ffffffff8153889e)
Location: security/landlock/cred.h:23
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_link
  - security/landlock/fs.c:hook_sb_umount
  - security/landlock/fs.c:hook_sb_mount
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
In security/landlock/syscalls.c (ffffffff81595ef8)
Location: security/landlock/cred.h:23
Inline: True
Inline callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
```
In security/landlock/cred.c (ffffffff81596bd5)
Location: security/landlock/cred.h:23
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_free
  - security/landlock/cred.c:hook_cred_prepare
  - security/landlock/cred.c:hook_cred_prepare
```
```
In security/landlock/ptrace.c (ffffffff81596d16)
Location: security/landlock/cred.h:23
Inline: True
Inline callers:
  - security/landlock/ptrace.c:hook_ptrace_traceme
  - security/landlock/ptrace.c:hook_ptrace_traceme
  - security/landlock/ptrace.c:hook_ptrace_access_check
  - security/landlock/ptrace.c:task_is_scoped
  - security/landlock/ptrace.c:task_is_scoped
```
```
In security/landlock/fs.c (ffffffff8159734e)
Location: security/landlock/cred.h:23
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_link
  - security/landlock/fs.c:hook_sb_umount
  - security/landlock/fs.c:hook_sb_mount
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
In security/landlock/syscalls.c (ffffffff8163824f)
Location: security/landlock/cred.h:24
Inline: True
Inline callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
```
In security/landlock/cred.c (ffffffff81638fe5)
Location: security/landlock/cred.h:24
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_free
  - security/landlock/cred.c:hook_cred_prepare
  - security/landlock/cred.c:hook_cred_prepare
```
```
In security/landlock/ptrace.c (ffffffff816390ce)
Location: security/landlock/cred.h:24
Inline: True
Inline callers:
  - security/landlock/ptrace.c:task_ptrace
  - security/landlock/ptrace.c:task_ptrace
  - security/landlock/ptrace.c:task_ptrace
  - security/landlock/ptrace.c:task_ptrace
```
```
In security/landlock/fs.c (ffffffff8163ae8e)
Location: security/landlock/cred.h:24
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
  - security/landlock/fs.c:hook_sb_umount
  - security/landlock/fs.c:hook_sb_mount
  - security/landlock/fs.c:current_check_refer_path
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
In security/landlock/syscalls.c (ffffffff816ef3af)
Location: security/landlock/cred.h:24
Inline: True
Inline callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
```
In security/landlock/cred.c (ffffffff816f0525)
Location: security/landlock/cred.h:24
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_free
  - security/landlock/cred.c:hook_cred_prepare
  - security/landlock/cred.c:hook_cred_prepare
```
```
In security/landlock/ptrace.c (ffffffff816f062e)
Location: security/landlock/cred.h:24
Inline: True
Inline callers:
  - security/landlock/ptrace.c:task_ptrace
  - security/landlock/ptrace.c:task_ptrace
  - security/landlock/ptrace.c:task_ptrace
  - security/landlock/ptrace.c:task_ptrace
```
```
In security/landlock/fs.c (ffffffff816f2660)
Location: security/landlock/cred.h:24
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_path_truncate
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
  - security/landlock/fs.c:hook_sb_umount
  - security/landlock/fs.c:hook_sb_mount
  - security/landlock/fs.c:current_check_refer_path
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
In security/landlock/syscalls.c (ffffffff8172985f)
Location: security/landlock/cred.h:24
Inline: True
Inline callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
```
In security/landlock/cred.c (ffffffff8172a9c5)
Location: security/landlock/cred.h:24
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_free
  - security/landlock/cred.c:hook_cred_prepare
  - security/landlock/cred.c:hook_cred_prepare
```
```
In security/landlock/ptrace.c (ffffffff8172aace)
Location: security/landlock/cred.h:24
Inline: True
Inline callers:
  - security/landlock/ptrace.c:task_ptrace
  - security/landlock/ptrace.c:task_ptrace
  - security/landlock/ptrace.c:task_ptrace
  - security/landlock/ptrace.c:task_ptrace
```
```
In security/landlock/fs.c (ffffffff8172caa0)
Location: security/landlock/cred.h:24
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_path_truncate
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
  - security/landlock/fs.c:hook_sb_umount
  - security/landlock/fs.c:hook_sb_mount
  - security/landlock/fs.c:current_check_refer_path
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
In security/landlock/syscalls.c (ffffffff8176adff)
Location: security/landlock/cred.h:24
Inline: True
Inline callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
```
In security/landlock/cred.c (ffffffff8176c3a5)
Location: security/landlock/cred.h:24
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_free
  - security/landlock/cred.c:hook_cred_prepare
  - security/landlock/cred.c:hook_cred_prepare
```
```
In security/landlock/ptrace.c (ffffffff8176c4ae)
Location: security/landlock/cred.h:24
Inline: True
Inline callers:
  - security/landlock/ptrace.c:task_ptrace
  - security/landlock/ptrace.c:task_ptrace
  - security/landlock/ptrace.c:task_ptrace
  - security/landlock/ptrace.c:task_ptrace
```
```
In security/landlock/fs.c (ffffffff8176c62f)
Location: security/landlock/cred.h:24
Inline: True
Inline callers:
  - security/landlock/fs.c:get_current_fs_domain
```
```
In security/landlock/net.c (ffffffff8176e1f6)
Location: security/landlock/cred.h:24
Inline: True
Inline callers:
  - security/landlock/net.c:current_check_access_socket
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
