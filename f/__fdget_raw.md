# Function: <code>__fdget_raw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8122abc0)
Location: fs/file.c:767
Inline: False
Direct callers:
  - fs/open.c:SyS_fchdir
  - fs/stat.c:vfs_fstat
  - fs/namei.c:path_init
  - fs/fcntl.c:SyS_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffffffff8122abc0-ffffffff8122abd2: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81253300)
Location: fs/file.c:768
Inline: False
Direct callers:
  - fs/open.c:SyS_fchdir
  - fs/stat.c:vfs_fstat
  - fs/namei.c:path_init
  - fs/fcntl.c:SyS_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffffffff81253300-ffffffff81253312: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81266550)
Location: fs/file.c:768
Inline: False
Direct callers:
  - fs/open.c:SyS_fchdir
  - fs/stat.c:vfs_fstat
  - fs/namei.c:path_init
  - fs/fcntl.c:SyS_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffffffff81266550-ffffffff81266562: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81273d30)
Location: fs/file.c:754
Inline: False
Direct callers:
  - fs/open.c:SyS_fchdir
  - fs/stat.c:vfs_statx_fd
  - fs/namei.c:path_init
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffffffff81273d30-ffffffff81273d42: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81296600)
Location: fs/file.c:757
Inline: False
Direct callers:
  - fs/open.c:SyS_fchdir
  - fs/stat.c:vfs_statx_fd
  - fs/namei.c:path_init
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffffffff81296600-ffffffff81296612: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bc9c0)
Location: fs/file.c:753
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/stat.c:vfs_statx_fd
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffffffff812bc9c0-ffffffff812bc9d2: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d1c80)
Location: fs/file.c:783
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/stat.c:vfs_statx_fd
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffffffff812d1c80-ffffffff812d1c92: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812eecb0)
Location: fs/file.c:789
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/stat.c:vfs_statx_fd
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffffffff812eecb0-ffffffff812eecc2: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81300770)
Location: fs/file.c:789
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/stat.c:vfs_statx_fd
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffffffff81300770-ffffffff81300782: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81339990)
Location: fs/file.c:814
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/stat.c:vfs_statx_fd
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffffffff81339990-ffffffff813399a2: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813456c0)
Location: fs/file.c:950
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/stat.c:vfs_fstat
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffffffff813456c0-ffffffff813456d2: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134ba60)
Location: fs/file.c:962
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/stat.c:vfs_fstat
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
  - fs/statfs.c:fd_statfs
  - security/landlock/syscalls.c:get_path_from_fd
```
**Symbols:**

```
ffffffff8134ba60-ffffffff8134ba72: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813998a0)
Location: fs/file.c:1022
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/stat.c:vfs_fstat
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
  - fs/statfs.c:fd_statfs
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - security/landlock/syscalls.c:get_path_from_fd
```
**Symbols:**

```
ffffffff813998a0-ffffffff813998b2: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141c270)
Location: fs/file.c:1024
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/stat.c:vfs_fstat
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
  - fs/statfs.c:fd_statfs
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - security/landlock/syscalls.c:get_path_from_fd
```
**Symbols:**

```
ffffffff8141c270-ffffffff8141c28a: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a8340)
Location: fs/file.c:1034
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/stat.c:vfs_fstat
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
  - fs/statfs.c:fd_statfs
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - security/landlock/syscalls.c:get_path_from_fd
```
**Symbols:**

```
ffffffff814a8340-ffffffff814a835a: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dd320)
Location: fs/file.c:1035
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_v1v2_get_from_fd
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/stat.c:vfs_fstat
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
  - fs/statfs.c:fd_statfs
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - security/landlock/syscalls.c:get_path_from_fd
```
**Symbols:**

```
ffffffff814dd320-ffffffff814dd33a: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8150fca0)
Location: fs/file.c:1164
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_v1v2_get_from_fd
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/stat.c:vfs_fstat
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
  - fs/statfs.c:fd_statfs
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - security/landlock/syscalls.c:add_rule_path_beneath
```
**Symbols:**

```
ffffffff8150fca0-ffffffff8150fd6a: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b2580)
Location: fs/file.c:789
Inline: False
Direct callers:
  - fs/open.c:__arm64_sys_fchdir
  - fs/stat.c:vfs_statx_fd
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__arm64_sys_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffff8000103b2580-ffff8000103b25b0: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c05918d0)
Location: fs/file.c:789
Inline: False
Direct callers:
  - fs/open.c:__se_sys_fchdir
  - fs/stat.c:vfs_statx_fd
  - fs/namei.c:path_init
  - fs/fcntl.c:__se_sys_fcntl64
  - fs/fcntl.c:__se_sys_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
c05918d0-c05918f0: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ae410)
Location: fs/file.c:789
Inline: False
Direct callers:
  - fs/open.c:__se_sys_fchdir
  - fs/stat.c:vfs_statx_fd
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__se_sys_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
c0000000004ae410-c0000000004ae428: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe0002765d0)
Location: fs/file.c:789
Inline: False
Direct callers:
  - fs/open.c:__se_sys_fchdir
  - fs/stat.c:vfs_statx_fd
  - fs/namei.c:path_init
  - fs/fcntl.c:__se_sys_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffffffe0002765d0-ffffffe0002765fc: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f8d50)
Location: fs/file.c:789
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/stat.c:vfs_statx_fd
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffffffff812f8d50-ffffffff812f8d62: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e9970)
Location: fs/file.c:789
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/stat.c:vfs_statx_fd
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffffffff812e9970-ffffffff812e9982: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f6b60)
Location: fs/file.c:789
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/stat.c:vfs_statx_fd
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffffffff812f6b60-ffffffff812f6b72: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int __fdget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81307db0)
Location: fs/file.c:789
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/stat.c:vfs_statx_fd
  - fs/namei.c:path_init
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
  - fs/statfs.c:fd_statfs
```
**Symbols:**

```
ffffffff81307db0-ffffffff81307dc2: __fdget_raw (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
