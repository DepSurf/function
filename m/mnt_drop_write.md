# Function: <code>mnt_drop_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122b840)
Location: fs/namespace.c:476
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - kernel/acct.c:SyS_acct
  - fs/open.c:vfs_truncate
  - fs/open.c:chmod_common
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_lchown
  - fs/namei.c:done_path_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_create
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_unlinkat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:utimes_common
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_unlink
```
**Symbols:**

```
ffffffff8122b840-ffffffff8122b861: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81253fed)
Location: fs/namespace.c:476
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - kernel/acct.c:SyS_acct
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:utimes_common
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff81253fb0-ffffffff81253fd1: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8126732d)
Location: fs/namespace.c:475
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - kernel/acct.c:SyS_acct
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:utimes_common
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff812672f0-ffffffff81267311: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81274b8d)
Location: fs/namespace.c:476
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - kernel/acct.c:SyS_acct
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:utimes_common
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81274b50-ffffffff81274b71: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812994bd)
Location: fs/namespace.c:530
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file_path
Direct callers:
  - kernel/acct.c:SyS_acct
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:utimes_common
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81297480-ffffffff812974a1: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bd670)
Location: fs/namespace.c:530
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812bd670-ffffffff812bd691: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d2960)
Location: fs/namespace.c:447
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812d2960-ffffffff812d2981: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812efb30)
Location: fs/namespace.c:444
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812efb30-ffffffff812efb51: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81301600)
Location: fs/namespace.c:444
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81301600-ffffffff81301621: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133a6e0)
Location: fs/namespace.c:444
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:filename_create
  - fs/namei.c:do_tmpfile
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:utimes_common
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff8133a6e0-ffffffff8133a701: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81346a10)
Location: fs/namespace.c:444
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:filename_create
  - fs/namei.c:do_tmpfile
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:vfs_utimes
  - fs/init.c:init_chown
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81346a10-ffffffff81346a58: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134cc60)
Location: fs/namespace.c:450
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:vfs_utimes
  - fs/init.c:init_chown
  - fs/quota/quota.c:__ia32_sys_quotactl_path
  - fs/quota/quota.c:__x64_sys_quotactl_path
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff8134cc60-ffffffff8134cca8: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139abd0)
Location: fs/namespace.c:452
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:vfs_utimes
  - fs/init.c:init_chown
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff8139abd0-ffffffff8139ac18: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141e520)
Location: fs/namespace.c:468
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:vfs_utimes
  - fs/init.c:init_chown
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - io_uring/io_uring.c:io_setxattr
  - io_uring/io_uring.c:io_fsetxattr
```
**Symbols:**

```
ffffffff8141e520-ffffffff8141e5a7: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814aacb0)
Location: fs/namespace.c:583
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:vfs_utimes
  - fs/init.c:init_chown
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
```
**Symbols:**

```
ffffffff814aacb0-ffffffff814aad37: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814dfab0)
Location: fs/namespace.c:478
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:vfs_utimes
  - fs/init.c:init_chown
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
```
**Symbols:**

```
ffffffff814dfab0-ffffffff814dfb37: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81512a50)
Location: fs/namespace.c:485
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:vfs_utimes
  - fs/init.c:init_chown
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
```
**Symbols:**

```
ffffffff81512a50-ffffffff81512ad7: mnt_drop_write (STB_GLOBAL)
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
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b49e8)
Location: fs/namespace.c:444
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - ipc/mqueue.c:__arm64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffff8000103b49e8-ffff8000103b4a3c: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0592bc0)
Location: fs/namespace.c:444
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:utimes_common
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_open
```
**Symbols:**

```
c0592bc0-c0592c08: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b0e00)
Location: fs/namespace.c:444
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
c0000000004b0e00-c0000000004b0e74: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027751a)
Location: fs/namespace.c:444
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_open
```
**Symbols:**

```
ffffffe00027751a-ffffffe000277570: mnt_drop_write (STB_GLOBAL)
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
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f9be0)
Location: fs/namespace.c:444
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812f9be0-ffffffff812f9c01: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ea800)
Location: fs/namespace.c:444
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812ea800-ffffffff812ea821: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f79d0)
Location: fs/namespace.c:444
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812f79d0-ffffffff812f79f1: mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81308ce0)
Location: fs/namespace.c:444
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81308ce0-ffffffff81308d26: mnt_drop_write (STB_GLOBAL)
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
