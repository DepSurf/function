# Function: <code>mnt_want_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122d620)
Location: fs/namespace.c:382
Inline: True
Direct callers:
  - kernel/acct.c:SyS_acct
  - fs/open.c:vfs_truncate
  - fs/open.c:chmod_common
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_lchown
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
  - ipc/mqueue.c:SyS_mq_unlink
```
**Symbols:**

```
ffffffff8122d620-ffffffff8122d66b: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81255df0)
Location: fs/namespace.c:382
Inline: True
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
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:utimes_common
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff81255df0-ffffffff81255e3b: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812691e0)
Location: fs/namespace.c:381
Inline: True
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
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:utimes_common
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff812691e0-ffffffff8126922b: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81276980)
Location: fs/namespace.c:382
Inline: True
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
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:utimes_common
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81276980-ffffffff812769cb: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812992d0)
Location: fs/namespace.c:382
Inline: True
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
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:utimes_common
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812992d0-ffffffff8129931b: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bf160)
Location: fs/namespace.c:382
Inline: True
Direct callers:
  - kernel/acct.c:acct_on
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
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
ffffffff812bf160-ffffffff812bf1b2: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d4430)
Location: fs/namespace.c:353
Inline: True
Direct callers:
  - kernel/acct.c:acct_on
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
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
ffffffff812d4430-ffffffff812d4482: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f1940)
Location: fs/namespace.c:350
Inline: True
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
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
ffffffff812f1940-ffffffff812f1992: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813034f0)
Location: fs/namespace.c:350
Inline: True
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
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
ffffffff813034f0-ffffffff81303542: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133d200)
Location: fs/namespace.c:350
Inline: True
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_tmpfile
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:utimes_common
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff8133d200-ffffffff8133d250: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813490c0)
Location: fs/namespace.c:350
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:do_tmpfile
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/init.c:init_chown
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff813490c0-ffffffff81349155: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134fac0)
Location: fs/namespace.c:371
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/init.c:init_chown
  - fs/quota/quota.c:__ia32_sys_quotactl_path
  - fs/quota/quota.c:__ia32_sys_quotactl_path
  - fs/quota/quota.c:__x64_sys_quotactl_path
  - fs/quota/quota.c:__x64_sys_quotactl_path
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff8134fac0-ffffffff8134fb55: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139de20)
Location: fs/namespace.c:372
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/init.c:init_chown
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff8139de20-ffffffff8139deb5: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81420e20)
Location: fs/namespace.c:389
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/init.c:init_chown
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - io_uring/io_uring.c:io_setxattr
  - io_uring/io_uring.c:io_fsetxattr
```
**Symbols:**

```
ffffffff81420e20-ffffffff81420ee3: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814ad440)
Location: fs/namespace.c:504
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/init.c:init_chown
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
```
**Symbols:**

```
ffffffff814ad440-ffffffff814ad503: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e2220)
Location: fs/namespace.c:399
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/init.c:init_chown
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
```
**Symbols:**

```
ffffffff814e2220-ffffffff814e22e3: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81512f00)
Location: fs/namespace.c:405
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/utimes.c:vfs_utimes
  - fs/init.c:init_chown
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
```
**Symbols:**

```
ffffffff81512f00-ffffffff81512fc3: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b6a30)
Location: fs/namespace.c:350
Inline: True
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - ipc/mqueue.c:__arm64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffff8000103b6a30-ffff8000103b6a94: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c05950cc)
Location: fs/namespace.c:350
Inline: True
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
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
c05950cc-c0595120: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b3280)
Location: fs/namespace.c:350
Inline: True
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
c0000000004b3280-c0000000004b331c: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe0002795de)
Location: fs/namespace.c:350
Inline: True
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_setxattr
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_open
```
**Symbols:**

```
ffffffe0002795de-ffffffe00027963a: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fbad0)
Location: fs/namespace.c:350
Inline: True
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
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
ffffffff812fbad0-ffffffff812fbb22: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ec6f0)
Location: fs/namespace.c:350
Inline: True
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
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
ffffffff812ec6f0-ffffffff812ec742: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f98c0)
Location: fs/namespace.c:350
Inline: True
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
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
ffffffff812f98c0-ffffffff812f9912: mnt_want_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mnt_want_write(struct vfsmount *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130abe0)
Location: fs/namespace.c:350
Inline: True
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:chmod_common
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
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
ffffffff8130abe0-ffffffff8130ac32: mnt_want_write (STB_GLOBAL)
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
