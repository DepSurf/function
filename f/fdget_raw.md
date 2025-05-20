# Function: <code>fdget_raw</code>

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
In fs/open.c (ffffffff8120acd0)
Location: include/linux/file.h:59
Inline: True
Inline callers:
  - fs/open.c:SyS_fchdir
```
```
In fs/stat.c (ffffffff81211535)
Location: include/linux/file.h:59
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff81218fd0)
Location: include/linux/file.h:59
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff8121ee3f)
Location: include/linux/file.h:59
Inline: True
Inline callers:
  - fs/fcntl.c:SyS_fcntl
```
```
In fs/statfs.c (ffffffff81241c85)
Location: include/linux/file.h:59
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (ffffffff81230980)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/open.c:SyS_fchdir
```
```
In fs/stat.c (ffffffff81237fe5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff8123dffd)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812467cf)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fcntl.c:SyS_fcntl
```
```
In fs/statfs.c (ffffffff81269fd5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (ffffffff81242f30)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/open.c:SyS_fchdir
```
```
In fs/stat.c (ffffffff8124aca5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff81250ddd)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812597bf)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fcntl.c:SyS_fcntl
```
```
In fs/statfs.c (ffffffff8127cf85)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (ffffffff8124e690)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/open.c:SyS_fchdir
```
```
In fs/stat.c (ffffffff81256787)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/namei.c (ffffffff8125c530)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff8126639a)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
```
```
In fs/statfs.c (ffffffff8128a935)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (ffffffff81270610)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/open.c:SyS_fchdir
```
```
In fs/stat.c (ffffffff812789d7)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/namei.c (ffffffff8127e999)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff81288c5a)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
```
```
In fs/statfs.c (ffffffff812ad655)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (ffffffff812949f5)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff8129f313)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/namei.c (ffffffff812a7791)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812aee4d)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/statfs.c (ffffffff812d5385)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (ffffffff812a94a5)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff812b42f3)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/namei.c (ffffffff812bc83a)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812c3f3e)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/statfs.c (ffffffff812ea6a5)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (ffffffff812c5c05)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff812d1062)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/namei.c (ffffffff812d9318)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812e093e)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/statfs.c (ffffffff81309115)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (ffffffff812d7615)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff812e2bf2)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/namei.c (ffffffff812eae28)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812f23ee)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/statfs.c (ffffffff8131c185)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (ffffffff8130d7c5)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff8131aec6)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/namei.c (ffffffff81322b69)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff8132a60e)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/statfs.c (ffffffff81355e95)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (ffffffff81319aa5)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff81326615)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff8132e13d)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff81335b7e)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/statfs.c (ffffffff813627d5)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (ffffffff81320635)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff8132c725)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff81334771)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff8133bd0e)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/statfs.c (ffffffff81369275)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In security/landlock/syscalls.c (ffffffff81537185)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
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
In fs/open.c (ffffffff8136d165)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff81379e95)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff813820bc)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff8138998e)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/statfs.c (ffffffff813b7f75)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/quota/quota.c (ffffffff8141ea79)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
```
```
In security/landlock/syscalls.c (ffffffff815957a5)
Location: include/linux/file.h:68
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
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
In fs/open.c (ffffffff813ebd55)
Location: include/linux/file.h:66
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff813f8e15)
Location: include/linux/file.h:66
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff81403daa)
Location: include/linux/file.h:66
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff8140a9fd)
Location: include/linux/file.h:66
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/statfs.c (ffffffff8143d7b5)
Location: include/linux/file.h:66
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/quota/quota.c (ffffffff814967f9)
Location: include/linux/file.h:66
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
```
```
In security/landlock/syscalls.c (ffffffff81637a45)
Location: include/linux/file.h:66
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
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
In fs/open.c (ffffffff814741f5)
Location: include/linux/file.h:66
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff81482445)
Location: include/linux/file.h:66
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff8148e216)
Location: include/linux/file.h:66
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff8149526d)
Location: include/linux/file.h:66
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/statfs.c (ffffffff814cc085)
Location: include/linux/file.h:66
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/quota/quota.c (ffffffff8152a779)
Location: include/linux/file.h:66
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
```
```
In security/landlock/syscalls.c (ffffffff816eee15)
Location: include/linux/file.h:66
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
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
In kernel/cgroup/cgroup.c (ffffffff812264c5)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_v1v2_get_from_fd
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff81336105)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
```
```
In fs/open.c (ffffffff814a8ba5)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff814b7055)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff814c3959)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff814ca2bd)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/statfs.c (ffffffff815022c5)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/quota/quota.c (ffffffff81562b59)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
```
```
In security/landlock/syscalls.c (ffffffff817292a5)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
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
In kernel/cgroup/cgroup.c (ffffffff8123e155)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_v1v2_get_from_fd
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff8135a765)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
```
```
In fs/open.c (ffffffff814d9c05)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff814e93d5)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff814f5e29)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff814fcb8d)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/statfs.c (ffffffff81536f15)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/quota/quota.c (ffffffff81599249)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
```
```
In security/landlock/syscalls.c (ffffffff8176a67f)
Location: include/linux/file.h:67
Inline: True
Inline callers:
  - security/landlock/syscalls.c:add_rule_path_beneath
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
In fs/open.c (ffff80001037c9d4)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/open.c:__arm64_sys_fchdir
```
```
In fs/stat.c (ffff80001038a5d8)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/namei.c (ffff8000103944cc)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffff80001039c5dc)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__arm64_sys_fcntl
```
```
In fs/statfs.c (ffff8000103d3b30)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (c0569040)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/open.c:__se_sys_fchdir
```
```
In fs/stat.c (c05727b4)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/namei.c (c0578a74)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (c05822d0)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/fcntl.c:__se_sys_fcntl64
  - fs/fcntl.c:__se_sys_fcntl
```
```
In fs/statfs.c (c05adeac)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (c000000000471c74)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/open.c:__se_sys_fchdir
```
```
In fs/stat.c (c000000000481824)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/namei.c (c00000000048a5e8)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (c00000000049737c)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__se_sys_fcntl
```
```
In fs/statfs.c (c0000000004d6598)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (ffffffe000254372)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/open.c:__se_sys_fchdir
```
```
In fs/stat.c (ffffffe00025c51c)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/namei.c (ffffffe00026304e)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffe000268a3a)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/fcntl.c:__se_sys_fcntl
```
```
In fs/statfs.c (ffffffe00028e390)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (ffffffff812cfbf5)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff812db1d2)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/namei.c (ffffffff812e3408)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812ea9ce)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/statfs.c (ffffffff81314765)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (ffffffff812c0875)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff812cbe52)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/namei.c (ffffffff812d4048)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812db60e)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/statfs.c (ffffffff81305375)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (ffffffff812cda05)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff812d8fe2)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/namei.c (ffffffff812e1218)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812e87de)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/statfs.c (ffffffff81312555)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
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
In fs/open.c (ffffffff812de815)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/stat.c (ffffffff812e9ef2)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/namei.c (ffffffff812f0241)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812f97ae)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/statfs.c (ffffffff81323d95)
Location: include/linux/file.h:65
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
</details>
</li>
</ul>

## Differences
