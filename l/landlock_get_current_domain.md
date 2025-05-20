# Function: <code>landlock_get_current_domain</code>

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
In security/landlock/ptrace.c (ffffffff81538548)
Location: security/landlock/cred.h:29
Inline: True
Inline callers:
  - security/landlock/ptrace.c:hook_ptrace_traceme
  - security/landlock/ptrace.c:hook_ptrace_access_check
```
```
In security/landlock/fs.c (ffffffff81538895)
Location: security/landlock/cred.h:29
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
In security/landlock/ptrace.c (ffffffff81596d38)
Location: security/landlock/cred.h:29
Inline: True
Inline callers:
  - security/landlock/ptrace.c:hook_ptrace_traceme
  - security/landlock/ptrace.c:hook_ptrace_access_check
```
```
In security/landlock/fs.c (ffffffff81597345)
Location: security/landlock/cred.h:29
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
In security/landlock/ptrace.c (ffffffff816390fe)
Location: security/landlock/cred.h:29
Inline: True
Inline callers:
  - security/landlock/ptrace.c:task_ptrace
```
```
In security/landlock/fs.c (ffffffff8163ae85)
Location: security/landlock/cred.h:29
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
In security/landlock/ptrace.c (ffffffff816f065e)
Location: security/landlock/cred.h:29
Inline: True
Inline callers:
  - security/landlock/ptrace.c:task_ptrace
```
```
In security/landlock/fs.c (ffffffff816f2660)
Location: security/landlock/cred.h:29
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
In security/landlock/ptrace.c (ffffffff8172aafe)
Location: security/landlock/cred.h:29
Inline: True
Inline callers:
  - security/landlock/ptrace.c:task_ptrace
```
```
In security/landlock/fs.c (ffffffff8172caa0)
Location: security/landlock/cred.h:29
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
In security/landlock/ptrace.c (ffffffff8176c4e1)
Location: security/landlock/cred.h:29
Inline: True
Inline callers:
  - security/landlock/ptrace.c:task_ptrace
```
```
In security/landlock/fs.c (ffffffff8176c625)
Location: security/landlock/cred.h:29
Inline: True
Inline callers:
  - security/landlock/fs.c:get_current_fs_domain
```
```
In security/landlock/net.c (ffffffff8176e1ed)
Location: security/landlock/cred.h:29
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
